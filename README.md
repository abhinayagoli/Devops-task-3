
# DevOps Task 3: Version-Controlled DevOps Project using Git & GitHub

This project is part of my DevOps internship and demonstrates the use of Git best practices to manage a version-controlled project. The goal was to understand and implement branching strategies, pull requests, tagging, and proper documentation using Git and GitHub.

---

## 📁 Project Structure

This repo includes:

- `.gitignore` – to ignore unnecessary files
- `README.md` – this documentation file
- `TASK_LOG.md` – logs of activities performed
- `sample.txt` – a test file used for Git operations

---

## 🛠️ Git Workflow Followed

### ✅ Branches Created:
- `main` – production-ready branch
- `dev` – development integration branch
- `feature` – used to implement individual features

### ✅ Key Actions:
- Initialized Git repository
- Created and pushed branches (`main`, `dev`, `feature`)
- Made a change in `feature` branch (`sample.txt`)
- Created a Pull Request from `feature` → `dev`
- Merged the Pull Request using GitHub UI
- Created Git tag `v1.0` after the merge

---

## 🔖 Git Tag

- Created version tag: `v1.0`
- Tag message: `Initial release after feature merge`

---

## 💬 Important Git Commands Used

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <repo-url>
git branch -M main
git push -u origin main

git checkout -b dev
git push origin dev

git checkout -b feature
echo "This line is added in the feature branch" >> sample.txt
git add sample.txt
git commit -m "Updated sample.txt from feature branch"
git push origin feature

# Tag
git tag -a v1.0 -m "Initial release after feature merge"
git push origin v1.0
```

---

## 🙋‍♀️ Author

**Goli Abhinaya**  
DevOps Internship Trainee

---

## 📌 Task Objective

To learn version control workflows and apply Git fundamentals such as:
- Branching
- Merging
- Pull requests
- Tags
- Documentation

---
