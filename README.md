<div align="center">

# 🤖 AI21 Maestro + Bright Data 模板

[![许可证：MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/) [![Node.js 16+](https://img.shields.io/badge/node.js-16+-green.svg)](https://nodejs.org/) [![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)](https://fastapi.tiangolo.com/) [![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactjs.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![HeroUI](https://img.shields.io/badge/HeroUI-3b82f6?style=flat&logo=react&logoColor=white)](https://heroui.com/) [![欢迎提交 PR](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**🚀 用于构建可访问网络的 AI 智能体的生产就绪模板**

*将 AI21 的 Maestro 平台与 Bright Data 的网页爬虫能力相结合，创建可研究和分析实时网络数据的强大 AI 智能体。*

[快速入门](#-快速开始) • [演示](#-演示) • [文档](#-api-文档) • [参与贡献](#-参与贡献)

</div>

---

## 📸 演示

### AI 智能体控制面板
*配置并运行具有不同个性和预算的 AI 智能体*

<img width="1345" alt="AI 智能体控制面板 - 配置智能体、查看实时结果并管理运行历史记录" src="https://github.com/user-attachments/assets/296de2a5-53cb-450b-adf0-699668f4211b" />

### 交互式 API 文档 
*使用 FastAPI 自动生成的文档探索并测试所有端点*

<img width="1483" alt="FastAPI 交互式文档 - 通过自动验证测试 API 端点" src="https://github.com/user-attachments/assets/ba04140f-0d37-4447-9362-ad8add3c94ad" />

---

## ✨ 功能

| 功能 | 说明 |
|---------|-------------|
| 🤖 **AI 智能体控制面板** | 配置并运行具有不同个性和预算的 AI 智能体 |
| 🌐 **网络数据访问** | 集成 Bright Data 的免费及专业网页爬虫工具 |
| 📊 **实时结果** | 观察智能体的工作过程，并实时查看结果 |
| 📝 **运行历史记录** | 通过详细日志和结果跟踪智能体的所有运行记录 |
| 🎨 **精美 UI** | 使用 HeroUI 组件构建的现代化响应式界面 |
| ⚡ **高速 API** | 支持异步操作的高性能 FastAPI 后端 |
| 🔒 **生产就绪** | 环境配置、错误处理和安全最佳实践 |
| 📚 **自动生成文档** | 通过 FastAPI 自动生成 OpenAPI 交互式 API 文档 |

---

## 🛠️ 技术栈

<div align="center">

### 后端
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![AI21](https://img.shields.io/badge/AI21%20Maestro-0066CC?style=for-the-badge) ![Bright Data](https://img.shields.io/badge/Bright%20Data-FF6B35?style=for-the-badge)

### 前端
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

</div>

---

## 📋 目录

- [🤖 AI21 Maestro + Bright Data 模板](#-ai21-maestro--bright-data-模板)
  - [📸 演示](#-演示)
    - [AI 智能体控制面板](#ai-智能体控制面板)
    - [交互式 API 文档](#交互式-api-文档)
  - [✨ 功能](#-功能)
  - [🛠️ 技术栈](#️-技术栈)
    - [后端](#后端)
    - [前端](#前端)
  - [📋 目录](#-目录)
  - [🚀 快速开始](#-快速开始)
    - [前置要求](#前置要求)
    - [后端设置](#后端设置)
    - [前端设置](#前端设置)
  - [📖 API 文档](#-api-文档)
    - [主要端点](#主要端点)
  - [🔧 可用工具](#-可用工具)
    - [🆓 免费工具（快速模式）](#-免费工具快速模式)
    - [💎 专业工具（高级版）](#-专业工具高级版)
  - [⚙️ 配置](#️-配置)
    - [智能体个性](#智能体个性)
    - [预算级别](#预算级别)
    - [环境变量](#环境变量)
  - [🏗️ 项目结构](#️-项目结构)
  - [🧪 开发](#-开发)
    - [后端开发](#后端开发)
    - [前端开发](#前端开发)
  - [🤝 参与贡献](#-参与贡献)
    - [开发流程](#开发流程)
    - [Pull Request 指南](#pull-request-指南)
  - [📄 许可证](#-许可证)
  - [🙏 致谢](#-致谢)
  - [🔗 实用链接](#-实用链接)

---

## 🚀 快速开始

### 前置要求

开始之前，请确保已安装以下软件：

- ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white) Python 3.8 或更高版本
- ![Node.js](https://img.shields.io/badge/Node.js-16+-green?logo=node.js&logoColor=white) Node.js 16 或更高版本
- 🔑 [AI21 Labs API 密钥](https://studio.ai21.com/) - 免费注册
- 🌐 [Bright Data 令牌](https://www.bright.cn/) - 获取网页爬虫访问权限

### 后端设置

1. **克隆仓库**
   ```bash
   git clone https://github.com/bright-cn/ai21labs-brightdata-template
   cd maestro-brightdata
   ```

2. **创建虚拟环境**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **安装依赖项**
   ```bash
   pip install -r requirements.txt
   ```

4. **配置环境**
   ```bash
   cp .env.example .env
   # Edit .env and add your API keys
   ```

5. **启动 API 服务器**
   ```bash
   python api_server.py
   ```

   🎉 **API 将在 `http://localhost:8000` 上可用**

### 前端设置

1. **进入 UI 目录**
   ```bash
   cd ui
   ```

2. **安装依赖项**
   ```bash
   npm install
   ```

3. **启动开发服务器**
   ```bash
   npm run dev
   ```

   🎉 **Web 界面将在 `http://localhost:5173` 上可用**

---

## 📖 API 文档

后端运行后，访问 **`http://localhost:8000/docs`** 即可查看由 FastAPI 自动生成 OpenAPI 的交互式 API 文档。

### 主要端点

| 方法 | 端点 | 说明 |
|--------|----------|-------------|
| `POST` | `/run` | 运行可访问网络的 AI 智能体 |
| `GET` | `/status/{run_id}` | 获取特定运行任务的状态 |
| `GET` | `/runs` | 列出所有运行任务及其状态 |
| `GET` | `/tools` | 获取可用 Bright Data 工具的相关信息 |
| `POST` | `/quick-run` | 用于基本查询的简化端点 |

---

## 🔧 可用工具

### 🆓 免费工具（快速模式）
- **搜索引擎** - 从 Google、Bing 或 Yandex 抓取搜索结果
- **网页抓取工具** - 从任意网页提取整洁的 Markdown

### 💎 专业工具（高级版）
- **电商** - Amazon、Walmart、eBay、Home Depot、Zara、Etsy、Best Buy
- **社交媒体** - LinkedIn、Instagram、Twitter、TikTok、Facebook
- **商业智能** - ZoomInfo、Crunchbase、职位列表
- **浏览器自动化** - 浏览、点击、输入、截屏

---

## ⚙️ 配置

### 智能体个性
| 个性 | 说明 |
|-------------|-------------|
| **网络研究员** | 专注于网络数据研究的实用助手 |
| **数据分析师** | 处理数据分析任务的技术助手 |
| **内容创作者** | 用于内容生成的创意助手 |
| **技术专家** | 提供包含来源的详细技术回答 |

### 预算级别
| 级别 | 资源 | 适用场景 |
|-------|-----------|----------|
| **低** | 基础计算 | 简单查询 |
| **中** | 标准计算 | 大多数使用场景 |
| **高** | 最高计算能力 | 复杂分析 |

### 环境变量

```bash
# Required
AI21_LABS_KEY=your_ai21_labs_api_key_here
BRIGHTDATA_TOKEN=your_brightdata_token_here

# Optional
PORT=8000
HOST=0.0.0.0
```

---

## 🏗️ 项目结构

```
maestro-brightdata/
├── 📄 api_server.py          # FastAPI server
├── 📋 requirements.txt       # Python dependencies
├── 🔧 .env.example          # Environment variables template
├── 🚫 .gitignore            # Git ignore rules
├── 📖 README.md             # This file
└── 🎨 ui/                   # Frontend React app
    ├── 📁 src/
    │   ├── 🧩 components/   # Reusable UI components
    │   ├── 📄 pages/        # Page components
    │   ├── ⚙️ config/       # Configuration files
    │   └── 📝 types/        # TypeScript type definitions
    ├── 📦 package.json      # Node.js dependencies
    └── ⚡ vite.config.ts    # Vite configuration
```

---

## 🧪 开发

### 后端开发
```bash
# Run with auto-reload
uvicorn api_server:app --reload --host 0.0.0.0 --port 8000

# Format code
black .
isort .
```

### 前端开发
```bash
cd ui

# Development server with hot reload
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Lint code
npm run lint
```

---

## 🤝 参与贡献

我们非常期待你的参与！无论是以下哪种方式，我们都希望让参与此项目的贡献过程尽可能简单、透明：

- 🐛 报告错误
- 💡 讨论代码的当前状态
- 🚀 提交修复
- 💫 提议新功能
- 🎯 成为维护者

### 开发流程

1. Fork 仓库
2. 创建功能分支（`git checkout -b feature/amazing-feature`）
3. 进行更改
4. 运行测试和代码检查
5. 提交更改（`git commit -m 'Add some amazing feature'`）
6. 推送到分支（`git push origin feature/amazing-feature`）
7. 创建 Pull Request

### Pull Request 指南

- 遵循现有代码风格
- 为新功能添加测试
- 根据需要更新文档
- 确保所有测试均通过

---

## 📄 许可证

本项目采用 MIT 许可证，详情请参阅 [LICENSE](LICENSE) 文件。

```
MIT License - feel free to use this template for your own projects!
```

---

## 🙏 致谢

特别感谢成就此模板的优秀团队和项目：

- 🤖 [**AI21 Labs**](https://ai21.com/) - 提供强大的 Maestro 平台
- 🌐 [**Bright Data**](https://www.bright.cn/) - 提供全面的网络数据采集工具
- 🎨 [**HeroUI**](https://heroui.com/) - 提供美观且无障碍的组件库
- ⚡ [**FastAPI**](https://fastapi.tiangolo.com/) - 提供出色且快速的 Web 框架
- ⚛️ [**React 团队**](https://reactjs.org/) - 提供卓越的前端库
- 🎯 [**Vite**](https://vitejs.dev/) - 提供极速构建工具

---

## 🔗 实用链接

- 📚 [AI21 Maestro 文档](https://docs.ai21.com/docs/maestro-overview)
- 🌐 [Bright Data 平台文档](https://docs.brightdata.com/)
- 🎨 [HeroUI 组件库](https://heroui.com/docs/guide/introduction)
- ⚡ [FastAPI 文档](https://fastapi.tiangolo.com/)

---

<div align="center">

**⭐ 如果此模板对你有所帮助，请考虑点亮一颗星！**

[![GitHub 星标](https://img.shields.io/github/stars/brightdata/ai21labs-brightdata-template.svg?style=social&label=Star)](https://github.com/bright-cn/ai21labs-brightdata-template)

由 Bright Data 和 AI21 Labs 社区用 ❤️ 打造

</div>