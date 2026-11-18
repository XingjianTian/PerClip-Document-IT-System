# 项目提案

[English](proposal.md) | 中文

## 1. 项目概述

员工在日常工作中经常用手机保存 PDF、链接和笔记，导致重要资料散落在不同应用和文件夹里，事后查找耗时费力。PerClip 旨在将这些资料集中归入自托管档案库。其 Android 客户端支持按标题搜索，并采用检索增强生成（RAG）技术根据检索到的段落回答问题（Lewis et al., 2020），用户可直接打开引用的原文段落核对信息来源。

作为一项面向组织落地的 IT 系统，PerClip 涉及四类核心利益相关者：终端用户、开发团队、IT 运维以及项目发起人。部门员工与知识工作者（终端用户）在日常工作中使用应用保存和检索资料，协助定义真实的查找任务并反馈使用体验；项目经理与开发团队在既定范围和周期内构建并测试 Android 客户端、归档服务与 RAG 管线；IT 运维与系统管理员在系统移交后负责服务托管、访问权限、数据备份与日常技术支持；项目发起人与管理层提供资源保障，并根据上线成效决定是否在更大范围内推广部署。

### 1.1 项目目的

本项目旨在减少员工在零散移动应用与文件夹之间反复查找文档的时间，并为管理层评估是否扩大组织内部部署提供清晰、循证的决策依据。项目的核心目标是：五名用户中至少有四人能在无人协助的情况下，于 60 秒内找到指定文档。开发团队将通过对比同一日常查找任务在普通文件夹与 PerClip 中的完成用时来评估这一指标。依据《PMBOK 指南》关于价值交付与度量衡量的原则（Project Management Institute, 2021），项目发起人将在批准扩大推广前，综合检索用时、用户反馈、入门培训投入以及后续运维支持成本作出决策。

### 1.2 项目范围

**范围内：**
- Android 端资料采集（PDF、网页链接与文本笔记）及自托管归档。
- 标题搜索与带直接原文段落链接的 RAG 问答。
- 用户入门材料、访问控制配置、备份规程以及向 IT 运维的移交。
- 上线前与系统管理员共同核验：当 RAG 服务不可用时，用户仍能正常保存文档并按标题检索。

**范围外：**
- iOS 客户端开发。
- 多租户云托管。
- 企业级单点登录（SSO）集成。
- 现有第三方档案库的自动迁移。

## 2. 参考文献

Asai, A., Wu, Z., Wang, Y., Sil, A., & Hajishirzi, H. (2024). [Self-RAG: Learning to retrieve, generate, and critique through self-reflection](https://arxiv.org/abs/2310.11511). *International Conference on Learning Representations (ICLR 2024)*.

Edge, D., Trinh, H., Cheng, N., Bradley, J., Chao, A., Mody, A., Truitt, S., & Larson, J. (2024). [From local to global: A graph RAG approach to query-focused summarization](https://arxiv.org/abs/2404.16130). *arXiv preprint arXiv:2404.16130*.

Gao, Y., Xiong, Y., Gao, X., Jia, K., Pan, J., Bi, Y., Dai, Y., Sun, J., & Wang, H. (2023). [Retrieval-augmented generation for large language models: A survey](https://arxiv.org/abs/2312.10997). *arXiv preprint arXiv:2312.10997*.

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).

Shi, W., Min, S., Yasunaga, M., Seo, M., James, R., Lewis, M., Zettlemoyer, L., & Yih, W.-t. (2024). [REPLUG: Retrieval-augmented black-box language models](https://arxiv.org/abs/2301.12652). *Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2024)*.

Yan, S.-Q., Gu, J.-C., Zhu, Y., & Ling, Z.-H. (2024). [Corrective retrieval augmented generation](https://arxiv.org/abs/2401.15884). *arXiv preprint arXiv:2401.15884*.

## 3. 附录

### Appendix A — 核心工作流与上线前核验

1. **采集与归档：** 员工通过 Android 客户端提交 PDF、网页链接或文本笔记；自托管服务保存原始文件并返回可识别的入库回执。
2. **检索与核验：** 用户按标题查找记录或通过 RAG 提出自然语言问题，随后直接打开引用的原文段落核对答案。
3. **优雅降级：** 正式发布前，开发团队与系统管理员共同确认：即使 RAG 服务离线，核心的文档保存与标题搜索功能仍可正常运行。
