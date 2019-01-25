# ufw

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-ufw.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-ufw)

Ansible role for ufw

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.ufw`

# Default settings

```

ufw_rules_allow_ports: [22, 80, 443]
ufw_banned_ip: []
ufw_allowed_connections: []

graylog_collector_outputs: []
app_servers: []
game_servers: []

```

# Development

Please check [development guide](DEVELOPMENT.md) for details about developing and testing this role.
