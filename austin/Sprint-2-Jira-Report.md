# Sprint 2 Jira Report

**Jira Project:** SCRUM
**Jira Project Link:** https://uwp-se-career-fair.atlassian.net/jira/software/projects/SCRUM/boards/1
**Sprint Name/Number:** Sprint 2

---

## Sprint Commitment vs Delivery

_Metrics derived from Jira board and git commit history (Feb 18–Mar 3)._

| Metric | Count |
|--------|-------|
| Issues committed at sprint start | 0 |
| Issues completed | 19 |
| Issues not completed | 0 |
| Issues added mid-sprint | 19 |

---

## Issue Breakdown by Type

_Categorized from Jira issues and commit history._

| Type | To Do | In Progress | Done |
|------|-------|-------------|------|
| Story | 0 | 0 | 2 |
| Task | 0 | 0 | 2 |
| Bug | 0 | 0 | 0 |

_Stories: fair enrollment management (join/leave/invite code), Firebase token verification middleware & auth refactoring, FairBoothView/FairBooths/FairLanding/FairList components, user auth & email verification enhancements, application builder UI (ninapelli), candidate applications (ninapelli), draft status (ninapelli), AI resume tailoring (kreli)_
_Tasks: comprehensive test coverage (AdminDashboard, Dashboard, NotificationBell, FairContext, BoothEditor, Fair components, console.js), CI/SonarQube configuration & coverage reporting, report generation scripts, package updates & maintenance, code refactoring & cleanup, backend deployment config (kreli)_
_Bugs: log injection / sensitive data in job invitation endpoints, null checks & parameter handling in job input validation, CI configuration fixes (org name, host URL, action version), fix booths & invitations (ninapelli), booth logo & resume upload fixes (kreli)_

---

## Per-Student Work Allocation

_Issues Assigned/Completed based on Jira board and commit history._

| Student | Issues Assigned | Issues Completed | Commits | Primary Work |
|---------|----------------|-----------------|---------|--------------|
| Austin Moser | 0 | 0 | 42 | Fair enrollment features, Firebase auth middleware, fair components, user auth enhancements, test coverage (AdminDashboard, BoothEditor, Fair components, console.js), CI/SonarQube setup & code standards alignment, log injection security fixes, report scripts, code refactoring |

---

## Estimation & Accuracy

_Story points tracked via Jira._

| Metric | Value |
|--------|-------|
| Total story points committed | 97 |
| Total story points completed | 97 |
| Completion % | 100% |

---

## Workflow Discipline

_Workflow tracked via Jira board and GitHub PRs._

- ☑ Issues moved through workflow states (To Do → In Progress → Done)
- ☑ Issues closed only after acceptance criteria met
- ☑ Sprint completed/closed in Jira

---

## Blockers & Scope Changes

- **Major blockers:** Getting SonarQube Cloud integrated and working was a significant blocker — required multiple iterations to fix the organization name, host URL, action version, and workflow triggers before scans would run successfully. Once SonarQube was operational, aligning the existing codebase with SonarQube quality standards required substantial refactoring (improving null checks, removing sensitive data from logs, implementing `sanitizeLog` for log injection prevention, and restructuring code for readability/maintainability). Backend line coverage also dropped from 82.95% (Sprint 1) to 75.18% due to new source files (`backend/routes/fairs.js`, expanded `console.js`) added without proportional test coverage. Migrating event management from Firestore to API-based fairs required rewriting multiple test suites to use fetch mocks instead of Firestore dependencies.
- **Scope changes:** Fair enrollment management (join/leave/invite code refresh) was added mid-sprint. Firebase token verification middleware was implemented, requiring authorization logic refactoring across header components. CI/CD scope expanded with SonarQube integration, Node.js 20 upgrade, and multiple rounds of CI configuration fixes. Security hardening was added for job invitation endpoints (sanitizeLog, sensitive data removal). ninapelli added application builder UI, candidate applications, and draft status features. kreli implemented AI resume tailoring and fixed file uploads.
- **Why work spilled over (if any):** N/A — all committed issues completed. CI/SonarQube integration required multiple fix iterations (organization name, host URL, action version, workflow triggers) before stabilizing.

---

## Jira Evidence Links

- **Sprint report link:** https://github.com/SE-Project-VCF/assets/blob/main/austin/Sprint-2-GitHub-Report_AustinMoser.md
- **Backlog link:** https://uwp-se-career-fair.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog
- **Board link:** https://uwp-se-career-fair.atlassian.net/jira/software/projects/SCRUM/boards/1
