# Proposal

English | [简体中文](proposal_ZH.md)

## 1. PROJECT OVERVIEW

PerClip RAG Document Management System is preparing for its first departmental release. The Document Management System will let staff file notes, links and PDFs from Android, keep the originals on departmental storage and ask questions with links to the source passages.

A staff member who needs the policy behind a decision may have to search a team chat, a downloads folder and several PDFs before finding the right passage. A pilot in one department will test whether PerClip shortens that search enough to justify training, hosting and support.

The pilot depends on four groups with different responsibilities.

- Department staff: Choose representative documents, time the same lookup in folders and in PerClip, and report where they still need help.
- IT operations: Manage access, backups and service recovery. The administrator takes ownership of the support queue at handover.
- Project team (Group 2): Agree the pilot scope with users, estimate the work and bring test results, costs and open issues to the release review.
- Sponsor and academic reviewer: The department sponsor would authorise the pilot and decide whether to expand it. Dr. Nabil Hasan Saleh reviews the group’s project management work for UECS6013.

For the pilot release decision, the sponsor is accountable, the project lead is responsible for the recommendation, IT operations is consulted and pilot users are informed. This applies the RACI roles from Topic 2 to a decision the team will face at launch.

### 1.1 Purpose of the Project

The project will give the sponsor a basis for deciding whether to extend PerClip beyond one department. The team will compare retrieval times, estimate the cost of supporting another group and review what prevents staff from using the service in their daily work.

Five work packages connect the release plan to that decision.

1. Scope and requirements: Agree which records staff will capture and which questions they need to answer. Link each requirement to an acceptance check.
2. Schedule and dependencies: Use a work breakdown structure (WBS) to sequence archive checks, retrieval tests, staff onboarding and the pilot review.
3. Cost and change control: Record requests such as adding another department. Estimate the extra support hours, cost and delay before the sponsor decides.
4. Quality and operational risk: Check the passage behind each test answer. If evidence is missing, show that to the user. Keep title search available during an indexing outage.
5. Adoption and handover: Give pilot staff a short walkthrough using their own work tasks. Assign a support contact and review recurring problems with IT operations.

### 1.2 Scope

#### In Scope

- Pilot release: One department, an Android client and a self-hosted archive. Staff can capture a record, check its status, search by title and open the source behind a RAG answer.
- Management plan: Set the scope, schedule and cost baselines. At each review the lead records decisions, assigns an owner to each open risk and tracks approved changes against the baselines.
- Release gates: Following Topic 3, IT operations reviews five acceptance checks before admitting users. At day 30 the sponsor reviews retrieval times, incidents and support costs, then decides whether to expand, extend or stop the pilot.

#### Out of Scope

- Native iOS development and commercial billing.
- Cross-department rollout, single sign-on and multi-tenant hosting.
- Migration of live departmental archives and formal regulatory certification.
- Purchasing production infrastructure. The pilot review will establish demand and capacity for a wider rollout.

#### Project Timeline & Milestones

The course planning period is 13 November to 10 December 2026 (Malaysia time, UTC+8). The proposed 30-day pilot starts after departmental authorisation.

- 19 November 2026 (18:00 MYT): Review the proposal and Team Charter with the group.
- 20 November 2026: Submit the Proposal and Team Charter. Agree the requirements, MOV and WBS baseline by 27 November.
- 8 December 2026: Submit the Project Charter following the 7 December review of scope, cost, risks and acceptance criteria.
- 10 December 2026: Present the release recommendation and the decisions the sponsor will face after the pilot.

## 2. REFERENCES

Saleh, N. H. (2026, November 3). Project requirements [UECS6013 assignment handout]. Universiti Teknologi Malaysia. https://elearning.utm.my/26271/mod/assign/view.php?id=197110

Universiti Teknologi Malaysia. (2026). The project management team and Principles of project management [UECS6013 lecture slides, Topics 2–3]. Faculty of Computing.

## 3. APPENDIX

### Appendix A — End-to-End System Workflow

1. Capture: A staff member shares a policy PDF or link from Android. A receipt identifies the record and shows whether the archive has received it.
2. Archive & Index: Departmental storage holds the original and its source details. A separate worker indexes the text. If indexing stalls, IT operations can retry the queue while staff continue filing and searching by title.
3. Retrieve & Query: Staff locate a record by title or ask a question and open the cited passage. A missing citation or incorrect answer goes into the pilot issue log for review.

### Appendix B — Functional Acceptance Scenarios

The quality lead will record the input, expected result and outcome for each check before recommending pilot access.

1. Note Capture: Save a plain-text note and verify receipt generation and readable storage.
2. Link Archiving: Share a web URL and confirm preservation of both the link and page title.
3. File Attachment: Upload a sample document and verify lossless retrieval of the original file.
4. Title and source lookup: Find a target policy by title, ask a question about it and check that the cited passage supports the answer.
5. Graceful Degradation: Simulate RAG service unavailability and verify that core saving, browsing, and title search continue uninterrupted with clear status indicators.

### Appendix C — Measurable Organizational Value (MOV) Target

During the first 30 days, five pilot users will each find a policy in folders and then a comparable policy in PerClip. The measurable organisational value (MOV) target is for at least four to find the right document unaided within 60 seconds in PerClip. Record times, errors and requests for help. If the target is missed, interview users and retest before inviting another department.

### Appendix D — Group Presentation Plan

Each member will explain one decision in the release plan. The team leader opens and returns after the quality review to give the group’s recommendation.

1. Xingjian Tian (Team Leader): Introduce the department’s problem and the sponsor’s decision. Close with the proposed release conditions.
2. Li Chunze: Define pilot scope, user requirements and the retrieval-time target.
3. Lin Zhihua: Show which WBS tasks must finish before staff can join the pilot.
4. Tan Shirong: Explain the cost baseline, how a change affects it and who owns the main risks.
5. Zhang Shuai: Present the acceptance checks and handover to IT operations, then return to the team leader.

### Appendix E — Resource & Budget Estimate

The course planning estimate covers 90 person-hours (18 per member). At MYR 25 per hour, labour is valued at MYR 2,250. A MYR 100 testing allowance and a 10% contingency of MYR 235 bring the estimate to MYR 2,585. During the pilot, IT operations will track hosting, model use and support hours so the sponsor can price the next department.
