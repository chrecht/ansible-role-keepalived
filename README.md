Config in hostvar
=========

```
keepalived:
    notification_email:
        - me@domain.tld
    instances:
        - name: "proxysql_1"
          priority: 101
          iface: ens160
          state: BACKUP
          router_id: 13
          vip: 172.31.31.16
        - name: "proxysql_2"
          priority: 100
          iface: ens160
          state: BACKUP
          router_id: 14
          vip: 172.31.31.17
```
