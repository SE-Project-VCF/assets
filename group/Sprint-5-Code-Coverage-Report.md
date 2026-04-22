# Sprint 5 Code Coverage Report

Generated: 2026-04-021

---

## 1. Tool & Setup

| Item | Value |
|------|-------|
| Language | JavaScript (Node.js / React) |
| Backend Tests | Jest 30 |
| Frontend Tests | Vitest 4 |
| Coverage Tool | Istanbul / v8 (bundled with Jest & Vitest) |

---

## 2. Coverage Metrics

| Coverage Tool | Coverage Report |
|---------------|-----------------|
| SonarQube - NewCode | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-5-sonarqube-report1.pdf |
| SonarQube - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-5-sonarqube-report2.pdf |
| Trivy - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-5-trivy-report.pdf |

---

## 3. Scope of Coverage

**Included:**
- Entire project repository including both frontend and backend source code
- JavaScript / TypeScript application files
- Dependency files such as package-lock.json
- Security and secret scans on project files including backend/privateKey.json
- Code quality analysis including maintainability, reliability, and security metrics

**Excluded:**
- No files or directories were intentionally excluded from the scan
- External libraries inside node_modules were not directly analyzed as source code (only dependency vulnerabilities were checked)


---

## 4. Coverage Trend

| Sprint | Line Coverage |
|--------|--------------|
| Sprint 0 | None |
| Sprint 1 | 82.95% |
| Sprint 2 | 70.2% |
| Sprint 3 | 83.0% |
| Sprint 4 | 83.0% |
| Sprint 5 | 86.0% |


---

## 5. Weak Areas

The team did not encounter any major weak areas during this sprint. Overall coverage improved from 83.0% to 86.0%, which continues the positive trend from Sprint 4.

One concern was a security rating change from A to B. While this is not a critical issue, it is an area we plan to monitor and improve.

In the previous report, we committed to reducing overall SonarQube issues. That work was postponed to the final sprint of the semester. One Jira task was not included in this push because it introduced a new database collection instead of refactoring the legacy collection with the rest of our data.

## 6. Evidence

- SonarQube: https://sonarcloud.io/project/overview?id=SE-Project-VCF_virtual-career-fair 

---

## 7. Statement of Integrity

This coverage was generated from automated tests executed during this sprint.
