# Sprint 2 Code Coverage Report

Generated: 2026-04-07

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
| SonarQube - NewCode | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-4-sonarqube-report1.pdf |
| SonarQube - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-4-sonarqube-report2.pdf |
| Trivy - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-4-trivy-report.pdf |

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


---

## 5. Weak Areas

The team did not experience any significant weak areas during this sprint. Coverage remained stable at 83.0%, consistent with Sprint 3 levels. All new code introduced during the sprint — including the server.js decomposition into modular route files, networking lounge feature, and calls/sessions endpoints — was accompanied by corresponding test coverage. SonarQube scans did not flag any critical maintainability, reliability, or security issues in the new code. The team maintained code quality standards throughout the sprint with no regressions in test coverage or code health metrics.

One weak area is that duplicate code has been gradually increasing over the last few sprints in the overall codebase. As new features were added across multiple route files and components, some patterns — such as authorization checks, error handling logic, and Firestore query structures — were repeated rather than abstracted into shared utilities. This duplication is reflected in SonarQube's overall code analysis and is something the team plans to address through refactoring in future sprints to improve long-term maintainability.

## 6. Evidence

- SonarQube: https://sonarcloud.io/project/overview?id=SE-Project-VCF_virtual-career-fair 

---

## 7. Statement of Integrity

This coverage was generated from automated tests executed during this sprint.
