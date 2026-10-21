# LuckyDraw

抽奖系统；对应 CODING 的 luckydraw 项目

[← 项目总索引](https://github.com/licat233/projects-index) · [原 CODING 项目](https://licat.coding.net/p/luckydraw)

## 组件仓库

| 组件 | GitHub 仓库 | 技术标识 | 来源 | 开发文档 |
|---|---|---|---|---|
| 管理后台 | [luckydraw-admin](https://github.com/licat233/luckydraw-admin) | React / Umi | 现有 GitHub 仓库，包含 CODING 历史 | [README](https://github.com/licat233/luckydraw-admin/blob/main/README.md) |
| 后端 | [luckydraw-backend](https://github.com/licat233/luckydraw-backend) | Go 1.20 | 现有 GitHub 仓库，包含 CODING 历史 | [README](https://github.com/licat233/luckydraw-backend/blob/main/README.md) |
| H5 前端 | [luckydraw-h5](https://github.com/licat233/luckydraw-h5) | Vue / Vite | 现有 GitHub 仓库，包含 CODING 历史 | [README](https://github.com/licat233/luckydraw-h5/blob/main/README.md) |

## 克隆组件

登录 GitHub CLI 后，可在本地项目目录中分别克隆所需组件。

```bash
gh repo clone licat233/luckydraw-admin
gh repo clone licat233/luckydraw-backend
gh repo clone licat233/luckydraw-h5
```

## 开发入口

从上表的组件 README 开始，按各仓库文档安装依赖、准备配置并启动。

以下脚本名称来自组件默认分支的 `package.json`；依赖版本与参数以仓库文件为准。

| 仓库 | 已定义的 npm scripts |
|---|---|
| [luckydraw-admin](https://github.com/licat233/luckydraw-admin/blob/main/package.json) | `dev`、`serve`、`start`、`build` |
| [luckydraw-h5](https://github.com/licat233/luckydraw-h5/blob/main/package.json) | `dev`、`build` |

## 项目检索

项目标签：`project-luckydraw`。

在 GitHub 仓库搜索中输入 `user:licat233 topic:project-luckydraw` 可查找已标注的组件。所列仓库均已公开，可直接访问；已归档的相关版本也可从上表进入。
