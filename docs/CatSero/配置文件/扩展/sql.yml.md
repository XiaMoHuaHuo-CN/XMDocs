---
title: sql.yml
---
# sql.yml

```yaml
# CatSero QQ SQL Config
# Generate by CatSero v@plugin.version@

# JDBC
jdbc:
  # SQLite JDBC class名称
  sqlite-class-name: "org.sqlite.JDBC"
  # MySQL JDBC class名称
  mysql-class-name: "com.mysql.jdbc.Driver"

# 数据储存方法
# sqlite | mysql
type: sqlite
# MySQL设置
mysql-config:
  # 地址
  host: localhost
  # 端口
  port: 3306
  # 用户名
  username: catsero
  # 密码
  password: 123456
  # 数据库名
  database: catsero
  # 时区
  timezone: "Asia/Shanghai"
  # 使用Unicode
  unicode: true
  # 数据库编码格式
  encoding: "UTF-8"
  # 使用SSL连接
  ssl: false
```