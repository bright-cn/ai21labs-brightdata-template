<div align="center">

# 🤖 AI21 Maestro + Bright Data 模板

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Node.js 16+](https://img.shields.io/badge/node.js-16+-green.svg)](https://nodejs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![HeroUI](https://img.shields.io/badge/HeroUI-3b82f6?style=flat&logo=react&logoColor=white)](https://heroui.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

🚀 面向生产的 AI 智能体开发模板，内置网页数据访问能力

将 AI21 的 Maestro 平台与 Bright Data 的网页采集能力相结合，构建可研究与分析实时网页数据的强大 AI 智能体。

[快速开始](#快速开始) •
[演示](#演示) •
[API 文档](#api-文档) •
[参与贡献](#参与贡献)

</div>

---

## 📸 演示

### AI 智能体控制台
为不同人格与预算配置并运行 AI 智能体

<img width="1345" alt="AI 智能体控制台 - 配置智能体、查看实时结果并管理运行历史" src="https://github.com/user-attachments/assets/296de2a5-53cb-450b-adf0-699668f4211b" />

### 交互式 API 文档
通过 FastAPI 的自动文档探索并测试全部接口

<img width="1483" alt="FastAPI 交互式文档 - 借助自动校验测试 API 端点" src="https://github.com/user-attachments/assets/ba04140f-0d37-4447-9362-ad8add3c94ad" />

---

## ✨ 特性

| 特性 | 说明 |
|------|------|
| 🤖 AI 智能体控制台 | 为不同人格与预算配置并运行 AI 智能体 |
| 🌐 网页数据访问 | 集成 Bright Data 免费与专业网页采集工具 |
| 📊 实时结果 | 实时观看智能体执行并查看结果 |
| 📝 运行历史 | 以详细日志与结果追踪所有运行 |
| 🎨 优雅界面 | 基于 HeroUI 的现代自适应界面 |
| ⚡ 高性能 API | 基于 FastAPI 的高性能异步后端 |
| 🔒 生产可用 | 环境配置、错误处理与安全最佳实践 |
| 📚 自动文档 | FastAPI 自动生成的交互式 OpenAPI 文档 |

---

## 🛠️ 技术栈

<div align="center">

### 后端
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![AI21](https://img.shields.io/badge/AI21%20Maestro-0066CC?style=for-the-badge)
![Bright Data](https://img.shields.io/badge/Bright%20Data-FF6B35?style=for-the-badge)

### 前端
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</div>

---

## 📋 目录

- [🤖 AI21 Maestro + Bright Data 模板](#ai21-maestro--bright-data-模板)
  - [📸 演示](#演示)
    - [AI 智能体控制台](#ai-智能体控制台)
    - [交互式 API 文档](#交互式-api-文档)
  - [✨ 特性](#特性)
  - [🛠️ 技术栈](#技术栈)
    - [后端](#后端)
    - [前端](#前端)
  - [📋 目录](#目录)
  - [🚀 快速开始](#快速开始)
    - [前置条件](#前置条件)
    - [后端设置](#后端设置)
    - [前端设置](#前端设置)
  - [📖 API 文档](#api-文档)
    - [关键端点](#关键端点)
  - [🔧 可用工具](#可用工具)
    - [🆓 免费工具（快速模式）](#免费工具快速模式)
    - [💎 专业工具（付费）](#专业工具付费)
  - [⚙️ 配置](#配置)
    - [智能体人格](#智能体人格)
    - [预算级别](#预算级别)
    - [环境变量](#环境变量)
  - [🏗️ 项目结构](#项目结构)
  - [🧪 开发](#开发)
    - [后端开发](#后端开发)
    - [前端开发](#前端开发)
  - [🤝 参与贡献](#参与贡献)
    - [开发流程](#开发流程)
    - [拉取请求指南](#拉取请求指南)
  - [📄 许可证](#许可证)
  - [🙏 致谢](#致谢)
  - [🔗 相关链接](#相关链接)

---

## 🚀 快速开始

### 前置条件

开始之前，请确保已安装：

- ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white) Python 3.8 或更高版本
- ![Node.js](https://img.shields.io/badge/Node.js-16+-green?logo=node.js&logoColor=white) Node.js 16 或更高版本
- 🔑 [AI21 Labs API 密钥](https://studio.ai21.com/) - 免费注册
- 🌐 [Bright Data 令牌](https://www.bright.cn/) - 获取网页采集访问权限

### 后端设置

1. 克隆仓库
   ```bash
   git clone https://github.com/bright-cn/ai21labs-brightdata-template
   cd maestro-brightdata
   ```

2. 创建虚拟环境
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows 上使用： .venv\Scripts\activate
   ```

3. 安装依赖
   ```bash
   pip install -r requirements.txt
   ```

4. 配置环境变量
   ```bash
   cp .env.example .env
   # 编辑 .env 并添加你的 API 密钥
   ```

5. 启动 API 服务
   ```bash
   python api_server.py
   ```

   🎉 API 可通过 http://localhost:8000 访问

### 前端设置

1. 进入 UI 目录
   ```bash
   cd ui
   ```

2. 安装依赖
   ```bash
   npm install
   ```

3. 启动开发服务器
   ```bash
   npm run dev
   ```

   🎉 Web 界面可通过 http://localhost:5173 访问

---

## 📖 API 文档

后端启动后，访问 http://localhost:8000/docs 查看由 FastAPI 自动生成的交互式 API 文档（OpenAPI）。

### 关键端点

| 方法 | 路径 | 说明 |
|------|------|------|
| POST | `/run` | 运行具备网页访问能力的 AI 智能体 |
| GET  | `/status/{run_id}` | 获取指定运行的状态 |
| GET  | `/runs` | 列出所有运行及其状态 |
| GET  | `/tools` | 获取可用 Bright Data 工具信息 |
| POST | `/quick-run` | 简化的基础查询端点 |

---

## 🔧 可用工具

### 🆓 免费工具（快速模式）
- 搜索引擎：抓取 Google、Bing 或 Yandex 的搜索结果
- 网页抓取器：从任意网页提取干净的 Markdown

### 💎 专业工具（付费）
- 电商：Amazon、Walmart、eBay、Home Depot、Zara、Etsy、Best Buy
- 社媒：LinkedIn、Instagram、Twitter、TikTok、Facebook
- 商业情报：ZoomInfo、Crunchbase、职位列表
- 浏览器自动化：导航、点击、输入、截图

---

## ⚙️ 配置

### 智能体人格
| 人格 | 描述 |
|------|------|
| Web Researcher | 专注网页数据研究的助理 |
| Data Analyst | 面向数据分析任务的技术助理 |
| Content Creator | 面向内容创作的创意助理 |
| Technical Expert | 提供含来源的技术性详尽回答 |

### 预算级别
| 级别 | 资源 | 适用场景 |
|------|------|----------|
| 低 | 基础计算资源 | 简单查询 |
| 中 | 标准计算资源 | 大多数用例 |
| 高 | 最大计算资源 | 复杂分析 |

### 环境变量

```bash
# 必填
AI21_LABS_KEY=your_ai21_labs_api_key_here
BRIGHTDATA_TOKEN=your_brightdata_token_here

# 选填
PORT=8000
HOST=0.0.0.0
```

---

## 🏗️ 项目结构

```
maestro-brightdata/
├── 📄 api_server.py          # FastAPI 服务
├── 📋 requirements.txt       # Python 依赖
├── 🔧 .env.example          # 环境变量模板
├── 🚫 .gitignore            # Git 忽略规则
├── 📖 README.md             # 本文件
└── 🎨 ui/                   # 前端 React 应用
    ├── 📁 src/
    │   ├── 🧩 components/   # 可复用 UI 组件
    │   ├── 📄 pages/        # 页面组件
    │   ├── ⚙️ config/       # 配置文件
    │   └── 📝 types/        # TypeScript 类型定义
    ├── 📦 package.json      # Node.js 依赖
    └── ⚡ vite.config.ts    # Vite 配置
```

---

## 🧪 开发

### 后端开发
```bash
# 自动重载运行
uvicorn api_server:app --reload --host 0.0.0.0 --port 8000

# 代码格式化
black .
isort .
```

### 前端开发
```bash
cd ui

# 启动带热重载的开发服务器
npm run dev

# 生产构建
npm run build

# 预览生产构建
npm run preview

# 代码检查
npm run lint
```

---

## 🤝 参与贡献

我们欢迎你的参与！无论是：

- 🐛 提交 Bug
- 💡 讨论当前实现
- 🚀 提交修复
- 💫 提出新功能
- 🎯 成为维护者

### 开发流程

1. Fork 本仓库
2. 创建功能分支（`git checkout -b feature/amazing-feature`）
3. 完成功能开发
4. 运行测试与代码检查
5. 提交变更（`git commit -m 'Add some amazing feature'`）
6. 推送到远程（`git push origin feature/amazing-feature`）
7. 提交 Pull Request

### 拉取请求指南

- 遵循现有代码风格
- 为新功能补充测试
- 需要时更新文档
- 确保所有测试通过

---

## 📄 许可证

本项目基于 MIT 许可证开源，详见 [LICENSE](LICENSE)。

```
MIT License - 欢迎将此模板用于你的项目！
```

---

## 🙏 致谢

特别感谢以下优秀团队与项目：

- 🤖 [AI21 Labs](https://ai21.com/) - 强大的 Maestro 平台
- 🌐 [Bright Data](https://www.bright.cn/) - 全面的网页数据采集工具
- 🎨 [HeroUI](https://heroui.com/) - 优雅易用的组件库
- ⚡ [FastAPI](https://fastapi.tiangolo.com/) - 高效卓越的 Web 框架
- ⚛️ [React 团队](https://reactjs.org/) - 出色的前端库
- 🎯 [Vite](https://vitejs.dev/) - 闪电般快速的构建工具

---

## 🔗 相关链接

- 📚 [AI21 Maestro 文档](https://docs.ai21.com/docs/maestro-overview)
- 🌐 [Bright Data 平台文档](https://docs.brightdata.com/)
- 🎨 [HeroUI 组件库](https://heroui.com/docs/guide/introduction)
- ⚡ [FastAPI 文档](https://fastapi.tiangolo.com/)

---

<div align="center">

如果这个模板对你有帮助，欢迎点亮一颗 Star！

[![GitHub stars](https://img.shields.io/github/stars/bright-cn/ai21labs-brightdata-template.svg?style=social&label=Star)](https://github.com/bright-cn/ai21labs-brightdata-template)

由 Bright Data 与 AI21 Labs 社区倾情打造 ❤️

</div>
