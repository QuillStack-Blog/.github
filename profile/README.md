
<div align="center">
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0E7490&height=200&section=header&text=QuillStack&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=&descAlignY=65" alt="QuillStack Banner"/>
</p>
  <p>一款基于 Next.js 构建的 <strong>更轻、更快、更美观</strong> 的静态博客模板</p>
  <p>开源组织：<a href="https://github.com/QuillStack-Blog">QuillStack-Blog</a> | 核心仓库：<a href="https://github.com/QuillStack-Blog/QuillStack">QuillStack</a></p>
  <br/>
</div>
<!-- 徽章区 -->
<p align="center">
  <img src="https://img.shields.io/badge/Next.js--black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/React--61DAFB?style=flat-square&logo=react" />
  <img src="https://img.shields.io/badge/TypeScript--3178C6?style=flat-square&logo=typescript" />
  <img src="https://img.shields.io/badge/TailwindCSS--38B2AC?style=flat-square&logo=tailwind-css" />
  <img src="https://img.shields.io/badge/Status-开发中-orange?style=flat-square" />
</p>

## 组织简介
**QuillStack-Blog** 是专注于维护「QuillStack」静态博客模板的开源组织，该模板由 `SnowBall-Bqiu` 发起，基于 Next.js 构建，专为个人开发者、技术博主打造，兼顾性能与视觉体验，支持灵活的自定义配置和标准的 Markdown 文章管理。

目前核心源码正逐步上传至组织仓库，本仓库为 QuillStack 博客模板的核心开发与分发载体，欢迎关注、试用和贡献代码。

## 组织核心仓库
| 仓库名 | 仓库地址 | 核心用途 |
|--------|----------|----------|
| QuillStack | [https://github.com/QuillStack-Blog/QuillStack](https://github.com/QuillStack-Blog/QuillStack) | 主模板仓库，包含完整的 Next.js 项目代码、配置文件、文章管理逻辑 |
| web-site | [https://github.com/QuillStack-Blog/web-site](https://github.com/QuillStack-Blog/web-site) | 模板配套演示站点，基于 TypeScript 开发 |

## 快速开始
### 环境要求
- Node.js 18+
- npm / yarn / pnpm（推荐pnpm）

### 核心命令
先克隆核心模板仓库：
```bash
# 克隆仓库
git clone https://github.com/QuillStack-Blog/QuillStack.git
# 进入项目目录
cd QuillStack
```

执行项目操作：
```bash
# 安装依赖
npm install

# 启动开发环境（热更新）
npm run dev

# 构建生产版本
npm run build

# 启动生产服务
npm run start
```

## 项目目录结构
QuillStack 遵循 Next.js 最新目录规范，结构清晰、职责分离，核心目录结构如下：
```
QuillStack/
├── content/          # 核心配置与文章目录【重点】
│   ├── settings.json # 全局站点配置文件
│   ├── sitedoc.json  # 所有文章的元数据配置
│   └── doc/          # Markdown 文章存储目录
├── src/              # 开发源码目录
│   ├── app/          # Next.js 路由与页面组件
│   ├── components/   # 通用 React 组件（公共组件）
│   └── lib/          # 工具函数、通用逻辑
├── public/           # 静态资源目录（图片、图标、静态文件）
└── package.json      # 项目依赖与脚本配置
```

## 开发与贡献
目前 QuillStack 源码正**逐步上传**中，暂未开放完整的贡献流程，后续将完善 Issue 模板、PR 规范和代码评审机制。

若你在使用过程中发现问题、有功能建议，可通过以下方式参与：
1. 在 [核心仓库](https://github.com/QuillStack-Blog/QuillStack) 提交 Issue，清晰描述问题/需求；
2. 关注组织仓库更新，待源码全部上传后，可 Fork 仓库并提交 PR；
3. 欢迎在 Discussion 区交流使用心得、定制技巧。

### 贡献须知
- 提交代码需遵循代码风格规范（后续补充）；
- 新功能需附带简单的使用说明；
- Bug 修复需提供复现步骤和验证方案。

## 联系我们
- 开源组织：[QuillStack-Blog](https://github.com/QuillStack-Blog)
- 核心模板仓库：[QuillStack](https://github.com/QuillStack-Blog/QuillStack)
- 发起者：[SnowBall-Bqiu](https://github.com/SnowBall-Bqiu)
- 邮箱：[quillstack@outlook.com](mailto:quillstack@outlook.com)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0E7490&height=100&section=footer"/>
</p>
