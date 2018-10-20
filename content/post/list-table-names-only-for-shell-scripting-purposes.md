---
title: "List Table Names Only for Shell Scripting Purposes"
date: 2018-10-15T12:42:34+08:00
draft: false
---
```
mysql -s --skip-column-names  -ne "use DB_to_Use; show tables;"
```
