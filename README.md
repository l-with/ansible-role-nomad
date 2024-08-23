# Ansible Role Nomad

The role installs nomad.

## Role Variables

<!-- markdownlint-disable MD033 -->
| group | variable | default | description |
| --- | --- | --- | --- |
| basic | `nomad_install_method` | `'service'` | the install method, supported methods are `'service'` |
| basic | `nomad_install` | `true` | if nomad should be installed |
