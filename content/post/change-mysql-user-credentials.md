---
title: "Change MySQL User Credentials"
date: 2018-04-08T23:20:10+08:00
draft: false
---

For as long as you have root acess to MySQL, this would work:

```
UPDATE mysql.user SET Password=PASSWORD('new-password-here') WHERE USER='user-name-here' AND Host='host-name-here';
```
more details from https://www.cyberciti.biz/faq/mysql-change-user-password/
