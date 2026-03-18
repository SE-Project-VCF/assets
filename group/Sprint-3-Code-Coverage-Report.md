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
| SonarQube - NewCode | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-3-sonarqube-report1.pdf |
| SonarQube - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-3-sonarqube-report2.pdf |
| Trivy - Overall | https://github.com/SE-Project-VCF/assets/blob/main/group/sprint-3-trivy-report.pdf |

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
| Sprint 3 | 83.% |

---

## 5. Weak Areas

Overall, the team faced very few weak areas this sprint. The main challenge occurred near the end, when a merged branch was inadvertently canceled and some intended changes were not integrated before the demo. Although this affected the demo, the issue was quickly identified and resolved immediately afterward, with code coverage scores updated accordingly. The team’s prompt response ensured that all issues were addressed and quality standards were maintained. 

The coverage report did not pass the quality gate due to minor configuration issues with some markdown files (specifically, the `render_with_liquid` setting was not marked as false). This did not affect any source code or test results, so the reported coverage remains accurate and reliable.

## 6. Evidence

- SonarQube: https://sonarcloud.io/project/overview?id=SE-Project-VCF_virtual-career-fair 

---

## 7. Statement of Integrity

This coverage was generated from automated tests executed during this sprint.
