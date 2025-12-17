# Python
Python codes, python projects. Started on 17 december 2025
# Python (iPad + GitHub sync)

This repository is my Python learning project.
I mainly write code on my iPad using **Pythonista** and use **Working Copy + GitHub** to sync everything with my Windows PC (VS Code).

---

## One-time setup

### 1. GitHub
- Create a repository (for example: `Python`).
- This repository is the single source of truth.

### 2. Working Copy (iPad)
- Open Working Copy.
- Clone this GitHub repository to your iPad.
- This creates a local repository folder that Git tracks.

### 3. Pythonista (iPad)
- Pythonista is used to **edit and run** `.py` files.
- The Python files you edit in Pythonista must be the **same files** that exist inside the Working Copy repository folder.

> Important:  
> - Pythonista runs the code  
> - Working Copy handles Git (commit, pull, push)

---

## Daily workflow (iPad → GitHub)

When you write or change code on the iPad:

1. Edit the Python files in Pythonista.
2. Open Working Copy.
3. Check that your changes are visible.
4. Create a **commit** (short description of what changed).
5. **Push** to GitHub.

---

## Daily workflow (Windows / VS Code)

When you continue working on Windows:

1. Open the repository in VS Code.
2. Always start with:
   ```bash
   git pull
