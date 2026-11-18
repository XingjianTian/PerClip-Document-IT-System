# 团队章程

[English](team-charter.md) | 中文

> 本译文用于辅助理解；团队协作请以英文 Google Docs 为准。

PerClip RAG Document Management System | Document Management System | Group 2 | UECS6013

## 1. 团队名称

**Group 2 — PerClip Document Management Team**  
**选定项目：** PerClip RAG Document Management System（类别：*Document Management System*）

本章程明确了五名团队成员在交付 PerClip 首次发布过程中的团队治理、角色问责、沟通规范与工作标准——PerClip 是一款包含自托管文档档案库与 Android 客户端的系统，支持标题搜索及带原文出处链接的检索增强生成（RAG；Lewis et al., 2020），涵盖从需求定义到向 IT 运维移交的全过程。

## 2. 团队成员

PerClip 文档管理团队由五名成员组成，分别负责项目管理、系统开发、质量核验与运维移交工作：

| 角色 | 姓名 | 学号 | 邮箱 / 联系方式 |
| --- | --- | --- | --- |
| Team Leader | Xingjian Tian | \_\_\_\_\_\_\_\_\_\_ | xingjian@graduate.utm.my |
| Member | Li Chunze | \_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Lin Zhihua | \_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Tan Shirong | \_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Zhang Shuai | \_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

## 3. 技能与知识

为将项目任务与个人专长相匹配并明确同伴支持需求，每名成员须在下方填写核心技术与管理能力：

| 成员 | 核心技能与领域知识 |
| --- | --- |
| **Xingjian Tian** | IT 项目整合与治理、敏捷/Scrum 协调、利益相关者沟通、PMBOK 流程管理 |
| **Li Chunze** | 需求工程、范围基准制定、用户故事地图、业务价值与 MOV 指标设计 |
| **Lin Zhihua** | WBS 与关键路径排期、Python/FastAPI 后端开发、RAG 与向量索引架构 |
| **Tan Shirong** | 成本估算与预算控制、风险登记表评估、资源配置、运维支持分析 |
| **Zhang Shuai** | 软件质量保障、验收测试设计（UAT）、检索性能审计、版本发布移交 |

*技能协同策略：* 当 Android 采集、自托管归档、RAG 段落检索或成本与进度控制等专业工作由特定成员牵头时，各领域负责人将与指定同伴审查人结对协作，确保全队理解端到端系统设计及发布决策依据。

## 4. 角色与职责

遵循《PMBOK 指南》的团队治理与价值交付原则（Project Management Institute, 2021），每名成员负责一个专属项目领域，并担任相关联领域的同伴审查人。四个项目阶段的规划总工作量为 90 人时（每人 18 小时）：

| 成员 | 主要项目角色与交付物 | 同伴审查分工 |
| --- | --- | --- |
| **Xingjian Tian** *(Team Leader)* | 项目总体协调，统筹终端用户、IT 运维与项目发起人之间的对齐，负责团队章程治理、沟通与变更日志、文档整合及展示开场与总结。 | 审查质量与验收计划 |
| **Li Chunze** *(Requirements & Scope Lead)* | 问题定义、用户检索任务、范围边界（Android 采集、归档、标题搜索与来源链接 RAG）及 60 秒检索基准（MOV）。 | 审查利益相关者与章程一致性 |
| **Lin Zhihua** *(Schedule & WBS Lead)* | 工作分解结构（WBS）、任务依赖关系、里程碑跟踪，以及跨 Android 客户端、自托管档案库与 RAG 管线的工作流协调。 | 审查需求与范围 |
| **Tan Shirong** *(Cost & Risk Lead)* | 资源规划、分阶段成本估算（MYR 2,585 基准）与后续运维支持成本分析，以及项目风险登记表。 | 审查 WBS 与项目进度 |
| **Zhang Shuai** *(Quality & Closure Lead)* | 质量标准、对比检索用时测试、与系统管理员共同开展上线前 RAG 中断降级核验，以及向 IT 运维的移交。 | 审查预算与风险登记表 |

## 5. 商定的会议时间

| 会议类型 | 安排与时间（MYT / UTC+8） | 目的 |
| --- | --- | --- |
| **Weekly Sync** | 每周四 20:00 MYT（按需） | 评审周度进展、解决阻碍事项并对齐后续任务。 |
| **Kickoff Meeting** | 2026 年 11 月 13 日 20:00 MYT | 确认角色分工、技能矩阵与沟通渠道。 |
| **Gate Review 1** | 2026 年 11 月 18 日 20:00 MYT | Project Proposal 与 Team Charter 基准评审。 |
| **Gate Review 2** | 2026 年 12 月 4 日 20:00 MYT | Project Charter 整合与发布就绪评审。 |
| **Presentation Rehearsal** | 2026 年 12 月 9 日 20:00 MYT | 12 月 10 日展示前的全员五人合练与问答准备。 |

*会议规范：* 每次例会前至少 12 小时，各章节负责人须发布简短更新，说明已完成工作、剩余工时及阻碍事项。会议作出的所有决策须记录责任人与截止日期。

## 6. 商定的会议地点

- **主要线上渠道：** Google Meet（按次生成会议链接）
- **线下地点（如适用）：** UTM Faculty of Computing Level 5 Meeting Room
- **共享工作区：** 使用共享 Google Docs 与受版本控制的 GitHub 仓库开展协同撰稿、议题跟踪与同伴审查。

## 7. 团队沟通

- **日常协调：** 使用专属群聊渠道（微信群 / WeChat group）进行快速同步、日程协调和阻碍提醒。凡涉及变更范围、进度或交付物的群聊结论，须正式记入团队决策日志。
- **任务与文档跟踪：** 工作事项通过共享任务看板 / GitHub Issues 跟踪，文档更新须经过结构化同伴审查后方可合入主稿。
- **响应时间标准：** 成员须在 **24 小时内** 确认常规消息与审查请求；影响临近里程碑的紧急阻碍须在**当天**提出。
- **利益相关者升级与里程碑交付：** 影响范围、资源或验收标准的跨领域问题，由组长汇总并与项目发起人及学术评审人沟通。组长（或指定代表）负责各里程碑交付包的统一正式提交。

## 8. 团队规则与期望

### 8.1 团队目标

1. 按期完成全体五名成员参与的 Task 1（Proposal 与 Team Charter，11 月 20 日）、Task 2（Project Charter，12 月 8 日）及小组展示（12 月 10 日）。
2. 将 PerClip 首次发布聚焦于 60 秒检索基准、RAG 中断降级核验与 IT 运维移交。

### 8.2 团队价值观

- **问责与透明：** 对负责的交付物全权负责，及早暴露阻碍事项。
- **建设性同伴审查：** 24 小时内提供可执行的审查反馈，并基于核验后的检索指标与成本估算作出决策。

### 8.3 团队道德准则

- **准确报告与署名：** 如实汇报进展、成本与测试结果，如实认可实际贡献，并按 APA 第七版格式引用文献。
- **数据隐私：** 严禁将 API 密钥、凭据及私密文件放入共享仓库或文档中。

### 8.4 运行规则与冲突解决

- **审查与变更控制：** 在关口日期前提交草稿；涉及范围、进度或预算的变更须在评估交付影响后取得团队共识。
- **逾期与升级：** 进度滞后时立即通知组长并商定补救计划；未决僵局记录备选方案后上报项目发起人或学术评审人。

## 9. 签名

每位成员在下方签名，即确认已审阅并同意本《团队章程》所规定的角色分工、沟通标准与治理规则。

| 角色 | 姓名 | 签名 | 日期 |
| --- | --- | --- | --- |
| Team Leader | Xingjian Tian | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ | 18/11/2026 |
| Member | Li Chunze | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Lin Zhihua | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Tan Shirong | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_ |
| Member | Zhang Shuai | \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ | \_\_\_\_\_\_\_\_\_\_\_\_\_\_ |

## 参考文献

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).
