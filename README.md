# DevOps Project – Version Controlled with Git

## 📌 Objective
Manage a DevOps project using Git best practices, including proper branching, commits, pull requests, and documentation.

## 🛠️ Tools Used
- Git
- GitHub

## 📂 Branching Strategy
This repository follows a structured branching strategy:

- `main` – Stable production-ready code
- `dev` – Integration branch for development
- `feature/*` – Feature-specific branches (e.g., `feature/login`, `feature/ui`)

## 🔀 Git Workflow
1. Clone the repository:
   ```bash
   git clone https://github.com/ashnaash/internship-day-4.git
   ```

2. Create a new branch:
   ```bash
   git checkout -b feature/<your-feature-name>
   ```

3. Commit changes:
   ```bash
   git add .
   git commit -m "Add: <describe your changes>"
   ```

4. Push to GitHub:
   ```bash
   git push origin feature/<your-feature-name>
   ```

5. Create a Pull Request from GitHub UI to merge into `dev`, then into `main`.

## 📄 .gitignore
A `.gitignore` file is used to exclude unnecessary files like:
- `node_modules/`
- `.env`
- `*.log`
- `__pycache__/`

## 🏷️ Tags
Use Git tags for versioning stable releases:
```bash
git tag v1.0
git push origin v1.0
```

## 📝 Documentation
All tasks and updates will be documented using Markdown.

---

## ✅ Deliverables
- Proper Git commits with meaningful messages
- Feature and development branches
- Pull Requests for merging
- `.gitignore` and tags usage
- Markdown-based task documentation
