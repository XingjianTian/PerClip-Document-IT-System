# 项目提案

[English](proposal.md) | 中文

## 1. 项目概述

员工在工作中用手机保存 PDF、链接和笔记，再次查找时往往要翻看多个应用和文件夹。PerClip 计划将这些资料归入自托管档案库。员工可在 Android 客户端按标题搜索，也可就文档内容提问。系统采用检索增强生成（RAG）方法，根据检索到的段落生成回答（Lewis 等，2020）。员工可以打开引用的原文核对答案。

员工协助确定实际的查找任务。第 2 组负责与系统管理员制定发布计划，管理员负责访问权限、备份和技术支持。发起人根据预期收益和成本决定是否扩大使用范围。

### 1.1 项目目的

项目旨在缩短员工查找文档的时间。拟定的衡量目标是：五名用户中至少四人能在无人协助的情况下，于 60 秒内找到指定文档。团队会分别记录使用文件夹和 PerClip 完成同类任务的用时。依据《PMBOK 指南》关于价值和衡量的原则，发起人会结合查找结果、支持成本和用户反馈进行评审（Project Management Institute，2021）。

### 1.2 项目范围

**范围内。** 发布计划涵盖 Android 端采集、文档归档、标题搜索、带来源链接的问答，以及员工入门培训和运维交接。发布前，团队将检查 RAG 服务中断时员工是否仍能保存和查找文档。

**范围外。** 首次发布不包括 iOS 客户端、多租户托管或现用机构档案的迁移。

## 2. 参考文献

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).
