---
date: '2020-02-07T17:15:26.000Z'
author: wivwiv
keywords: null
description: null
category: null
ref: null
---

# command-line

EMQ X 提供了 `emqx` 命令行工具，方便用户对 EMQ X 进行启动、关闭、进入控制台等操作。

* `emqx start`

  后台启动 EMQ X Broker；

* `emqx stop`

  关闭 EMQ X Broker；

* `emqx restart`

  重启 EMQ X Broker；

* `emqx console`

  使用控制台启动 EMQ X Broker；

* `emqx foreground`

  使用控制台启动 EMQ X Broker，与 `emqx console` 不同，`emqx foreground` 不支持输入 Erlang 命令；

* `emqx ping`

  Ping EMQ X Broker。

以上命令为用户常用命令，此外 `emqx` 命令还有一些[其他选项](../advanced/cli.md)为方便开发者使用，普通用户无需关心。

