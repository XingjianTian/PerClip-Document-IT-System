# Proposal

English | [简体中文](proposal_ZH.md)

## 1. Project overview

Staff collect PDFs, links, and notes on their phones throughout the workday, leaving important records scattered across apps and folders. When they need a document again, finding it takes unnecessary time. PerClip addresses this by bringing saved items into a single self-hosted archive. Its Android app supports title search and uses retrieval-augmented generation (RAG) to answer questions from retrieved passages (Lewis et al., 2020), allowing users to open each cited passage and verify the source directly.

As an organizational IT system, PerClip involves four main stakeholder groups: end users, the development team, IT operations, and the project sponsor. Department staff and knowledge workers use the app to save and retrieve daily records, help define realistic search tasks, and report usability issues. The project manager and development team build and test the Android client, archive service, and RAG pipeline. IT operations and system administrators take over hosting, access control, backups, and routine support after launch, while the project sponsor and management provide resources and decide whether to expand deployment across the organization.

### 1.1 Purpose of the project

The project aims to reduce the time staff spend finding documents and provide a clear basis for wider adoption. Its target is for at least four out of five users to locate a specified document unaided within 60 seconds. The development team will assess this by comparing search times in PerClip against standard folder lookups on the same tasks. Following the value delivery and measurement principles in the PMBOK Guide (Project Management Institute, 2021), the sponsor will evaluate these retrieval times alongside user feedback and ongoing support costs before authorizing broader rollout.

### 1.2 Scope

**In scope.** The initial release covers Android document capture, self-hosted archiving, title search, and RAG question answering with source links, together with user onboarding and handover to IT operations. Before launch, the development team and system administrator will verify that users can still save and find documents by title when the RAG service is unavailable.

**Out of scope.** The first release excludes an iOS client, multi-tenant cloud hosting, and automated migration of existing third-party archives.

## 2. References

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).
