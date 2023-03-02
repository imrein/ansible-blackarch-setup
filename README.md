# Black arch ansible setup
My personal setup for a blackarch install on top of base arch.

## Requirements

An existing Arch linux.

## Role Variables

| Variable    | Default | Info                    |
| :---------- | :------ | :---------------------- |
| `packages`  | `[]`    | Hostname of the system  |

## Example playbook

```yml
---
- name: test playbook
  hosts: general

  roles:
  - role: ansible-blackarch-setup
```