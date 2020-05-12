---
title: "MySQL/MariaDB with Credentials File"
date: 2020-02-19T23:11:25+08:00
tags: [mysql, mariadb, authentication, permission, credentials, credentials-file]
draft: false
---

```
mysql --defaults-file=/path/to/credentials.ini  pantheon
```

where credentials.ini has this format:
```
[client]
host=<replace_with_servername_or_ip>
user=<replace_with_db_user>
password=<replace_with_db_password>
```
