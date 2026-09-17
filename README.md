# StudyOS

StudyOS 是一个面向个人的学习与知识管理系统，也是一个长期的软件工程学习项目。

它将从基础 Web 开发开始，逐步成长为一个结合 **Full-Stack + AI + RAG + Agent + Deployment** 能力的个人学习操作系统。

> 当前仓库已经停止作为 freeCodeCamp fork 使用。后续开发将全部围绕 StudyOS 展开。

## 为什么做这个项目

我希望通过一个真实、持续迭代的软件项目，把学习记录、学习计划、项目实践和知识积累连接起来，而不是只停留在零散教程或一次性练习上。

StudyOS 同时承担两个角色：

- 一个可以实际使用的个人学习系统
- 一个长期的软件工程学习与实践载体

## 项目目标

- 管理个人学习记录、任务和项目进度
- 用真实业务学习前端、后端、数据库和部署
- 逐步加入 AI、知识库、RAG 和 Agent 能力
- 保持每个阶段简单、清晰、可运行、可理解
- 通过需求、设计、实现、运行、测试和迭代完成学习闭环

## 核心功能

第一阶段计划实现：

- **Dashboard**：今日学习情况、当前任务、最近记录、项目进度和统计
- **学习记录**：创建、查看、编辑、删除，按分类和时间查看
- **学习计划**：创建任务、查看任务、修改任务、标记完成和删除任务
- **项目记录**：管理项目简介、技术栈、阶段、状态、进度和时间

后续逐步增加：

- 用户注册、登录和权限控制
- AI 总结、知识点提取、复习问题和学习建议
- 个人知识库与 RAG 检索
- 能读取和修改学习数据的 Agent
- 测试、Docker、Linux、Nginx 和公网部署

## 技术栈

### 当前起点

- HTML
- CSS
- JavaScript
- localStorage

### 目标技术路线

- **Frontend**：React、TypeScript、Vite
- **Backend**：Python、FastAPI
- **Database**：PostgreSQL
- **AI**：LLM API
- **Knowledge**：Embedding、Vector Database、RAG
- **Agent**：Tool Calling、Agent Workflow
- **Engineering**：Git、Testing、Docker、Linux、Nginx、Deployment

不会在早期无实际需求时引入微服务、Kubernetes、消息队列或复杂的分布式架构。

## 当前项目状态

**Phase 0：项目初始化 — 🟨 进行中**

当前重点是完成仓库重建、项目文档和第��阶段的开发准备。代码实现将按照阶段逐步加入，不提前堆叠未来技术。

## Roadmap

| 阶段 | 内容 | 状态 |
| --- | --- | --- |
| Phase 0 | 项目初始化 | 🟨 进行中 |
| Phase 1 | 前端 MVP | ⬜ 未开始 |
| Phase 2 | React + TypeScript | ⬜ 未开始 |
| Phase 3 | FastAPI | ⬜ 未开始 |
| Phase 4 | PostgreSQL | ⬜ 未开始 |
| Phase 5 | 前后端联调 | ⬜ 未开始 |
| Phase 6 | 用户系统 | ⬜ 未开始 |
| Phase 7 | AI | ⬜ 未开始 |
| Phase 8 | RAG | ⬜ 未开始 |
| Phase 9 | Agent | ⬜ 未开始 |
| Phase 10 | 测试与工程化 | ⬜ 未开始 |
| Phase 11 | Docker | ⬜ 未开始 |
| Phase 12 | Linux + 部署 | ⬜ 未开始 |

状态说明：`⬜ 未开始`、`🟨 进行中`、`✅ 已完成`。

## 项目架构

### 当前架构

```text
Browser
  ↓
Frontend
  ↓
HTML + CSS + JavaScript
  ↓
localStorage
```

### 后续架构

```text
Browser
  ↓
React + TypeScript
  ↓ HTTP
FastAPI
  ↓
PostgreSQL
```

### 长期目标架构

```text
React
  ↓
FastAPI
  ↓
PostgreSQL
  ↓
AI Service
  ↓
Vector Store
  ↓
Agent
```

架构会根据真实需求逐步演进，不提前把未来设计全部实现或固化。

## 本地运行

当前��目初始化阶段不依赖复杂构建系统。完成前端 MVP 后，将优先支持使用浏览器或简单静态服务器运行：

```bash
cd frontend
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

具体运行方式会随着项目阶段更新。

## 开发方式

每次迭代遵循：

```text
需求
↓
设计
↓
最小实现
↓
运行
↓
测试
↓
记录问题
↓
学习并解决
↓
继续迭代
```

开发原则：

1. 增量开发：每次只解决当前阶段的问题。
2. 保持可运行：完成每个阶段后项目都应能够运行。
3. 保持可理解：代码服务于学习，避免难以理解的过度抽象。
4. 不过度工程化：优先选择简单、清晰、可维护的方案。
5. 不偷换技术：如需改变既定技术路线，必须在文档中记录原因。

## 学习目标

- 掌握 HTML、CSS、JavaScript 和浏览器基础
- 理解 React、TypeScript 和前端组件化
- 学习 HTTP、REST API、FastAPI 和后端开发
- 学习 SQL、PostgreSQL、ORM 和数据库设计
- 理解认证、测试、错误处理和工程化流程
- 实践 AI API、RAG、向量检索和 Agent 工具调用
- 学习 Docker、Linux、Nginx 和部署
- 建立清晰的 Git 提交与长期项目维护习惯

## 项目目录

随着项目逐步实现，目录将按实际需要增长。目标结构如下：

```text
StudyOS/
├── frontend/
├── backend/
├── docs/
│   ├── PROJECT_PLAN.md
│   ├── ARCHITECTURE.md
│   └── LEARNING.md
├── .gitignore
└── README.md
```

不为了“看起来完整”提前创建没有实际用途的空目录或配置。

## 文档

- [项目学习计划](docs/PROJECT_PLAN.md)
- [系统架构](docs/ARCHITECTURE.md)
- [学习日志](docs/LEARNING.md)

## 后续计划

1. 完成项目初始化和文档
2. 使用原生 HTML/CSS/JavaScript 完成前端 MVP
3. 迁移到 React + TypeScript + Vite
4. 建立 FastAPI REST API
5. 接入 PostgreSQL，实现真正的数据持久化
6. 增加用户系统
7. 在已有业务数据之上加入 AI
8. 建立知识库、RAG 和 Agent 能力
9. 补充测试、Docker、Linux 和公网部署

StudyOS 的最终目标不是一次性实现所有技术，而是通过持续的真实开发，把它逐步建设成我的个人学习系统、全栈学习项目、AI 学习项目和长期软件工程实践项目。
