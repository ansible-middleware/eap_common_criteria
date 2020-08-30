# eap_common_criteria

[![Build Status](https://github.com/ansible-middleware/eap_common_criteria/workflows/CI/badge.svg?branch=master)](https://github.com/ansible-middleware/eap_common_criteria/actions?workflow=CI)

A set of Ansible roles that checks that a JBoss EAP setup is compliant with Common Criteria recommendations

## Prerequisites

Install the dependencies

```
$ ansible-galaxy collection install -r requirements.yml
```

## Execute Compliance Check

1. Populate [inventory](inventory) with the targeted hosts
2. Execute playbook

```
$ ansible-playbook -i inventory playbook.yml
```