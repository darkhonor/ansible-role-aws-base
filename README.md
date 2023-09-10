# Ansible Role AWS Baseline

Apply baseline configuration to an EC2 instance on AWS

## Requirements

None

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

None

## Example Playbook

Here is a sample playbook to apply this role to:

```yaml
---
- name: Configure Blog AMI
  hosts: default
  become: true
  roles:
    - name: darkhonor.aws_base
```

## License

MIT

## Author Information

Alex Ackerman, X @darkhonor
