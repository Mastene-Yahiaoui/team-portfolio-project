Read me file 

# Team Portfolio Project

A collaborative portfolio website showcasing the profiles of our Software Engineering team.

This project was developed using Git workflows to simulate a professional collaborative environment — featuring feature branches, pull requests, peer reviews, and conflict resolution before deployment through GitHub Pages.

---

## Team Members

| Name | Role | GitHub Username |
| --- | --- | --- |
| **Mastene Yahiaoui** | Team Lead | [@Mastene-Yahiaoui](https://github.com/Mastene-Yahiaoui) |
| **Mohammed Radhoine Amara** | Developer | [@Radhoine-Amara](https://github.com/Radhoine-Amara) |
| **Lydia Serine Laouamer** | Developer | [@lydiaserine](https://github.com/lydiaserine) |
| **Oumnia Rahma Gouasmia** | Developer | [@GOUASMIA-oumnia-rahma](https://github.com/GOUASMIA-oumnia-rahma) |

---

## Deployed Website

🔗 [Visit our Team Portfolio on GitHub Pages](https://mastene-yahiaoui.github.io/team-portfolio-project/)

---

## Team Retrospective Analysis

Throughout the development of our *Team Portfolio Project*, our team encountered multiple technical challenges that helped us better understand collaborative workflows in Git and the importance of quality control in deployment.

One of the most significant challenges emerged during the **collaboration phase**, when a teammate accidentally **reverted a pull request instead of merging it**. This caused several key files—including the favicon assets and one team member’s HTML page—to disappear from the `develop` branch. Resolving this required a deep dive into Git conflict resolution, including restoring deleted files, re-merging branches, and using `git pull origin develop` to synchronize the team’s local work with the remote repository.

Later, another challenge appeared during the **final integration step**. When merging multiple feature branches into `develop`, we encountered several **rename/delete conflicts** involving the favicon assets. Git treated our directory restructuring (`assets/favicon` → `assets/favicons`) as simultaneous rename and delete operations, forcing us to manually choose the correct version of each file and re-stage the fixed ones. This taught us the importance of maintaining consistent file paths and coordination before committing structural changes.

After deployment via **GitHub Pages**, we discovered an **incorrect hyperlink** in the main `index.html` page — one team member’s link was pointing to an outdated file path from before the last refactor. This issue highlighted the critical need for **post-deployment verification** and taught us to test all internal links and assets after each merge. The fix required creating a small update branch, committing the correction, and reopening a pull request to patch the live site.

These issues reinforced the importance of a systematic workflow: creating feature branches, performing pull requests, and conducting code reviews before merging. The **peer review process** in particular proved effective, allowing us to catch inconsistencies and maintain high-quality integration.

Overall, this project simulated a realistic software engineering environment — involving real-world version control challenges, conflict resolution, and post-deployment debugging — and helped the team strengthen both our technical collaboration and project management skills.

---

## Tech Stack

- **Frontend:** HTML, CSS
- **Version Control:** Git & GitHub
- **Workflow:** Feature Branches, Pull Requests, Code Reviews, Merge Conflict Resolution
- **Deployment:** GitHub Pages

---

## Project Workflow Summary

1. **Initialization (Phase 1)**
    - Repository created and cloned.
    - Branch protection rules applied to `main`.
    - `develop` branch created for active development.
    - Team members listed in `README.md`.
2. **Feature Development (Phase 2)**
    - Each member created a personal feature branch from `develop`.
    - Individual profile pages implemented and linked in `index.html`.
    - Pull requests opened → peer-reviewed → merged into `develop`.
3. **Integration & Deployment (Phase 3)**
    - Final pull request merged `develop` into `main`.
    - Site deployed via GitHub Pages.
    - README updated with final deliverables and retrospective analysis.

---

© 2025 — Team Portfolio Project | ENSIA Software Engineering