# 我的项目驱动学习计划

> 目标：以 freeCodeCamp 的课程为主线，通过完整项目掌握前端、后端、数据库、测试、部署和系统设计，而不是只完成零散练习。
>
> 使用方式：每完成一个阶段，就勾选对应任务；每个项目都必须留下代码、README、测试和复盘记录。

## 总体路线

```text
freeCodeCamp 基础课程
        ↓
小型项目与前端能力
        ↓
完整全栈项目：RealWorld / Medium 类内容平台
        ↓
工程化：测试、Docker、CI/CD、性能与安全
        ↓
原理型项目：Mini Git / Mini Redis / Mini Shell
```

## 学习原则

- [ ] 先理解需求，再开始写代码
- [ ] 每个项目先完成 MVP，再迭代功能
- [ ] 遇到教程时先自己实现，再对照参考答案
- [ ] 每个阶段都提交 Git commit，并写下遇到的问题
- [ ] 不复制粘贴完整项目；参考项目只用于理解设计和查漏补缺
- [ ] 每个完整项目至少包含 README、运行说明��测试和部署说明

## 阶段一：Web 基础

参考：

- [freeCodeCamp Responsive Web Design](https://www.freecodecamp.org/learn/responsive-web-design-v9/)
- [freeCodeCamp JavaScript](https://www.freecodecamp.org/learn/javascript-v9/)
- [MDN Web 文档](https://developer.mozilla.org/zh-CN/)

### 学习内容

- [ ] HTML 语义化与可访问性
- [ ] CSS 盒模型、Flexbox、Grid 和响应式布局
- [ ] JavaScript 基础、模块、异步和 Fetch
- [ ] Git 基础与 GitHub 工作流
- [ ] HTTP、JSON、浏览器开发者工具

### 小型项目

- [ ] 个人作品集页面
- [ ] 响应式技术文档页面
- [ ] JavaScript 计算器
- [ ] Markdown 预览器
- [ ] 天气查询或随机名言应用

**阶段完成标准**：能够独立完成一个响应式前端页面，并调用公开 API 展示数据。

## 阶段二：React 与前端工程化

参考：

- [30 Days of React](https://github.com/Asabeneh/30-Days-Of-React)
- [freeCodeCamp Front-End Development Libraries](https://www.freecodecamp.org/learn/front-end-development-libraries-v9/)

### 学习内容

- [ ] React 组件、Props、State 和 Hooks
- [ ] 路由、表单和数据请求
- [ ] 状态管理与组件拆分
- [ ] TypeScript 基础
- [ ] ESLint、Prettier 和环境变量
- [ ] 加载态、错误态、空状态和移动端适配

### 项目：个人知识库前端

- [ ] 登录页面和用户设置页面
- [ ] 文章列表、详情和编辑页面
- [ ] 标签筛选、搜索和分页
- [ ] Markdown 编辑与预览
- [ ] 基础组件和页面测试

**阶段完成标准**：能够使用 React + TypeScript 独立构建一个多页面前端应用。

## 阶段三：后端、数据库与 API

参考：

- [freeCodeCamp Relational Databases](https://www.freecodecamp.org/learn/relational-databases-v9/)
- [freeCodeCamp Back-End Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis-v9/)
- [Full Stack Open](https://fullstackopen.com/)

建议技术栈：

```text
React + TypeScript
Node.js + Express 或 NestJS
PostgreSQL
Prisma 或其他 ORM
Docker
```

### 学习内容

- [ ] REST API 设计
- [ ] PostgreSQL 表设计、关联、索引和事务
- [ ] 用户注册、登录和密码安全
- [ ] JWT 或 Session 认证
- [ ] 输入校验、错误处理和权限控制
- [ ] 单元测试和 API 集成测试

### 项目：全栈博客系统

- [ ] 用户注册与登录
- [ ] 文章增删改查
- [ ] Markdown 编辑器
- [ ] 评论、点赞和标签
- [ ] 搜索、筛选和分页
- [ ] 管理员后台
- [ ] API 文档
- [ ] ���据库迁移和种子数据

**阶段完成标准**：项目可以在新环境中按照 README 启动，并有可重复执行的测试。

## 阶段四：完整项目复现——RealWorld

参考仓库：

- [RealWorld](https://github.com/realworld-apps/realworld)
- [RealWorld API 规范](https://docs.realworld.show/)

目标：实现一个类似 Medium 的内容平台，并在理解后加入自己的设计。

### 复现步骤

- [ ] 阅读需求和 API 规范，不先看实现代码
- [ ] 设计数据库实体和关系
- [ ] 先完成后端 API
- [ ] 编写认证、文章、评论和用户功能
- [ ] 完成前端页面和状态管理
- [ ] 添加端到端测试
- [ ] 部署一个可访问的演示版本

### 二次扩展

- [ ] 图片上传与对象存储
- [ ] 全文搜索
- [ ] Redis 缓存
- [ ] 邮件或站内通知
- [ ] 内容审核
- [ ] 多角色权限
- [ ] 操作日志

**阶段完成标准**：能够从空目录重新实现核心功能，并解释每个模块的职责和数据流。

## 阶段五：工程化、部署与系统设计

参考：

- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Developer Roadmap](https://roadmap.sh/)

### 工程化清单

- [ ] Docker Compose 本地开发环境
- [ ] GitHub Actions 自动运行 lint、测试和构建
- [ ] 生产环境变量管理
- [ ] 数据库备份与迁移策略
- [ ] 日志、错误追踪和健康检查
- [ ] API 限流和基础安全检查
- [ ] 数据库查询和前端性能优化
- [ ] HTTPS、域名和持续部署

### 系统设计练习

- [ ] 设计 URL Shortener
- [ ] 设计文件上传服务
- [ ] 设计通知系统
- [ ] 设计高并发文章阅读计数
- [ ] 为博客系统绘制架构图和数据流图

## 阶段六：原理型项目

参考：[Build Your Own X](https://github.com/codecrafters-io/build-your-own-x)

按难度逐步选择：

- [ ] Mini HTTP Server
- [ ] Mini Shell
- [ ] Mini Git
- [ ] Mini Redis
- [ ] Mini Docker
- [ ] Mini Database

每个项目需要记录：

- [ ] 要解决的问题
- [ ] 使用的核心数据结构
- [ ] 协议或文件格式
- [ ] 错误处理方式
- [ ] 测试用例
- [ ] 与真实工具的差异

## 项目交付模板

每个项目完成后，必须补充以下内容：

- [ ] 项目简介和功能截图
- [ ] 技术栈和架构图
- [ ] 本地运行步骤
- [ ] 环境变量说明
- [ ] 数据库初始化方式
- [ ] 测试命令和测试覆盖范围
- [ ] 部署地址或运行演示
- [ ] 已知问题和后续计划
- [ ] 学到的内容与踩坑记录

## 当前执行区

### 当前阶段

- 阶段：`阶段一：Web 基础`
- 当前项目：`待开始`
- 本周目标：`完成后再填写`
- 开始日期：`待填写`

### 每周记录

| 周次 | 目标 | 完成内容 | 遇到的问题 | 下一步 |
| --- | --- | --- | --- | --- |
| 第 1 周 |  |  |  |  |
| 第 2 周 |  |  |  |  |
| 第 3 周 |  |  |  |  |
| 第 4 周 |  |  |  |  |

## 推荐执行顺序

1. 完成 freeCodeCamp Responsive Web Design 和 JavaScript 的核心部分
2. 完成 3 个小型前端项目
3. 学习 React + TypeScript，并完成知识库前端
4. 学习数据库和后端，完成全栈博客
5. 复现并扩展 RealWorld
6. 补充测试、Docker、CI/CD 和系统设计
7. 实现 Mini Git、Mini Redis 或 Mini Shell

> 判断是否真正学会的标准：不是“看完教程”，而是能够不看答案解释设计、独立实现、写测试、部署上线，并在需求变化时继续迭代。

---

# 每日执行版（建议直接照做）

> 目标：把大计划拆成每天能执行的任务，避免“看一堆资料但不动手”。
>
> 建议每次学习 90 分钟 - 2 小时，至少 5 天/周，连续 8 周以上。

## 第 1 周：HTML / CSS / JavaScript 语法打底

### 每天任务

- [ ] 第 1 天：HTML 语义��� + 常用标签 + 表单结构
- [ ] 第 2 天：CSS 基础 + 盒模型 + Flexbox + 颜色/边框/间距
- [ ] 第 3 天：CSS Grid + 响应式布局 + 断点布局
- [ ] 第 4 天：JavaScript 基础：变量、函数、数组、对象、条件判断
- [ ] 第 5 天：JavaScript 异步：Promise / async / await / fetch
- [ ] 第 6 天：实战：做一个响应式个人作品集页面
- [ ] 第 7 天：复盘 + Git 提交 + README 记录

### 第 1 周产出

- [ ] 一个能正常展示的个人作品集主页
- [ ] 1 份简短复盘文档
- [ ] 1 次 Git 提交记录

## 第 2 周：JavaScript 深入 + 小项目

### 每天任务

- [ ] 第 1 天：DOM 操作与事件处理
- [ ] 第 2 天：组件化思维：制作计算器
- [ ] 第 3 天：API 调用：天气查询应用
- [ ] 第 4 天：本地存储 + 表单校验
- [ ] 第 5 天：随机名言/待办清单/计时器项目
- [ ] 第 6 天：整合项目并修 bug
- [ ] 第 7 天：总结与再次重构

### 第 2 周产出

- [ ] 2 个小型前端项目
- [ ] 1 个对外 API 调用项目
- [ ] 1 份 README 说明

## 第 3 周：React 入门

### 每天任务

- [ ] 第 1 天：React 介绍 + 创建项目
- [ ] 第 2 天：组件、Props、State
- [ ] 第 3 天：事件处理与列表渲染
- [ ] 第 4 天：Hooks：useState / useEffect / useMemo
- [ ] 第 5 天：路由和页面拆分
- [ ] 第 6 天：做一个知识库/博客前端
- [ ] 第 7 天：修 bug、测试和复盘

### 第 3 周产出

- [ ] 1 个 React 单页应用
- [ ] 至少 3 个页面
- [ ] 组件拆分清晰

## 第 4 周：React 进阶 + TypeScript

### 每天任务

- [ ] 第 1 天：TypeScript 基础
- [ ] 第 2 天：React + TypeScript 组件开发
- [ ] 第 3 天：表单处理与校验
- [ ] 第 4 天：错误处理、加载状态和空状态
- [ ] 第 5 天：点赞、评论和过滤状态
- [ ] 第 6 天：添加测试
- [ ] 第 7 天：复盘和重构

### 第 4 周产出

- [ ] React + TypeScript 项目
- [ ] 组件测试或基础 E2E 测试
- [ ] 1 份设计说明

## 第 5 周：后端 + 数据库

### 每天任务

- [ ] 第 1 天：Node.js / Express 基础环境搭建
- [ ] 第 2 天：REST API 基础设计
- [ ] 第 3 天：PostgreSQL 安装和表设计
- [ ] 第 4 天：用户注册和登录
- [ ] 第 5 天：文章 CRUD
- [ ] 第 6 天：评论和标签模块
- [ ] 第 7 天：API 调试与异常处理

### 第 5 周产出

- [ ] 后端 API 文档
- [ ] 1 份数据库 ER 图
- [ ] 统一的接口返回格式

## 第 6 周：全栈博客 MVP

### 每天任务

- [ ] 第 1 天：前后端联调基础
- [ ] 第 2 天：登录与鉴权
- [ ] 第 3 天：文章列表与详情页
- [ ] 第 4 天：编辑和删除文章
- [ ] 第 5 天：评论、点赞和搜索
- [ ] 第 6 天：后台管理页
- [ ] 第 7 天：部署本地环境并测试

### 第 6 周产出

- [ ] 可运行的全栈博客
- [ ] README 运行步骤
- [ ] 可演示的功能截图

## 第 7 周：RealWorld 复现与扩展

### 每天任务

- [ ] 第 1 天：阅读 API 规范和需求
- [ ] 第 2 天：按需求重写数据库设计
- [ ] 第 3 天：实现用户和认证模块
- [ ] 第 4 天：完成文章和评论模块
- [ ] 第 5 天：完成前端界面和状态管理
- [ ] 第 6 天：补充测试和性能优化
- [ ] 第 7 天：总结与对比原项目

### 第 7 周产出

- [ ] 一个可运行的 Medium 类项目
- [ ] 对照原项目的设计差异说明

## 第 8 周：工程化 / 部署 / 原理型挑战

### 每天任务

- [ ] 第 1 天：Docker 本地部署
- [ ] 第 2 天：GitHub Actions 自动测试
- [ ] 第 3 天：日志与错误追踪
- [ ] 第 4 天：Mini HTTP Server
- [ ] 第 5 天：Mini Shell 或 Mini Git
- [ ] 第 6 天：Redis / 缓存设计
- [ ] 第 7 天：做最后的复盘和总结

### 第 8 周产出

- [ ] 可部署项目
- [ ] 一个底层原理型项目
- [ ] 一份完整自评总结

## 每周复盘模板

- [ ] 本周目标：
- [ ] 完成了什么：
- [ ] 遇到的最大问题：
- [ ] 学到的关键点：
- [ ] 下周要改进的地方：
- [ ] 当前需要保持的习惯：

## 退出条件

你可以认为自己已经真正进入项目驱动学习状态，当满足下列条件：

- [ ] 能独立启动并运行一个完整 Web 项目
- [ ] 能写出前端页面和后端 API
- [ ] 能设计一张数据库表和 3 个主要模块
- [ ] 能解释为什么某个功能要这样设计
- [ ] 能写测试并通过基本验证
- [ ] 能把项目部署到本地或云环境中

> 只要做到“能自己做出东西”，就说明你的学习已经从“看资料”转到了“真正构建产品”。

---

## 直接开始的建议（非常重要）

如果你现在想立刻开始，不要等到计划完全完成，直接从下面选一个你最适合的起点：

### 选项 A：零基础

- freeCodeCamp Responsive Web Design
- freeCodeCamp JavaScript
- 做 3 个前端小项目
- 每天 1 - 2 小时

### 选项 B：有一点基础

- 先做 React
- 再做全栈博客
- 然后 RealWorld

### 选项 C：更偏工程化

- React / TypeScript
- 后端 API
- PostgreSQL
- Docker
- CI/CD
- 最后做 RealWorld

如果你愿意，我下一步可以直接帮你做两件事中的任意一件：

1. 把这个计划拆成“每周 7 天任务表”，可以直接复制到 Notion / Obsidian / GitHub Issue 中执行。
2. 根据你的基础层级，直接生成“第 1 周的具体学习步骤和代码任务清单”。
