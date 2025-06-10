# Patch and Release

Draft for a release process. Things to include, thoughts and structure

**Contents:**
1. [About Patch and Release](#1-about-patch-and-release)
2. [Key Questions to Resolve](#2-key-questions-to-resolve)
3. [Subjects to Include in the Draft Version](#3-subjects-to-include-in-the-draft-version)
4. [Draft: High-Level Patch and Release Process](#4-draft-high-level-patch-and-release-process)

---

## 1. About Patch and Release

[See in `about-patch-and-release.md`](./about-patch-and-release.md)

---

## 2. Key Questions to Resolve
### 2.1 Questions to Resolve ASAP
These questions will help shape the initial process:

- **What types of changes qualify as patches?**
  - Bug fixes only? Minor enhancements?
- **How frequently do we want to release patches?**
  - On-demand, weekly, bi-weekly?
- **Who are responsible for what?**
  - team? individual? role? 
- **What environments do we use (e.g., dev, test, staging, prod)?**
  - local
  - dev
  - test
  - prod
- **How do we track and document patches?**
  - Ticketing system, changelog, versioning

### 2.2 Questions to Resolve Down the Line

- **What testing is required before a patch can be released?**
  - Unit, integration, regression, smoke?

- **What is the rollback plan if a patch fails?**

- **Patch and Release checklist?**
  - Add relevant parts of the process into a checklist to confirm each item's accomplishment

---

## 3. Subjects to Include

### **Included in the Draft Version of the Process**
- Patch definition and scope
- Trigger for patch creation (e.g., bug report)
- Approval and testing steps
- Basic release checklist
- Communication plan (who gets notified and how)
- Ownership and responsibilities
- Semantic versioning

### ⏳ **Wait to Implement Later**
- Automation (CI/CD pipelines, automated testing)
- Detailed rollback procedures
- Metrics and KPIs (e.g., patch success rate)
- Integration with monitoring/alerting tools
- Full documentation templates

---

## 4. Draft: High-Level Patch and Release Process

[See process in `patch-and-release.md`](./patch-and-release.md)
