
# 📘 DevOps Internship – Task 4 Documentation  

## 📝 Objective
The goal of this task was to practice **Git version control** with a proper branching workflow, pull requests, tagging, and documentation.  

---

## 🔨 Steps Performed  

### 1. Initialized Repository  
- Created a new folder and initialized Git using `git init`.  
- Linked the local repo to GitHub remote using:  
  ```bash
  git remote add origin <repo_url>
📸 Screenshot 1: Repository initialization

2. Branching Strategy
Default branch: main

Created dev branch for development:

bash
Copy code
git checkout -b dev
git push -u origin dev
Created feature branch feature/login:

bash
Copy code
git checkout -b feature/login
git push -u origin feature/login
📸 Screenshot 2: Branch creation

3. Added .gitignore
Added a .gitignore file to ignore logs, caches, and dependencies.
📸 Screenshot 3: .gitignore contents

4. Added Sample App
Created a simple Python app (app.py) for demonstration.

Example code:

python
Copy code
def main():
    print("Hello, DevOps Internship - Task 4!")
    print("This is a sample Python app to demonstrate Git workflow.")

if __name__ == "__main__":
    main()
📸 Screenshot 4: app.py file committed to GitHub

5. Commit and Push Workflow
Staged changes with git add .

Committed changes with git commit -m "Added sample app.py"

Pushed changes to feature/login branch.
📸 Screenshot 5: Commit history

6. Pull Request Workflow
Raised a PR from feature/login → dev.

Reviewed and merged.

Later merged dev → main.
📸 Screenshot 6: Pull Request on GitHub

7. Tags for Versioning
Created a version tag for the first stable release:

bash
Copy code
git tag v1.0
git push origin v1.0
📸 Screenshot 7: Git tag creation

8. Documentation in Markdown
Created README.md (overview) and docs.md (detailed report).
📸 Screenshot 8: docs.md preview on GitHub

🎯 Outcome
Learned to work with Git branching strategies (main, dev, feature).

Practiced Pull Request workflow.

Understood Git tags and releases.

Used .gitignore effectively.

Documented the process with markdown files.
