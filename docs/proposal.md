# Proposal

English | [简体中文](proposal_ZH.md)

## 1. Project overview

Staff collect PDFs, links and notes on their phones throughout the workday. When they need a document again, they may have to search several apps and folders. PerClip will bring those records into a self-hosted archive. Its Android app will support title search and use retrieval-augmented generation (RAG) to answer questions from retrieved passages (Lewis et al., 2020). Staff can open the cited passage to check an answer.

Staff will help define retrieval tasks. Group 2 will plan the release with the system administrator, who will manage access, backups and support. The sponsor will review the expected benefit and cost before authorising wider use.

### 1.1 Purpose of the project

The project aims to reduce the time staff spend finding documents. The proposed measure of success is for at least four of five users to find a specified document unaided within 60 seconds. The team will time comparable searches in folders and in PerClip. Following the value and measurement principles in the PMBOK Guide (Project Management Institute, 2021), the sponsor will review these results alongside support costs and user feedback.

### 1.2 Scope

**In scope.** The release plan covers Android capture, document archiving, title search and answers with source links. It also covers staff onboarding and handover to IT operations. Before release, the team will check that staff can still save and find documents when the RAG service is unavailable.

**Out of scope.** The first release excludes iOS, multi-tenant hosting and migration of live institutional archives.

## 2. References

Lewis, P., Perez, E., Piktus, A., Petroni, F., Karpukhin, V., Goyal, N., Küttler, H., Lewis, M., Yih, W.-t., Rocktäschel, T., Riedel, S., & Kiela, D. (2020). [Retrieval-augmented generation for knowledge-intensive NLP tasks](https://proceedings.neurips.cc/paper/2020/hash/6b493230-Abstract.html). *Advances in Neural Information Processing Systems, 33*, 9459–9474.

Project Management Institute. (2021). [*A guide to the project management body of knowledge (PMBOK Guide) and the standard for project management*](https://www.pmi.org/es-es/brasil/sitecore/content/home/standards/pmbok) (7th ed.).
