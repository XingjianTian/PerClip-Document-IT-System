# Proposal

English | [简体中文](proposal_ZH.md)

## 1. Project overview

Staff collect PDFs, links, and notes on their phones throughout the workday, leaving important records scattered across apps and folders. When they need a document again, finding it takes unnecessary time. PerClip addresses this by bringing saved items into a single self-hosted archive. Its Android app supports title search and uses retrieval-augmented generation (RAG) to answer questions from retrieved passages (Lewis et al., 2020), allowing users to open each cited passage and verify the source directly.

As an organizational IT system, PerClip involves four main stakeholder groups: end users, the development team, IT operations, and the project sponsor. Department staff and knowledge workers use the app to save and retrieve daily records, help define realistic search tasks, and report usability issues. The project manager and development team build and test the Android client, archive service, and RAG pipeline. IT operations and system administrators take over hosting, access control, backups, and routine support after launch, while the project sponsor and management provide resources and decide whether to expand deployment across the organization.

### 1.1 Purpose of the project

The project aims to reduce the time staff spend searching across scattered mobile apps and folders, while giving management a clear, evidence-based foundation for wider organizational adoption. Its primary target is for at least four out of five users to locate a specified document unaided within 60 seconds. To evaluate this, the development team will compare search times in PerClip against standard folder lookups on representative daily tasks. Following the value delivery and measurement principles in the PMBOK Guide (Project Management Institute, 2021), the project sponsor will review these retrieval timings alongside user feedback, onboarding effort, and ongoing support costs before authorizing broader rollout.

### 1.2 Scope

**In scope:**
- Android document capture (PDFs, web links, and text notes) and self-hosted archiving.
- Title search and RAG question answering with direct source passage links.
- User onboarding materials, access control setup, backup procedures, and handover to IT operations.
- Pre-launch verification with the system administrator that users can still save and find documents by title when the RAG service is unavailable.

**Out of scope:**
- iOS client development.
- Multi-tenant cloud hosting.
- Enterprise-wide single sign-on (SSO) integration.
- Automated migration of existing third-party archives.

## 2. References

Asai, A., Wu, Z., Wang, Y., Sil, A., & Hajishirzi, H. (2024). [Self-RAG: Learning to retrieve, generate, and critique through self-reflection](https://arxiv.org/abs/2310.11511). *International Conference on Learning Representations (ICLR 2024)*.

Edge, D., Trinh, H., Cheng, N., Bradley, J., Chao, A., Mody, A., Truitt, S., & Larson, J. (2024). [From local to global: A graph RAG approach to query-focused summarization](https://arxiv.org/abs/2404.16130). *arXiv preprint arXiv:2404.16130*.

Gao, Y., Xiong, Y., Gao, X., Jia, K., Pan, J., Bi, Y., Dai, Y., Sun, J., & Wang, H. (2023). [Retrieval-augmented generation for large language models: A survey](https://arxiv.org/abs/2312.10997). *arXiv preprint arXiv:2312.10997*.

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).

Shi, W., Min, S., Yasunaga, M., Seo, M., James, R., Lewis, M., Zettlemoyer, L., & Yih, W.-t. (2024). [REPLUG: Retrieval-augmented black-box language models](https://arxiv.org/abs/2301.12652). *Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL 2024)*.

Yan, S.-Q., Gu, J.-C., Zhu, Y., & Ling, Z.-H. (2024). [Corrective retrieval augmented generation](https://arxiv.org/abs/2401.15884). *arXiv preprint arXiv:2401.15884*.

## 3. Appendix

### Appendix A — Core Workflow and Pre-Release Verification

1. **Capture & Archive:** Staff submit a PDF, web link, or text note from the Android client; the self-hosted service stores the original item and returns an identifiable receipt.
2. **Search & Verify:** Users locate records by title or ask a natural-language question via RAG, then open the cited source passage directly to verify the answer.
3. **Graceful Degradation:** Prior to release, the development team and system administrator confirm that core saving and title search remain operational even if the RAG service is offline.
