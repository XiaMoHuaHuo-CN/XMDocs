---
title: config.yml
---
# config.yml

```yaml
# CatSero Plugin Config
# Generate by CatSero v@plugin.version@

# 语言文件
locale: zh_CN

# bStats
bstats: true

# HTTP API
http-api: false

# Debug日志
debug-log: false

# 检查更新
check-update:
  # 功能开关
  # true | false
  enable: true
  # 检查更新间隔
  # 单位: 秒
  interval: 3600
  # 版本模式
  # latest | dev
  mode: latest
  # 检查更新服务器API地址，一般情况请勿修改
  api-url: https://api.huahuo-cn.tk/mcplugins/CatSero/version
```