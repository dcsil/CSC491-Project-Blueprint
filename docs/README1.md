# 📑 Project Reference Manifest

This document outlines the pre-configured structure of the **CSC491 Project Blueprint**. These labels, milestones, and issues represent the standard development lifecycle for this course.

## 🏷️ Standardized Labels
We use a categorized labeling system to make the Kanban board easily filterable.

### Technical Categories
Used to identify the scope of work for each card:
* `tool-selection`, `deployment-platform`, `ui-design`
* `database-design`, `database-integration`
* `testing`, `unit-testing`, `reliability`, `resilience`
* `cloud-deployment`, `database-hosting`

### Milestone Labels
Used for quick visual identification of deliverable alignment:
* `milestone-1` through `milestone-6`

---

## 🗓️ Milestones (Deliverables)
The project is divided into 6 major milestones. Each milestone in GitHub is linked to a specific set of technical goals:

1. **Planning & Tool Selection:** Finalizing the stack and environment.
2. **UI Design:** Frontend architecture and user experience.
3. **Database Design:** Schema modeling and documentation.
4. **Database Integration & Testing:** Connectivity and CRUD operations.
5. **Local Reliability & Resilience Testing:** Ensuring stability under stress.
6. **Cloud Deployment & Database Hosting:** Production-ready environment setup.

---

## 📋 Pre-Configured Issues (30 Total)
This blueprint includes 30 template issues (5 per milestone). Each issue is pre-populated with:
* **Task Checklists:** Step-by-step technical requirements.
* **Acceptance Criteria:** Definition of what must be true to close the issue.
* **Automated Linking:** All issues are pre-assigned to their respective Milestones and Labels.

### Issue Breakdown
| Category | Issue Count | Primary Goal |
| :--- | :---: | :--- |
| Tooling & Platform | 5 | Environment & Stack setup |
| UI Design | 5 | Frontend implementation |
| DB Design | 5 | Data modeling |
| DB Integration | 5 | Backend connectivity |
| Reliability/Resilience | 5 | Error handling & Stress testing |
| Cloud/Hosting | 5 | Deployment & DevOps |

---

## 🛠️ Instructions for Students

1. **Audit the Issues:** Review the 30 issues in the [Issues Tab](https://github.com/dcsil/csc491-w2026-templates/issues).
2. **Customize:** While these are provided as a blueprint, you should edit the descriptions to fit your specific technology choices (e.g., if you choose PostgreSQL vs. MongoDB).
3. **Assigning Work:** Do not assign all 30 issues at once. Only assign issues to team members that are part of the *current* sprint.
4. **Re-running Scripts:** If you accidentally delete these issues, the `create_issues.py` script in the source folder can be used to regenerate the baseline.

> **Pro-Tip:** Use the "Group by Milestone" view on your Kanban board to see how these 30 issues distribute across your semester timeline.
