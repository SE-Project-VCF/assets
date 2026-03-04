# Sprint 2 Code Coverage Report

Generated: 2026-03-03

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

| Sonar Qube | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-2-sonarqube-report.pdf
| Trivy | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-2-trivy-report.pdf |

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

---

## 5. Weak Areas

 The most problematic area identified in this sprint was maintainability and code quality, as SonarQube reported a high number of code smells and the quality gate failed. The Trivy scan also detected a high severity dependency vulnerability and exposed secrets in the repository, indicating security concerns. In the next sprint, we plan to refactor problematic code, improve test coverage, and remove sensitive keys from the repository to reduce vulnerabilities and improve the overall quality gate results.

---

## 6. Evidence

- Backend HTML report: [`backend/coverage/lcov-report/index.html`](backend/coverage/lcov-report/index.html)
- Frontend HTML report: [`frontend/coverage/index.html`](frontend/coverage/index.html)

---

## 7. Statement of Integrity

This coverage was generated from automated tests executed during this sprint.
