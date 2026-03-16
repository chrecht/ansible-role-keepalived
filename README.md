# ansbile-role-keepalived
=========

## Use this role

add to your requirements.yaml:
```
---
roles:
  - name: ansible-role-keepalived
    src: git@github.com:chrecht/ansible-role-keepalived.git
    scm: git
    version: v0.0.1
```

then install the role:
`ansible-galaxy install -f -r requirements.yaml`

## Example
Full example can be found in the `example/` directory.
