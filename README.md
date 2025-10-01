# 🚀 Git Branching & Merging Demo  

A hands-on project to **learn and practice Git branching, merging, conflict resolution, and collaboration workflows**.  
This repository demonstrates real-world scenarios like creating feature branches, resolving conflicts, and safely deleting branches before pushing to GitHub.  

---

## 📌 Project Overview  
This project is designed as a **Git practice lab** to understand:  
- Creating and switching between branches  
- Merging feature branches into `main`  
- Handling merge conflicts  
- Safe (`-d`) vs Force (`-D`) branch deletion  
- Viewing commit history with logs and graphs  
- Pushing code to remote repositories  

---

## 🛠️ Commands Practiced  
Some of the key Git commands used in this project:  

```bash
# Clone repository
git clone <repo-url>

# Check repo status & history
git status -s
git log --oneline --graph --all --decorate

# Branch operations
git branch <branch_name>
git checkout <branch_name>
git checkout -b <new_branch>

# Stage & commit
git add .
git commit -m "commit message"

# Merging branches
git merge <branch_name>

# Delete branches
git branch -d <branch_name>   # safe delete
git branch -D <branch_name>   # force delete

# Push changes to remote
git push
```
# 📂 Branch Workflow 

This project demonstrates a simple Git branching workflow where different features were developed in separate branches and then merged into `main`.

![](/image/img2.png)
---

## 🔀 Branch Details & 🗂️ Project Structure
![](/image/img1.png)



