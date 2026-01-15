# 📑 Project Manifests & Workflow Example

This document showcases the pre-configured manifests within the **CSC491 Project Blueprint**. These serve as a functional example of how a typical web application project might be structured.

> [!IMPORTANT]
> **This is not a template to be copied blindly.** These configurations may or may not apply to your specific project scope. This manifest is intended to demonstrate how simple it is to set up your repository so that GitHub Projects can automatically track, visualize, and monitor your progress.

## 🏷️ Strategic Labeling
Labels are the primary way to make your Kanban board filterable and readable at a glance. We suggest using categories to identify the technical scope of each Issue.

### Example Technical Categories
In this blueprint, we have categorized work into specific domains:
* **Setup:** `tool-selection`, `deployment-platform`
* **Design:** `ui-design`, `database-design`
* **Development:** `database-integration`
* **Quality:** `testing`, `unit-testing`, `reliability`, `resilience`
* **DevOps:** `cloud-deployment`, `database-hosting`

---

## 🗓️ Milestone Alignment
Milestones provide high-level visibility for your deliverables. In this example, the project is divided into 6 major milestones, each linked to a specific set of technical goals:

| # | Milestone | Focus Area |
| :--- | :--- | :--- |
| 1 | **Planning & Tool Selection** | Finalizing the technology stack and development environment. |
| 2 | **UI Design** | Frontend architecture, wireframing, and user experience. |
| 3 | **Database Design** | Schema modeling, ERDs, and data documentation. |
| 4 | **Database Integration & Testing** | Backend connectivity, API development, and CRUD operations. |
| 5 | **Local Reliability & Resilience** | Ensuring system stability, error handling, and stress testing. |
| 6 | **Cloud Deployment & Hosting** | Production-ready environment setup and final cloud delivery. |

---

## 📋 Example Issues (30 Total)
To demonstrate how to populate a board effectively, we have included 30 example issues (5 per milestone). A well-structured issue ensures that any team member can pick up a task and understand the requirements immediately.

### Anatomy of these Example Issues:
* **Task Checklists:** Atomic, step-by-step technical requirements.
* **Acceptance Criteria:** A clear definition of what must be true to consider the issue "Done."
* **Automated Linking:** All issues are pre-assigned to their respective Milestones and Labels to show how GitHub Projects aggregates this data.

### Issue Distribution
| Category | Issue Count | Primary Goal |
| :--- | :---: | :--- |
| Tooling & Platform | 5 | Environment & Stack setup |
| UI Design | 5 | Frontend implementation |
| DB Design | 5 | Data modeling |
| DB Integration | 5 | Backend connectivity |
| Reliability & Resilience | 5 | Error handling & Stress testing |
| Cloud & Hosting | 5 | Deployment & DevOps |

---

**Next Step:** Use these examples as a guide to creating your own manifests that best represent your team's unique architecture and workflow.

---

## 🛠️ How to Leverage This Blueprint

To get the most out of this reference, we recommend the following workflow as you begin setting up your own project:

1.  **Audit the Example Issues:** Visit the [Issues Tab](https://github.com/dcsil/CSC491-Project-Blueprint/issues) to see how tasks are structured. Pay close attention to the level of detail in the checklists—this is the standard of documentation expected for a high-performing team.
2.  **Make it Your Own:** While these 30 issues provide a strong baseline, they are not "one-size-fits-all." You must customize the descriptions to reflect your specific tech stack (e.g., swapping generic database tasks for PostgreSQL-specific schema design).
3.  **Practice Intentional Assignment:** Avoid the temptation to assign all 30 issues at once. A healthy Kanban board reflects current reality; only assign issues to team members that are part of your **active sprint**.
4.  **Disaster Recovery:** If you accidentally delete or lose your configuration while experimenting, you can use the `create_issues.py` script located in the source folder to regenerate the baseline set of issues.

> [!TIP]
> **View by Milestone:** On your GitHub Project board, use the **"Group by Milestone"** feature. This will instantly transform your list of issues into a visual roadmap, showing you exactly how your workload is distributed across the semester timeline.
