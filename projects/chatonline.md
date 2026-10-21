# ChatOnline

在线聊天系统，包含服务端、Web、Android、iOS 和配套组件

[← 项目总索引](https://github.com/licat233/projects-index) · [原 CODING 项目](https://licat.coding.net/p/chatonline)

## 组件仓库

| 组件 | GitHub 仓库 | 技术标识 | 来源 | 开发文档 |
|---|---|---|---|---|
| 管理后台 | [chatonline-admin](https://github.com/licat233/chatonline-admin) | Vue / Vite | CODING 迁入 | [README](https://github.com/licat233/chatonline-admin/blob/main/README.md) |
| Android 客户端 | [chatonline-android](https://github.com/licat233/chatonline-android) | Android / Gradle | CODING 迁入 | [README](https://github.com/licat233/chatonline-android/blob/master/README.md) |
| 部署配置 | [chatonline-deploy](https://github.com/licat233/chatonline-deploy) | 源码 / 文件 | CODING 迁入 | [README](https://github.com/licat233/chatonline-deploy/blob/main/README.MD) |
| 即时通讯引擎 | [chatonline-im](https://github.com/licat233/chatonline-im) | Go 1.18 | CODING 迁入 | [README](https://github.com/licat233/chatonline-im/blob/main/README.md) |
| iOS 客户端 | [chatonline-ios](https://github.com/licat233/chatonline-ios) | iOS / Xcode | CODING 迁入 | [README](https://github.com/licat233/chatonline-ios/blob/main/README.md) |
| 客服客户端 | [chatonline-kefu-client](https://github.com/licat233/chatonline-kefu-client) | 源码 / 文件 | CODING 迁入 | [README](https://github.com/licat233/chatonline-kefu-client/blob/main/README.md) |
| Go 公共库 | [chatonline-lib](https://github.com/licat233/chatonline-lib) | Go 1.20 | CODING 迁入 | [README](https://github.com/licat233/chatonline-lib/blob/main/README.md) |
| 业务服务端 | [chatonline-server](https://github.com/licat233/chatonline-server) | Go 1.20 | CODING 迁入 | [README](https://github.com/licat233/chatonline-server/blob/main/README.md) |
| Web 客户端 | [chatonline-web](https://github.com/licat233/chatonline-web) | Turborepo | CODING 迁入 | [README](https://github.com/licat233/chatonline-web/blob/main/README.md) |

## 克隆组件

登录 GitHub CLI 后，可在本地项目目录中分别克隆所需组件。

```bash
gh repo clone licat233/chatonline-admin
gh repo clone licat233/chatonline-android
gh repo clone licat233/chatonline-deploy
gh repo clone licat233/chatonline-im
gh repo clone licat233/chatonline-ios
gh repo clone licat233/chatonline-kefu-client
gh repo clone licat233/chatonline-lib
gh repo clone licat233/chatonline-server
gh repo clone licat233/chatonline-web
```

## 开发入口

从上表的组件 README 开始，按各仓库文档安装依赖、准备配置并启动。

以下脚本名称来自组件默认分支的 `package.json`；依赖版本与参数以仓库文件为准。

| 仓库 | 已定义的 npm scripts |
|---|---|
| [chatonline-admin](https://github.com/licat233/chatonline-admin/blob/main/package.json) | `dev`、`build` |
| [chatonline-web](https://github.com/licat233/chatonline-web/blob/main/package.json) | `dev`、`build` |

## 项目检索

项目标签：`project-chatonline`。

在 GitHub 仓库搜索中输入 `user:licat233 topic:project-chatonline` 可查找已标注的组件。所列仓库均已公开，可直接访问；已归档的相关版本也可从上表进入。
