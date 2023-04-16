# nvPress概述

nvPress是一个基于nodejs实现的内容管理系统。

功能包括：用户管理、媒体管理、文章管理、主题、插件等。

用于：个人博客、作品集、网站内容展示。

可通过主题、插件来实现功能的二次扩展。

虽然nvPress是免费开放使用的，但源代码并不开放。本项目不包含nvPress的源代码，仅收集使用过程中遇到的错误、BUG。

有任何问题建议先在QQ群讨论确认后再提交issue。

👉 **QQ讨论群：611246443（官方唯一群，仅200人，不定期清理非活跃用户）**
👉 **QQ讨论群：790411996（网友自建群，开发者也在里面哦）**

# 安装使用

详见文档：https://docs.panda-studio.cn:8282/docs/post-19

# 二次开发

详见文档：https://docs.panda-studio.cn:8282/?shelf=nvPress

# 许可说明

nvPress是免费、开放、自主部署的项目，任何人都可以无限制的使用它。但**请不要抄袭它的任何界面！**

# 萌新一键安装

> 注意事项：
>  1. 一键部署方案适用于全新安装，不能在已有宝塔、WordPress、Nginx等现有环境中操作
> 2. 安装过程可能会有10分钟左右，请耐心等待，不要看到命令行没有动静就进行其他操作

### 萌新一键安装命令

1. 服务器选择使用干净的 centOS7 系统（不能自带任何第三方功能）
2. 在命令行或服务商后台运行以下命令即可一键安装

```bash
curl -fsSL http://dsm.panda-studio.cn:8181/shell/nvpress-install.sh | bash -s
```

### 萌新一键升级命令

在使用本页面提供的一键安装的基础上，可以使用下面的命令行一键升级nvPress本身（不含主题）

```bash
curl -fsSL http://dsm.panda-studio.cn:8181/shell/nvpress-update.sh | bash -s
```

其他关于一键安装、一键升级、使用HTTPS（SSL证书）等问题，请加上面的QQ群讨论。
