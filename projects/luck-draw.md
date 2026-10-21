# Luck Draw

抽奖系统；对应 CODING 的 luck_draw 项目

[← 项目总索引](https://github.com/licat233/projects-index) · [原 CODING 项目](https://licat.coding.net/p/luck_draw)

## 组件仓库

| 组件 | GitHub 仓库 | 技术标识 | 来源 | 开发文档 |
|---|---|---|---|---|
| 管理后台 | [luck-draw-admin](https://github.com/licat233/luck-draw-admin) | React / Umi | CODING 迁入 | [README](https://github.com/licat233/luck-draw-admin/blob/master/README.md) |
| 服务端 | [luck-draw-server](https://github.com/licat233/luck-draw-server) | Go 1.19 | CODING 迁入 | [README](https://github.com/licat233/luck-draw-server/blob/main/README.md) |
| 用户界面 | [coding-luck-draw-ui](https://github.com/licat233/coding-luck-draw-ui) | 源码 / 文件 | CODING 保留版本 | [README](https://github.com/licat233/coding-luck-draw-ui/blob/master/README.md) |

## 相关 GitHub 版本

以下仓库与 CODING 迁入版本分别保留，按来源区分；本入口不指定其中一份为最新版本。

| 组件 | 仓库 | 状态 |
|---|---|---|
| luck_draw-ui | [luck_draw-ui](https://github.com/licat233/luck_draw-ui) | 原有 GitHub 版本 |

## 克隆组件

登录 GitHub CLI 后，可在本地项目目录中分别克隆所需组件。

```bash
gh repo clone licat233/luck-draw-admin
gh repo clone licat233/luck-draw-server
gh repo clone licat233/coding-luck-draw-ui
```

## 开发入口

从上表的组件 README 开始，按各仓库文档安装依赖、准备配置并启动。

以下脚本名称来自组件默认分支的 `package.json`；依赖版本与参数以仓库文件为准。

| 仓库 | 已定义的 npm scripts |
|---|---|
| [luck-draw-admin](https://github.com/licat233/luck-draw-admin/blob/master/package.json) | `dev`、`serve`、`start`、`build` |

## 项目检索

项目标签：`project-luck-draw`。

在 GitHub 仓库搜索中输入 `user:licat233 topic:project-luck-draw` 可查找已标注的组件。所列仓库均已公开，可直接访问；已归档的相关版本也可从上表进入。
