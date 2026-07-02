# Sevoniva

[中文](#中文) | [English](#english)

Sevoniva maintains public repositories for data platforms, MCP servers, Codex skills, workflow automation, and delivery tooling.

Sevoniva 维护数据平台、MCP 服务、Codex skills、流程自动化和交付工具相关的公开仓库。

## Core Repositories / 核心仓库

| Repository | Area | What it is for | Start here |
| --- | --- | --- | --- |
| [oceanbase-mcp](https://github.com/sevoniva/oceanbase-mcp) | MCP / OceanBase | Read-only OceanBase metadata discovery, SQL access, ER export, and local MCP client integration. | [Docs](https://github.com/sevoniva/oceanbase-mcp#documentation--文档) |
| [skills](https://github.com/sevoniva/skills) | Codex skills | Reusable skills for local development, automation workflows, repository work, and repeatable agent tasks. | [Repository](https://github.com/sevoniva/skills) |
| [Crest](https://github.com/sevoniva/Crest) | BI platform | Datasets, dashboards, reports, and BI project management. | [README](https://github.com/sevoniva/Crest#readme) |
| [cogniflow](https://github.com/sevoniva/cogniflow) | ChatBI | Natural-language data questions, SQL generation, chart rendering, and conversation analysis. | [README](https://github.com/sevoniva/cogniflow#readme) |
| [Koravo](https://github.com/sevoniva/Koravo) | Workflow | Flowable-based process automation, data orchestration, approvals, and runtime inspection. | [README](https://github.com/sevoniva/Koravo#readme) |
| [Nivora](https://github.com/sevoniva/Nivora) | Delivery | CI/CD, GitOps, deployment planning, release audit, artifacts, and operational APIs. | [README](https://github.com/sevoniva/Nivora#readme) |

## 中文

Sevoniva 是一个以工程实践为主的开源组织，仓库集中在数据平台、MCP、Codex skills、流程自动化和交付工具几个方向。这个首页作为公开入口，帮助访问者快速判断每个项目的用途、成熟度和入口文档。

### 项目地图

| 方向 | 代表仓库 | 说明 |
| --- | --- | --- |
| MCP 服务 | [oceanbase-mcp](https://github.com/sevoniva/oceanbase-mcp) | OceanBase 只读 MCP 服务，支持元数据发现、SQL 查询、ER 图、数据字典和 OpenCode 接入。 |
| Codex skills | [skills](https://github.com/sevoniva/skills) | 面向 Codex 的可复用 skills，用于沉淀本地开发、自动化、代码库协作和重复任务。 |
| BI 与数据分析 | [Crest](https://github.com/sevoniva/Crest), [cogniflow](https://github.com/sevoniva/cogniflow) | 覆盖数据集、仪表盘、报表、SQL 生成、图表渲染和对话分析。 |
| 流程与编排 | [Koravo](https://github.com/sevoniva/Koravo) | 基于 Flowable 的流程自动化平台，包含流程模型、审批、任务和运行态查看。 |
| 研发交付 | [Nivora](https://github.com/sevoniva/Nivora) | 面向 CI/CD、GitOps、部署、制品、发布审计和运维接口的交付工具。 |
| 应用与工具 | [Memorica](https://github.com/sevoniva/Memorica), [NivaHome](https://github.com/sevoniva/NivaHome), [attendance](https://github.com/sevoniva/attendance) | 知识记录、家庭自动化、考勤和业务工具实验。 |
| 文档 | [apidocs](https://github.com/sevoniva/apidocs), [sevoniva.github.io](https://github.com/sevoniva/sevoniva.github.io) | API 文档、公开文档和站点资料。 |

### 推荐入口

| 想做什么 | 看这里 |
| --- | --- |
| 接入 OceanBase 到 MCP 客户端 | [oceanbase-mcp](https://github.com/sevoniva/oceanbase-mcp) |
| 找 Codex skills 或自动化工作流 | [skills](https://github.com/sevoniva/skills) |
| 看 BI、报表和仪表盘能力 | [Crest](https://github.com/sevoniva/Crest) |
| 看自然语言到 SQL 和图表分析 | [cogniflow](https://github.com/sevoniva/cogniflow) |
| 看流程、审批和数据编排 | [Koravo](https://github.com/sevoniva/Koravo) |
| 看交付、发布、GitOps 和审计 | [Nivora](https://github.com/sevoniva/Nivora) |
| 看公开计划 | [Sevoniva Roadmap](https://github.com/orgs/sevoniva/projects/1) |

### 核心项目说明

#### oceanbase-mcp

- 做什么：把 OceanBase 元数据、只读 SQL、ER 图、数据字典和变更分析暴露给 MCP 客户端。
- 适合谁：需要在 OpenCode、Codex 或其他 MCP 客户端里查看 OceanBase schema、表结构、关系路径和样例数据的开发者。
- 重点能力：本地 stdio、远程 HTTP、MySQL/Oracle 模式、schema/table/column 策略、审计日志、输出大小限制和部署模板。
- 入口：[文档](https://github.com/sevoniva/oceanbase-mcp#documentation--文档) · [示例](https://github.com/sevoniva/oceanbase-mcp/tree/main/examples)

#### skills

- 做什么：沉淀可复用的 Codex skills，把常见研发、自动化、代码库协作流程写成可重复执行的工作单元。
- 适合谁：经常在本地用 Codex 处理项目维护、文档整理、发布检查、代码审查和自动化任务的开发者。
- 重点能力：技能目录、任务说明、可复用脚本、上下文约束和面向项目的执行约定。
- 入口：[仓库](https://github.com/sevoniva/skills)

#### Crest

- 做什么：面向 BI 场景的数据集、仪表盘、报表和项目管理平台。
- 适合谁：需要维护数据集、制作报表、管理仪表盘和组织分析资产的团队。
- 重点能力：数据集管理、报表配置、仪表盘编排、权限与项目协作、前后端一体化交付。
- 入口：[README](https://github.com/sevoniva/Crest#readme)

#### cogniflow

- 做什么：从自然语言问题到 SQL、查询结果、图表渲染和对话分析的 ChatBI 服务。
- 适合谁：需要让业务问题进入数据查询流程，并保留 SQL 校验、审计和运行状态观察的团队。
- 重点能力：指标匹配、SQL 生成、结果分析、图表体系、对话上下文和质量门禁。
- 入口：[README](https://github.com/sevoniva/cogniflow#readme)

#### Koravo

- 做什么：基于 Flowable 的流程自动化与数据编排平台。
- 适合谁：需要建模审批流程、任务流、流程实例和运行态查看的团队。
- 重点能力：流程模型、审批任务、运行态接口、流程验证、数据编排和示例流程。
- 入口：[README](https://github.com/sevoniva/Koravo#readme)

#### Nivora

- 做什么：面向研发交付的 CI/CD、GitOps、部署计划、制品、发布审计和运维接口。
- 适合谁：需要把流水线、部署、发布记录和审计信息放进同一条交付链路的团队。
- 重点能力：PipelineRun、DeploymentRun、GitOps/Argo CD 基础、制品绑定、发布编排、审计事件和运行接口。
- 入口：[README](https://github.com/sevoniva/Nivora#readme)

### 按标签浏览

[mcp](https://github.com/orgs/sevoniva/repositories?q=topic%3Amcp) ·
[oceanbase](https://github.com/orgs/sevoniva/repositories?q=topic%3Aoceanbase) ·
[codex-skills](https://github.com/orgs/sevoniva/repositories?q=topic%3Acodex-skills) ·
[business-intelligence](https://github.com/orgs/sevoniva/repositories?q=topic%3Abusiness-intelligence) ·
[dashboard](https://github.com/orgs/sevoniva/repositories?q=topic%3Adashboard) ·
[workflow](https://github.com/orgs/sevoniva/repositories?q=topic%3Aworkflow) ·
[devops](https://github.com/orgs/sevoniva/repositories?q=topic%3Adevops) ·
[gitops](https://github.com/orgs/sevoniva/repositories?q=topic%3Agitops) ·
[documentation](https://github.com/orgs/sevoniva/repositories?q=topic%3Adocumentation)

### 协作入口

- [Roadmap](https://github.com/orgs/sevoniva/projects/1) - 公开项目计划和维护方向。
- [Support](https://github.com/sevoniva/.github/blob/main/SUPPORT.md) - 问题咨询和 issue 入口。
- [Security](https://github.com/sevoniva/.github/blob/main/SECURITY.md) - 安全问题私密报告方式。
- [Contributing](https://github.com/sevoniva/.github/blob/main/CONTRIBUTING.md) - 贡献和 pull request 规范。
- [Code of Conduct](https://github.com/sevoniva/.github/blob/main/CODE_OF_CONDUCT.md) - 公开协作规则。

### 人员

| 姓名 | GitHub | 地点 | 角色 |
| --- | --- | --- | --- |
| [Carson](https://github.com/iscarson) | [@iscarson](https://github.com/iscarson) | Shanghai, China | Sevoniva 创始人与维护者。 |
| [callum](https://github.com/liangml) | [@liangml](https://github.com/liangml) | 未公开 | 维护者与开发者。 |
| [hannshusei](https://github.com/hannshusei) | [@hannshusei](https://github.com/hannshusei) | 未公开 | 维护者与开发者。 |

## English

Sevoniva is an engineering-focused open-source organization. The repositories here cover data platforms, MCP servers, Codex skills, workflow automation, and delivery tooling. This page is the public entry point for finding the right project and the right documentation quickly.

### Project Map

| Area | Repositories | Description |
| --- | --- | --- |
| MCP servers | [oceanbase-mcp](https://github.com/sevoniva/oceanbase-mcp) | Read-only MCP server for OceanBase metadata, SQL access, ER diagrams, data dictionaries, and OpenCode integration. |
| Codex skills | [skills](https://github.com/sevoniva/skills) | Reusable Codex skills for local development, automation, repository work, and repeatable tasks. |
| BI and analytics | [Crest](https://github.com/sevoniva/Crest), [cogniflow](https://github.com/sevoniva/cogniflow) | Datasets, dashboards, reports, SQL generation, chart rendering, and conversation analysis. |
| Workflow orchestration | [Koravo](https://github.com/sevoniva/Koravo) | Flowable-based workflow platform for process models, approvals, tasks, and runtime inspection. |
| Delivery tooling | [Nivora](https://github.com/sevoniva/Nivora) | CI/CD, GitOps, deployment planning, release audit, artifacts, and operations APIs. |
| Applications and tools | [Memorica](https://github.com/sevoniva/Memorica), [NivaHome](https://github.com/sevoniva/NivaHome), [attendance](https://github.com/sevoniva/attendance) | Knowledge records, home automation, attendance, and business-tool experiments. |
| Documentation | [apidocs](https://github.com/sevoniva/apidocs), [sevoniva.github.io](https://github.com/sevoniva/sevoniva.github.io) | API documentation, public documentation, and site materials. |

### Recommended Entry Points

| Need | Repository |
| --- | --- |
| Connect OceanBase to MCP clients | [oceanbase-mcp](https://github.com/sevoniva/oceanbase-mcp) |
| Find Codex skills and automation workflows | [skills](https://github.com/sevoniva/skills) |
| Review BI, dashboards, and reporting | [Crest](https://github.com/sevoniva/Crest) |
| Review natural-language SQL and chart analysis | [cogniflow](https://github.com/sevoniva/cogniflow) |
| Review workflow, approvals, and orchestration | [Koravo](https://github.com/sevoniva/Koravo) |
| Review delivery, release, GitOps, and audit work | [Nivora](https://github.com/sevoniva/Nivora) |
| Review public plans | [Sevoniva Roadmap](https://github.com/orgs/sevoniva/projects/1) |

### Repository Profiles

#### oceanbase-mcp

- Purpose: expose OceanBase metadata, read-only SQL, ER diagrams, data dictionaries, and change analysis to MCP clients.
- Audience: developers who need to inspect OceanBase schemas, tables, relationships, and sample rows from OpenCode, Codex, or another MCP client.
- Focus: local stdio, remote HTTP, MySQL/Oracle modes, schema/table/column policy, audit logs, output-size limits, and deployment templates.
- Entry: [Docs](https://github.com/sevoniva/oceanbase-mcp#documentation--文档) · [Examples](https://github.com/sevoniva/oceanbase-mcp/tree/main/examples)

#### skills

- Purpose: collect reusable Codex skills for common development, automation, repository, and documentation workflows.
- Audience: developers who use Codex locally for maintenance work, release checks, code review, documentation, and repeatable tasks.
- Focus: skill catalog, task instructions, reusable scripts, context rules, and project-specific working agreements.
- Entry: [Repository](https://github.com/sevoniva/skills)

#### Crest

- Purpose: BI platform for datasets, dashboards, reports, and project management.
- Audience: teams that maintain datasets, produce reports, manage dashboards, and organize analytics assets.
- Focus: dataset management, report configuration, dashboard composition, permissions, project collaboration, and full-stack delivery.
- Entry: [README](https://github.com/sevoniva/Crest#readme)

#### cogniflow

- Purpose: ChatBI service for natural-language questions, SQL generation, query results, chart rendering, and conversation analysis.
- Audience: teams that want business questions to enter a data-query workflow with SQL checks, audit records, and runtime visibility.
- Focus: metric matching, SQL generation, result analysis, chart catalog, conversation context, and quality gates.
- Entry: [README](https://github.com/sevoniva/cogniflow#readme)

#### Koravo

- Purpose: Flowable-based workflow automation and data orchestration platform.
- Audience: teams that model approvals, task flows, process instances, and runtime inspection.
- Focus: process models, approval tasks, runtime APIs, process validation, data orchestration, and sample processes.
- Entry: [README](https://github.com/sevoniva/Koravo#readme)

#### Nivora

- Purpose: delivery tooling for CI/CD, GitOps, deployment planning, artifacts, release audit, and operations APIs.
- Audience: teams that need pipelines, deployment plans, release records, and audit information in one delivery workflow.
- Focus: PipelineRun, DeploymentRun, GitOps/Argo CD foundations, artifact binding, release orchestration, audit events, and runtime APIs.
- Entry: [README](https://github.com/sevoniva/Nivora#readme)

### Browse By Topic

[mcp](https://github.com/orgs/sevoniva/repositories?q=topic%3Amcp) ·
[oceanbase](https://github.com/orgs/sevoniva/repositories?q=topic%3Aoceanbase) ·
[codex-skills](https://github.com/orgs/sevoniva/repositories?q=topic%3Acodex-skills) ·
[business-intelligence](https://github.com/orgs/sevoniva/repositories?q=topic%3Abusiness-intelligence) ·
[dashboard](https://github.com/orgs/sevoniva/repositories?q=topic%3Adashboard) ·
[workflow](https://github.com/orgs/sevoniva/repositories?q=topic%3Aworkflow) ·
[devops](https://github.com/orgs/sevoniva/repositories?q=topic%3Adevops) ·
[gitops](https://github.com/orgs/sevoniva/repositories?q=topic%3Agitops) ·
[documentation](https://github.com/orgs/sevoniva/repositories?q=topic%3Adocumentation)

### Contribution Links

- [Roadmap](https://github.com/orgs/sevoniva/projects/1) - Public project directions and maintenance work.
- [Support](https://github.com/sevoniva/.github/blob/main/SUPPORT.md) - Where to ask questions or open project issues.
- [Security](https://github.com/sevoniva/.github/blob/main/SECURITY.md) - How to report security issues privately.
- [Contributing](https://github.com/sevoniva/.github/blob/main/CONTRIBUTING.md) - Contribution and pull request guidelines.
- [Code of Conduct](https://github.com/sevoniva/.github/blob/main/CODE_OF_CONDUCT.md) - Rules for public collaboration spaces.

### People

| Name | GitHub | Location | Role |
| --- | --- | --- | --- |
| [Carson](https://github.com/iscarson) | [@iscarson](https://github.com/iscarson) | Shanghai, China | Founder and maintainer of Sevoniva. |
| [callum](https://github.com/liangml) | [@liangml](https://github.com/liangml) | Not listed | Maintainer and developer. |
| [hannshusei](https://github.com/hannshusei) | [@hannshusei](https://github.com/hannshusei) | Not listed | Maintainer and developer. |
