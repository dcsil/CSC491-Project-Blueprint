# 📋 CSC491 Project Blueprint

This repository serves as a functional reference and starter guide for implementing a high-velocity Kanban workflow. 

> [!IMPORTANT]
> This repository is a **blueprint**, not a literal template to be copied. You should build your own project board from scratch to best reflect your team's specific needs and unique project architecture.


---

## ⚠️ CSC491 Project Board

This repository is linked to the **[Live Project Board](https://github.com/orgs/dcsil/projects/108/views/2)**. Use it solely as a visual reference of project status.

* Do **not** add tasks, cards, or comments directly to this board. You cannot do manual "drag-and-drop" overrides in project view.
* Use strictly **code to drive the board status**, not manual intervention. This means you can create your own custom [GitHub Workflows](https://github.com/dcsil/CSC491-Project-Blueprint/tree/main/.github/workflows) to automate label assignments or trigger card movement between columns.
* Use the project board to observe the current lifecycle of issues. It is a **real-time** representation of ongoing work; it does not function as a static to-do list but rather as a mirror of development activity.
* The project board has no versioning or history or **snapshot** feature. Status updates are only captured visually in the present moment. You cannot scroll back to view the board's state from previous weeks. Use this for immediate visibility, not as a historical record.

---

## 🚀 Why This Workflow?

We utilize GitHub Projects not just as a static management tool, but as a dynamic engine for **Sprinting**. By keeping our planning exactly where our code lives, we eliminate the "tooling gap" and maintain constant momentum.

* **Zero-Distance to Code:** Issues and Pull Requests are first-class citizens. There is no manual syncing—the **code is the status**.
* **Built for Sprinting:** Unlike traditional project trackers, this board is designed for rapid cycles. It facilitates quick item entry, immediate assignment, and real-time visibility into the current sprint's health.
* **The De Facto Standard:** GitHub Projects has become the industry standard for streamlined, integrated developer workflows, replacing heavy third-party software with a native experience.
* **Fully Free:** All features used in this blueprint—including advanced automations—are available on GitHub’s free tier.

---

## 📖 Quick Tutorial: How to Use Projects

At this stage, it is important to recognize that you are using the **GitHub Repository** for code management and **GitHub Projects** for progress tracking. Although these are set up independently, they must be linked so your project board can accurately reflect the real-time progress of your codebase.

> [!IMPORTANT]
> This guide covers the setup and workflow for your **Project board**. It is **not** the instruction set for your formal assignment submissions. This guide is merely intended to help you link your repository and your project for tracking purposes. 
> **Always reference Quercus for official assignment instructions and submission requirements.**

### 1. Link Your Repository
Ensure your Kanban board is pulling data from the correct source:
* Go to **Settings** > **Linked repositories**.
* Add the repository you are currently working on.

### 2. Issues as "Cards"
* **Create Issues:** Avoid using "Draft" cards. Create actual **Issues** in the repo for every task.
* **Assign Project:** In the Issue sidebar, select your project board to make the card appear.
* **Granular Tracking:** Use issues to break down the specific work required for each feature.

### 3. Pull Requests & Automation
Let the board update itself as you code:
* **Link PRs:** In your Pull Request description, use keywords like `Closes #123`.
* **Enable Workflows:** Click the **Workflows** (lightning bolt) icon to automate card movement:
    * `Pull request merged` → Move to **Done**.
    * `Ready for review` → Move to **In Review**.

### 4. Releases & Milestones
Organize your board around your deliverables:
* **Release Column:** Add a dedicated **Release** column to your board. 
* **PR-Centric Releases:** High-level Releases should reference Pull Requests rather than individual issues. This ensures that only reviewed and merged code is represented in a release.
* **Deliverable Milestones:** Link **Milestones** directly to your Releases. The recommended workflow is that each Release/Milestone represents one specific assignment deliverable.

---

## 🛠 Best Practices
* **Keep it Current:** If you start a task, move it to "In Progress."
* **Link Everything:** Never open a PR without linking it to an Issue.
* **Clean Up:** Periodically archive items in the "Done" column after a successful Release.

---

## 🔗 Useful Links

To help you navigate this blueprint, use the following links to explore the live configuration and deep-dive into the setup:

* **[Live Project Board](https://github.com/orgs/dcsil/projects/108/views/2):** View the sample Kanban board in action to see how Issues, Labels, and Milestones are visualized.
* **[Project Board Settings](https://github.com/orgs/dcsil/projects/108/settings):** Explore how the backend of the project is configured, including custom fields and automated workflows.
* **[Manifest Configuration Guide](./docs):** Visit the `/docs` directory to learn how the labels, milestones, and issue templates in this repository were designed and implemented.
