# Android interface screenshot catalogue

Captured on 13 November 2026 using PerClip Dev 0.3.0 on an isolated Android 15 (API 35) emulator, with English app language. This is a catalogue of application screens, **not functional acceptance testing**. Main-app screens use a fresh installation and an unsaved synthetic draft. Populated Knowledge, library, Recall and Settings screens use the application’s built-in offline Debug fixtures. These fixtures are absent from Release builds. Counts, documents, topics, connection details and errors shown are fictional; they do not demonstrate live synchronization, AI answering, RAGFlow availability or real user activity. Chinese titles and fixture-provided messages remain original sample content.

The files are direct Android screenshots with no compositing, text replacement or retouching. `01` = capture, `02` = Knowledge and detail, `03` = libraries, `04` = Memory Planet/Recall, `05` = Settings. Numbers identify an image, not a chronological feature test. Consecutive images for a screen show its sections, dialogs or alternative states. Android permission/file-picker surfaces belong to the operating system.

Application source baseline: public main `0a66cd4`, with local `codex/android-english-ui` modifications. APK SHA-256: `f517115102f007977590f15f8f9657fb4ce63660aca04e33bea3553ec0408e4c`. The APK and application source are not included in this document repository.

## Image index

| ID | Screen | What the screenshot shows | Origin |
|---|---|---|---|
| [01-01](screenshots/01-01.png) | Flash Note — empty composer | Text entry, attachment and recording actions, default-library entry and main navigation. | Actual app; fresh isolated emulator |
| [01-02](screenshots/01-02.png) | Flash Note — text draft | A synthetic course-note draft before saving. | Actual app; synthetic unsaved draft |
| [01-03](screenshots/01-03.png) | Flash Note — attachment picker | Android attachment selection surface; no personal files are selected. | Offline Debug fixture |
| [01-04](screenshots/01-04.png) | Flash Note — microphone permission | Android microphone-permission prompt; recording is not started. | Offline Debug fixture |
| [02-01](screenshots/02-01.png) | Knowledge — populated list | Synthetic saved documents, processing states, summaries and source labels. | Offline Debug fixture |
| [02-02](screenshots/02-02.png) | Knowledge — filter sheet | Status, platform, document type and attachment filters. | Offline Debug fixture |
| [02-03](screenshots/02-03.png) | Knowledge — empty list | Empty-state guidance when no local documents are available. | Offline Debug fixture |
| [02-04](screenshots/02-04.png) | Knowledge — dark appearance | The same document-list design in dark appearance. | Offline Debug fixture |
| [02-05](screenshots/02-05.png) | Memory detail — original content | Detail heading, capture date, source and preserved original synthetic text. | Offline Debug fixture |
| [02-06](screenshots/02-06.png) | Memory detail — URL | Original-URL presentation; the URL is sample fixture content, not a fetched page. | Offline Debug fixture |
| [02-07](screenshots/02-07.png) | Memory detail — loading | Loading-state presentation only. | Offline Debug fixture |
| [02-08](screenshots/02-08.png) | Memory detail — error | Fixture-provided unavailable-detail state; Chinese fixture error text is preserved. | Offline Debug fixture |
| [02-09](screenshots/02-09.png) | Knowledge — filter sheet, lower section | Remaining type and attachment filter options after scrolling. | Offline Debug fixture |
| [03-01](screenshots/03-01.png) | Libraries — management list | Synthetic library list and management actions. | Offline Debug fixture |
| [03-02](screenshots/03-02.png) | Libraries — empty state | Library management with no entries. | Offline Debug fixture |
| [03-03](screenshots/03-03.png) | Libraries — default selection | Default-library selection surface. | Offline Debug fixture |
| [03-04](screenshots/03-04.png) | Libraries — dark appearance | Library management in dark appearance. | Offline Debug fixture |
| [03-05](screenshots/03-05.png) | Libraries — creation dialog | Library name and optional description fields; nothing submitted. | Offline Debug fixture |
| [03-06](screenshots/03-06.png) | Libraries — archived section | Expanded archived-library list using fictional entries. | Offline Debug fixture |
| [03-07](screenshots/03-07.png) | Libraries — action menu | Actions exposed by the library overflow menu; no mutation is submitted. | Offline Debug fixture |
| [03-08](screenshots/03-08.png) | Libraries — rename dialog | Existing fictional library name in the rename dialog; nothing is submitted. | Offline Debug fixture |
| [04-01](screenshots/04-01.png) | Memory Planet — overview | Synthetic topic orbits, linked memories and topic insights. Chinese sample titles remain original content. | Offline Debug fixture |
| [04-02](screenshots/04-02.png) | Memory Planet — topic | Topic-focused navigation and related synthetic documents. | Offline Debug fixture |
| [04-03](screenshots/04-03.png) | Memory Planet — monthly window | Monthly window selected. The no-connection message is visible; no monthly data retrieval is demonstrated. | Offline Debug fixture |
| [04-04](screenshots/04-04.png) | Memory Planet — compact display | Reduced visible topics and memory labels. | Offline Debug fixture |
| [04-05](screenshots/04-05.png) | Memory Planet — display settings | Controls for graph and display preferences. | Offline Debug fixture |
| [04-06](screenshots/04-06.png) | Recall — hidden answer | Synthetic recall-session question before reveal. | Offline Debug fixture |
| [04-07](screenshots/04-07.png) | Recall — revealed answer | Synthetic recall-session answer after reveal. | Offline Debug fixture |
| [04-08](screenshots/04-08.png) | Recall — weekly review | Synthetic review counts, topics and suggested items; not real study statistics. | Offline Debug fixture |
| [04-09](screenshots/04-09.png) | Memory Planet — loading | Loading-state presentation. | Offline Debug fixture |
| [04-10](screenshots/04-10.png) | Memory Planet — unavailable | Fixture-provided unavailable state, not a measured service outage. | Offline Debug fixture |
| [04-11](screenshots/04-11.png) | Memory Planet — dark appearance | Synthetic topic overview in dark appearance. | Offline Debug fixture |
| [04-12](screenshots/04-12.png) | Memory Planet — period selector | Available date-window choices. | Offline Debug fixture |
| [04-13](screenshots/04-13.png) | Memory Planet — options menu | Overview actions and navigation options. | Offline Debug fixture |
| [04-14](screenshots/04-14.png) | Memory Planet — topic memories | Lower topic page with related synthetic memory cards. | Offline Debug fixture |
| [04-15](screenshots/04-15.png) | Memory Planet — display settings, lower section | Remaining topic toggles and restore-default action. | Offline Debug fixture |
| [04-16](screenshots/04-16.png) | Memory Planet — custom date range | Custom date range selection surface; no query is submitted. | Offline Debug fixture |
| [05-01](screenshots/05-01.png) | Settings — home | Connection, capture, libraries, Memory Planet, appearance and reduce-motion entries. | Offline Debug fixture |
| [05-02](screenshots/05-02.png) | Settings — connection | Full connection page with fictional address, masked token, connection controls and optional RAGFlow check; statuses are fixture-provided. | Offline Debug fixture |
| [05-04](screenshots/05-04.png) | Settings — capture and ingest | Device identity, network preferences, system shortcuts and queue summary. | Offline Debug fixture |
| [05-05](screenshots/05-05.png) | Settings — device-name dialog | Editable synthetic device identity; changes are not submitted. | Offline Debug fixture |
| [05-06](screenshots/05-06.png) | Settings — appearance | System, light and dark theme choices. | Offline Debug fixture |
| [05-07](screenshots/05-07.png) | Settings — dark appearance | Appearance controls rendered in dark mode. | Offline Debug fixture |
| [05-08](screenshots/05-08.png) | Settings — Memory Planet preferences | Display-management screen with synthetic topics. | Offline Debug fixture |
| [05-09](screenshots/05-09.png) | Settings — unavailable advanced features | Fixture-provided unsupported-feature state. | Offline Debug fixture |

## Illustrated screen guide

### 01-01 — Flash Note — empty composer

Text entry, attachment and recording actions, default-library entry and main navigation.

![Flash Note — empty composer](screenshots/01-01.png)

### 01-02 — Flash Note — text draft

A synthetic course-note draft before saving.

![Flash Note — text draft](screenshots/01-02.png)

### 01-03 — Flash Note — attachment picker

Android attachment selection surface; no personal files are selected.

![Flash Note — attachment picker](screenshots/01-03.png)

### 01-04 — Flash Note — microphone permission

Android microphone-permission prompt; recording is not started.

![Flash Note — microphone permission](screenshots/01-04.png)

### 02-01 — Knowledge — populated list

Synthetic saved documents, processing states, summaries and source labels.

![Knowledge — populated list](screenshots/02-01.png)

### 02-02 — Knowledge — filter sheet

Status, platform, document type and attachment filters.

![Knowledge — filter sheet](screenshots/02-02.png)

### 02-03 — Knowledge — empty list

Empty-state guidance when no local documents are available.

![Knowledge — empty list](screenshots/02-03.png)

### 02-04 — Knowledge — dark appearance

The same document-list design in dark appearance.

![Knowledge — dark appearance](screenshots/02-04.png)

### 02-05 — Memory detail — original content

Detail heading, capture date, source and preserved original synthetic text.

![Memory detail — original content](screenshots/02-05.png)

### 02-06 — Memory detail — URL

Original-URL presentation; the URL is sample fixture content, not a fetched page.

![Memory detail — URL](screenshots/02-06.png)

### 02-07 — Memory detail — loading

Loading-state presentation only.

![Memory detail — loading](screenshots/02-07.png)

### 02-08 — Memory detail — error

Fixture-provided unavailable-detail state; Chinese fixture error text is preserved.

![Memory detail — error](screenshots/02-08.png)

### 02-09 — Knowledge — filter sheet, lower section

Remaining type and attachment filter options after scrolling.

![Knowledge — filter sheet, lower section](screenshots/02-09.png)

### 03-01 — Libraries — management list

Synthetic library list and management actions.

![Libraries — management list](screenshots/03-01.png)

### 03-02 — Libraries — empty state

Library management with no entries.

![Libraries — empty state](screenshots/03-02.png)

### 03-03 — Libraries — default selection

Default-library selection surface.

![Libraries — default selection](screenshots/03-03.png)

### 03-04 — Libraries — dark appearance

Library management in dark appearance.

![Libraries — dark appearance](screenshots/03-04.png)

### 03-05 — Libraries — creation dialog

Library name and optional description fields; nothing submitted.

![Libraries — creation dialog](screenshots/03-05.png)

### 03-06 — Libraries — archived section

Expanded archived-library list using fictional entries.

![Libraries — archived section](screenshots/03-06.png)

### 03-07 — Libraries — action menu

Actions exposed by the library overflow menu; no mutation is submitted.

![Libraries — action menu](screenshots/03-07.png)

### 03-08 — Libraries — rename dialog

Existing fictional library name in the rename dialog; nothing is submitted.

![Libraries — rename dialog](screenshots/03-08.png)

### 04-01 — Memory Planet — overview

Synthetic topic orbits, linked memories and topic insights. Chinese sample titles remain original content.

![Memory Planet — overview](screenshots/04-01.png)

### 04-02 — Memory Planet — topic

Topic-focused navigation and related synthetic documents.

![Memory Planet — topic](screenshots/04-02.png)

### 04-03 — Memory Planet — monthly window

Monthly window selected. The no-connection message is visible; no monthly data retrieval is demonstrated.

![Memory Planet — monthly window](screenshots/04-03.png)

### 04-04 — Memory Planet — compact display

Reduced visible topics and memory labels.

![Memory Planet — compact display](screenshots/04-04.png)

### 04-05 — Memory Planet — display settings

Controls for graph and display preferences.

![Memory Planet — display settings](screenshots/04-05.png)

### 04-06 — Recall — hidden answer

Synthetic recall-session question before reveal.

![Recall — hidden answer](screenshots/04-06.png)

### 04-07 — Recall — revealed answer

Synthetic recall-session answer after reveal.

![Recall — revealed answer](screenshots/04-07.png)

### 04-08 — Recall — weekly review

Synthetic review counts, topics and suggested items; not real study statistics.

![Recall — weekly review](screenshots/04-08.png)

### 04-09 — Memory Planet — loading

Loading-state presentation.

![Memory Planet — loading](screenshots/04-09.png)

### 04-10 — Memory Planet — unavailable

Fixture-provided unavailable state, not a measured service outage.

![Memory Planet — unavailable](screenshots/04-10.png)

### 04-11 — Memory Planet — dark appearance

Synthetic topic overview in dark appearance.

![Memory Planet — dark appearance](screenshots/04-11.png)

### 04-12 — Memory Planet — period selector

Available date-window choices.

![Memory Planet — period selector](screenshots/04-12.png)

### 04-13 — Memory Planet — options menu

Overview actions and navigation options.

![Memory Planet — options menu](screenshots/04-13.png)

### 04-14 — Memory Planet — topic memories

Lower topic page with related synthetic memory cards.

![Memory Planet — topic memories](screenshots/04-14.png)

### 04-15 — Memory Planet — display settings, lower section

Remaining topic toggles and restore-default action.

![Memory Planet — display settings, lower section](screenshots/04-15.png)

### 04-16 — Memory Planet — custom date range

Custom date range selection surface; no query is submitted.

![Memory Planet — custom date range](screenshots/04-16.png)

### 05-01 — Settings — home

Connection, capture, libraries, Memory Planet, appearance and reduce-motion entries.

![Settings — home](screenshots/05-01.png)

### 05-02 — Settings — connection

Full connection page with fictional address, masked token, connection controls and optional RAGFlow check; statuses are fixture-provided.

![Settings — connection](screenshots/05-02.png)

### 05-04 — Settings — capture and ingest

Device identity, network preferences, system shortcuts and queue summary.

![Settings — capture and ingest](screenshots/05-04.png)

### 05-05 — Settings — device-name dialog

Editable synthetic device identity; changes are not submitted.

![Settings — device-name dialog](screenshots/05-05.png)

### 05-06 — Settings — appearance

System, light and dark theme choices.

![Settings — appearance](screenshots/05-06.png)

### 05-07 — Settings — dark appearance

Appearance controls rendered in dark mode.

![Settings — dark appearance](screenshots/05-07.png)

### 05-08 — Settings — Memory Planet preferences

Display-management screen with synthetic topics.

![Settings — Memory Planet preferences](screenshots/05-08.png)

### 05-09 — Settings — unavailable advanced features

Fixture-provided unsupported-feature state.

![Settings — unavailable advanced features](screenshots/05-09.png)

## Scope notes

This set documents screens visible in the captured build, including empty/loading/error and light/dark variants. It does not claim every dynamic combination, every Android permission prompt, or every remote-data state. Voice recording, external document processing, notification delivery, external website capture, AI question answering and live backend integrations were not functionally exercised for this screenshot task. The screenshots must not be cited as proof that the proposed course system’s AI/RAG features have been implemented or accepted.
