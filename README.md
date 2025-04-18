# DevOps Project

# 🚀 DevOps Version Control Project with Git

## 📑 Project Overview
This project is built as part of the DevOps Internship Task 4.  
The goal is to **manage a project using Git best practices**, including:
- Repository initialization
- Branching (main, dev, feature branches)
- Pull Requests and Merges
- Version tagging
- Documentation using markdown

This simulates a **real-world Git workflow** followed in professional DevOps teams.

---

## 🛠️ Tools Used
- **Git** (Version Control System)
- **GitHub** (Remote repository hosting)
- **Markdown** (For documentation)

---

## 🛤Git Workflow Followed

1. **Initialize Repository**  
   - Local Git repo created using `git init`.
   - Connected to GitHub using `git remote add origin`.

2. **Branching Strategy**  
   - `main` → Stable production-ready branch.
   - `dev` → Development integration branch.
   - `feature/*` → Feature-specific branches created from `dev`.

3. **Feature Development**  
   - All features were developed on individual `feature/*` branches.

4. **Pull Requests (PRs)**  
   - After feature development, PRs were created to merge into `dev`.
   - Code review and PR merge done through GitHub.

5. **Tagging**  
   - Important releases were tagged (example: `v1.0`) using `git tag`.

6. **Documentation**  
   - All important processes and steps documented inside `docs/` folder.

---


---

## 📝 Important Git Commands Used

| Purpose | Command |
|:---|:---|
| Initialize Git | `git init` |
| Add files | `git add .` |
| Commit changes | `git commit -m "message"` |
| Create branch | `git checkout -b branch-name` |
| Push branch | `git push -u origin branch-name` |
| Create tag | `git tag v1.0` + `git push origin v1.0` |
| Create Pull Request | Through GitHub UI |
| Merge Pull Request | After review, through GitHub UI |

---

## 📜 Version Tags
- **v1.0** → Initial project setup complete with basic Git workflow.

---

## 📋 Key Learnings

- How to initialize and organize a Git project
- Proper branching strategy (main, dev, feature branches)
- Making clean commits with meaningful messages
- Creating and handling Pull Requests
- Resolving merge conflicts (if any)
- Using Git Tags for versioning
- Writing clear documentation in markdown

---

## 📣 How to Run/Clone this Project

```bash
# Clone the repository
git clone https://github.com/anshu15183/git-branching.git

# Navigate into project directory
cd git-branching

# Check branches
git branch -a

# Checkout to dev or feature branches as needed
git checkout dev


