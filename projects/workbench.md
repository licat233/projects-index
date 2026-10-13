# Workbench

工作台，包含客户端与服务端

[← 项目总索引](https://github.com/licat233/projects-index) · [原 CODING 项目](https://licat.coding.net/p/workbench)

## 组件仓库

| 组件 | GitHub 仓库 | 技术标识 | 来源 | 开发文档 |
|---|---|---|---|---|
| 客户端 | [workbench-client](https://github.com/licat233/workbench-client) | React / Umi | 现有 GitHub 仓库，包含 CODING 历史 | [README](https://github.com/licat233/workbench-client/blob/main/README.md) |
| 服务端 | [workbench-server](https://github.com/licat233/workbench-server) | Go 1.18 | 现有 GitHub 仓库，包含 CODING 历史 | [README](https://github.com/licat233/workbench-server/blob/main/README.md) |

## 克隆组件

登录 GitHub CLI 后，可在本地项目目录中分别克隆所需组件。

```bash
gh repo clone licat233/workbench-client
gh repo clone licat233/workbench-server
```

## 开发入口

从上表的组件 README 开始，按各仓库文档安装依赖、准备配置并启动。

以下脚本名称来自组件默认分支的 `package.json`；依赖版本与参数以仓库文件为准。

| 仓库 | 已定义的 npm scripts |
|---|---|
| [workbench-client](https://github.com/licat233/workbench-client/blob/main/package.json) | `dev`、`serve`、`start`、`build` |

## 项目检索

项目标签：`project-workbench`。

在 GitHub 仓库搜索中输入 `user:licat233 topic:project-workbench` 可查找已标注的组件。私有仓库需要登录并具备访问权限；已归档的相关版本可从上表直接进入。
