# Ansible Infrastructure Automation Framework

Enterprise-oriented Ansible framework for Windows server provisioning and application stack deployment.

## Current framework standard

Roles follow a consistent lifecycle:

1. Validate
2. Prepare
3. Deploy / Configure
4. Verify
5. Summary

## Roles

- common_windows
- folders
- java
- erlang
- rabbitmq
- firewall
- env_variables
- app_service

## Repository structure

```
ansible-infra/
├── ansible.cfg
├── inventories/
├── playbooks/
└── roles/
    ├── common_windows/
    ├── folders/
    ├── java/
    ├── erlang/
    ├── rabbitmq/
    ├── firewall/
    ├── env_variables/
    └── app_service/
```

## Configuration direction

The framework is being evolved toward an enterprise configuration data model where reusable role logic is separated from environment-, customer-, application-, host-, and security-specific configuration.

## Branching

Feature work is developed on dedicated branches and promoted through review before reaching `main`.
