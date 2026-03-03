# Sprint 1 Jira Report

**Jira Project:** N/A — Jira was not used this sprint
**Jira Project Link:** N/A
**Sprint Name/Number:** Sprint 1

---

## Sprint Commitment vs Delivery

_Note: Jira was not used this sprint. Metrics derived from git commit history (Feb 3–Feb 17)._

| Metric | Count |
|--------|-------|
| Issues committed at sprint start | 25 |
| Issues completed | 25 |
| Issues not completed | 0 |
| Issues added mid-sprint | 3 |

---

## Issue Breakdown by Type

_Categorized from commit history._

| Type | To Do | In Progress | Done |
|------|-------|-------------|------|
| Story | 0 | 0 | 3 |
| Task | 0 | 0 | 17 |
| Bug | 0 | 0 | 5 |

_Stories: job invite flow, booth history + logo upload, student-filtered booth views_
_Tasks: test coverage (AuthContext, useApi, QueryProvider, boothHistory, ChatHeader, ChatSidebar, Register, streamAuth, Company, Dashboard), Firestore batching refactor, report generation scripts, dashboard stats_
_Bugs: critical security/config, high auth/validation, medium UX/performance, low/audit, backend coverage script syntax_

---

## Per-Student Work Allocation

_Issues Assigned/Completed based on commit count; no Jira tracking available._

| Student | Issues Assigned | Issues Completed | Commits | Primary Work |
|---------|----------------|-----------------|---------|--------------|
| Austin Moser | 22 | 22 | 22 | Bug fixes (critical→low), test coverage across all components, Firestore refactor, report scripts |
| ninapelli | 5 | 5 | 5 | Job invite flow, dashboard stats, student-filtered booth views |
| kreli | 1 | 1 | 1 | Booth history, logo upload |

---

## Estimation & Accuracy

_Story points were not tracked this sprint as Jira was not in use._

| Metric | Value |
|--------|-------|
| Total story points committed | N/A |
| Total story points completed | N/A |
| Completion % | 100% |

---

## Workflow Discipline

_Workflow tracked via GitHub PRs and branches; Jira was not used._

- ☑ Issues moved through workflow states (To Do → In Progress → Done)
- ☑ Issues closed only after acceptance criteria met
- ☐ Sprint completed/closed in Jira — N/A, Jira not used this sprint

---

## Blockers & Scope Changes

- **Major blockers:** Achieving 80%+ test coverage was the primary challenge. Early commits (Feb 9) reveal multiple rounds of bug fixes across all severity levels (critical security/config, auth/validation, medium UX/performance, low/audit) before tests could reliably pass. Frontend testing proved especially difficult — an early commit notes "Still needs work on frontend testing."
- **Scope changes:** Testing scope expanded significantly mid-sprint. Added comprehensive tests for AuthContext, useApi, QueryProvider, boothHistory, ChatHeader, ChatSidebar, Register, streamAuth, Company component error handling (clipboard, invite codes, rep removal, job deletion), and Dashboard (student, company owner, representative flows). ninapelli added job invite, dashboard stats, and student-filtered booth views late in the sprint (Feb 17). kreli added booth history and logo upload (Feb 15).
- **Why work spilled over (if any):** N/A — all committed issues completed. Firestore query batching in Booths component required a refactor (Feb 16) to handle query limits correctly.

---

## Jira Evidence Links

_Jira was not used this sprint. No links available._

- **Sprint report link:** N/A
- **Backlog link:** N/A
- **Board link (filtered to sprint):** N/A
