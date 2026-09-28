# 🚀 Advanced Git & GitHub Mastery Portfolio

## 📌 Project Overview
This repository serves as a practical demonstration of my proficiency in **Advanced Version Control using Git & GitHub**. As a Data Engineer, maintaining clean code history, collaborating safely, and debugging efficiently are critical skills. This project simulates a real-world development environment, showcasing complex Git workflows.

## 🛠️ Core Skills & Workflows Demonstrated

*   **Repository Initialization & Configuration:** Setting up environments, `.gitignore` for security (excluding secrets and virtual environments).
*   **Branching Strategies:** Creating, switching, and managing independent feature branches (`feature-update`, `feature_x`).
*   **Merge Conflict Resolution:** Deliberately simulating and manually resolving complex code conflicts between branches.
*   **Time Travel & Disaster Recovery:** Utilizing `git reset --hard` to rollback dangerous commits and eliminate bugs from history.
*   **History Rewriting:** Using Interactive Rebase (`git rebase -i`) to squash commits and maintain a clean, linear project history.
*   **Algorithmic Debugging:** Employing `git bisect` to perform binary searches through commit history to isolate the exact commit that introduced a critical bug.
*   **Worktrees & Stashing:** Managing multiple working environments simultaneously (`git worktree`) and temporarily shelving incomplete work (`git stash`).
*   **Version Tagging:** Creating immutable release points (e.g., `v1.0.0`) for production-ready code.

## 📂 Repository Structure
*   `extractor.py`: A simulated Python script for data extraction, used to test merge conflicts and rebasing.
*   `test_bisect.txt`: A file used specifically to demonstrate the `git bisect` automated debugging workflow.
*   `.gitignore`: Properly configured to protect sensitive data (`secrets.env`) and ignore `venv/` overhead.

---
*💡 "Version control is not just about saving code; it's about documenting the thought process and protecting the team's workflow."*

git pull origin main

## 📸 Project Proof & Screenshots

**1. Project Setup & Branching**
![Setup Phase](assets/1.png)

**2. Handling Merge Conflicts**
![Conflict Resolution](assets/2.png)

**3. Time Travel & History Rewriting**
![Time Travel](assets/3.png)
