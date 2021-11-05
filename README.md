## Mysql57 server
---

#### Bastille jail use

```bash
user@machine [/usr/local/jail] #: bastille create mysql-server 13.0-RELEASE 172.18.X.XX
user@machine [/usr/local/jail] #: bastille template mysql-server infracead/mysql
user@machine [/usr/local/jail] #: bastille rdr mysql-server tcp 3307 3306
```

