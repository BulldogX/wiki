---
title: "pip"
layout: page
date: 2018-04-09 10:27
---

[TOC]

#pip

1. pip 安装包  

 `pip install xxx`

2. pip查看已安装的包（包括安装路径等详细信息）

 `pip show --files xxx`

3. 检查哪些包需要更新

 `pip list --outdated `

4. pip卸载包

 `pip uninstall xxx`

5. 参数解释

```
# pip --help

Usage:

pip [options]

Commands:

install                     安装包.

uninstall                   卸载包.

freeze                      按着一定格式输出已安装包列表

list                        列出已安装包.

show                        显示包详细信息.

search                      搜索包，类似yum里的search.

wheel                       Build wheels from your requirements.

zip                         不推荐. Zip individual packages.

unzip                       不推荐. Unzip individual packages.

bundle                      不推荐. Create pybundles.

help                        当前帮助.

General Options:

-h, --help                  显示帮助.

-v, --verbose               更多的输出，最多可以使用3次

-V, --version               现实版本信息然后退出.

-q, --quiet                 最少的输出.

--log-file            覆盖的方式记录verbose错误日志，默认文件：/root/.pip/pip.log

--log                 不覆盖记录verbose输出的日志.

--proxy              Specify a proxy in the form [user:passwd@]proxy.server:port.

--timeout              连接超时时间 (默认15秒).

--exists-action     Default action when a path already exists: (s)witch, (i)gnore, (w)ipe, (b)ackup.

--cert                证书.

```