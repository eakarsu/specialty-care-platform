# Feature status — Specialty clinic operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 123 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 6 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 12 | 0 | Native records/view |
| Activity & audit trail | audit | 2 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Patients | records | 5 | 0 | Native records/view |
| Retinal Scans | records | 1 | 0 | Native records/view |
| Prescriptions | records | 1 | 0 | Native records/view |
| Frames | records | 1 | 0 | Native records/view |
| Insurance | records | 1 | 0 | Native records/view |
| Inventory | records | 1 | 0 | Native records/view |
| Appointments | records | 4 | 0 | Native records/view |
| Contact Lenses | records | 1 | 0 | Native records/view |
| Visual Acuity | records | 1 | 0 | Native records/view |
| Patient Recalls | records | 1 | 0 | Native records/view |
| AI Diagnosis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Predictive | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| agentic patient follow up | records | 1 | 0 | Native records/view |
| computer vision screening automation | records | 1 | 0 | Native records/view |
| insurance pre auth automation | records | 1 | 0 | Native records/view |
| prescription conflict checking | records | 1 | 0 | Native records/view |
| style fit prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| patients without patient | records | 2 | 0 | Native records/view |
| appointments without schedule | records | 1 | 0 | Native records/view |
| frames without frame | records | 1 | 0 | Native records/view |
| recalls without recall | records | 1 | 0 | Native records/view |
| limited ehr integration some integration stubs but | integration | 1 | 0 | Provider request records only |
| referral management e g refer to ophthalmologis | records | 1 | 0 | Native records/view |
| telemedicine remote consultation | records | 1 | 0 | Native records/view |
| patient portal for self | records | 1 | 0 | Native records/view |
| manufacturer integrations for inventory auto | integration | 1 | 0 | Provider request records only |
| webhooks for lab imaging system events | integration | 1 | 0 | Provider request records only |
| frontend pages listed per tsv | records | 1 | 0 | Native records/view |
| rbac beyond auth | records | 1 | 0 | Native records/view |
| Therapists | records | 1 | 0 | Native records/view |
| Exercise Library | records | 1 | 0 | Native records/view |
| Exercise Videos | records | 1 | 0 | Native records/view |
| Treatment Plans | records | 1 | 0 | Native records/view |
| Assessments | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Recovery Progress | records | 1 | 0 | Native records/view |
| Home Programs | records | 2 | 0 | Native records/view |
| Treatment Notes | records | 1 | 0 | Native records/view |
| Pain Assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outcome Measures | records | 1 | 0 | Native records/view |
| Waitlist | records | 1 | 0 | Native records/view |
| Agentic HEP execution | records | 1 | 0 | Native records/view |
| Movement quality scoring | records | 1 | 0 | Native records/view |
| Telehealth live feedback | records | 1 | 0 | Native records/view |
| Outcome prediction + intervention | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pain science education | records | 1 | 0 | Native records/view |
| Appointments without `/appointment | records | 1 | 0 | Native records/view |
| Exercises without `/exercise | records | 1 | 0 | Native records/view |
| Limited EHR/medical records integration (only stub) | integration | 1 | 0 | Provider request records only |
| No wearable integration (accelerometer movement data) | integration | 1 | 0 | Provider request records only |
| No remote monitoring (telehealth with real | records | 1 | 0 | Native records/view |
| Limited insurance billing automation | records | 1 | 0 | Native records/view |
| No integration with fitness/activity trackers | integration | 1 | 0 | Provider request records only |
| No notifications module (grep 0) | records | 1 | 0 | Native records/view |
| No webhooks for referral events | integration | 1 | 0 | Provider request records only |
| Limited mobile app (1 mobile reference) despite HEP delivery domain | records | 1 | 0 | Native records/view |
| Analyze Movement Form | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate Treatment Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assess Recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recommend Exercises | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate HEP | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate SOAP Note | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze Pain Patterns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict Treatment Outcomes | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outcome score calculator | records | 1 | 0 | Native records/view |
| Rom calculator | records | 1 | 0 | Native records/view |
| Exercise prescription | records | 1 | 0 | Native records/view |
| Progress chart | records | 1 | 0 | Native records/view |
| Appointment optimize | records | 1 | 0 | Native records/view |
| Patient dropout predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Vital Signs | records | 1 | 0 | Native records/view |
| Medications | records | 1 | 0 | Native records/view |
| Care Plans | records | 1 | 0 | Native records/view |
| Consultations | records | 1 | 0 | Native records/view |
| Devices | records | 2 | 0 | Native records/view |
| Alerts | records | 2 | 0 | Native records/view |
| Emergency | records | 2 | 0 | Native records/view |
| Escalation Ladder | records | 1 | 0 | Native records/view |
| Device Simulator | records | 1 | 0 | Native records/view |
| Shared Decision | records | 1 | 0 | Native records/view |
| Trajectory | records | 1 | 0 | Native records/view |
| Cost-Aware Plan | records | 1 | 0 | Native records/view |
| Caregiver Coach | records | 1 | 0 | Native records/view |
| Anomaly Detection | records | 1 | 0 | Native records/view |
| Caregiver Portal | records | 1 | 0 | Native records/view |
| CGM Pipeline | records | 1 | 0 | Native records/view |
| Decompensation Alert | records | 2 | 0 | Native records/view |
| EHR HL7/FHIR | integration | 1 | 0 | Provider request records only |
| Med Refill Automation | records | 1 | 0 | Native records/view |
| Med Optimization | records | 1 | 0 | Native records/view |
| Mental Health Screen | records | 1 | 0 | Native records/view |
| Secure Messaging | records | 1 | 0 | Native records/view |
| Patient Education | records | 2 | 0 | Native records/view |
| PHR Export | records | 1 | 0 | Native records/view |
| Social Determinants | records | 2 | 0 | Native records/view |
| Telehealth Video | integration | 1 | 0 | Provider request records only |
| Wearable Integration | integration | 1 | 0 | Provider request records only |
| Mental health screening | records | 1 | 0 | Native records/view |
| Medication optimization | records | 1 | 0 | Native records/view |
| predictive decompensation alerts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| shared decisionmaking tool | records | 1 | 0 | Native records/view |
| social prescribing recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| longitudinal health trajectory | records | 1 | 0 | Native records/view |
| costaware treatment planning | records | 1 | 0 | Native records/view |
| caregiver support coaching | records | 1 | 0 | Native records/view |
| Rules & Jobs | records | 5 | 0 | Native records/view |
| Sessions | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 123 feature pages were visited in the browser; 121 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 22 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

22 original AI entries are now grouped into **4 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
