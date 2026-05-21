# 💾 Upload Project to GitHub
### `RETRO TERMINAL EDITION 👾`

<div align="center">

```text
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
 SYSTEM :: GITHUB UPLOADER
 STATUS :: ONLINE
 MODE   :: RETRO DEV
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

> Learn how to upload your project to GitHub using Git commands like a true terminal wizard ⚡

---

# 📦 What You’ll Learn

✔ Initialize Git repository  
✔ Track project changes  
✔ Create commits  
✔ Connect to GitHub  
✔ Upload project online  
✔ Maintain future updates  

---

# 🖥️ STEP 1 — Initialize Git Repository

Turn your project folder into a Git repository.

```bash
git init
```

### 📼 Output

```text
Initialized empty Git repository
```

### 🧠 What This Does

Creates a hidden `.git` folder that tracks:
- project history
- changes
- commits
- branches

---

# 🧹 STEP 2 — Create `.gitignore`

Create file:

```text
.gitignore
```

Add files/folders you don't want uploaded.

Example:

```bash
.venv
node_modules
__pycache__
.env
```

---

# 📦 STEP 3 — Add Files to Git

Prepare all files for commit.

```bash
git add .
```

### 📼 Output

```text
✔ Files Added
```

---

# 💾 STEP 4 — Create First Commit

Save a snapshot of your project.

```bash
git commit -m "Initial commit"
```

### 📼 Output

```text
✔ Commit Created
```

### 🧠 What Is a Commit?

A commit is like:
> a save point for your project.

Git stores every commit in history.

---

# 🌐 STEP 5 — Create GitHub Repository

Go to:

👉 https://github.com

Then:

1. Click **New Repository**
2. Enter repository name
3. Click:

```text
CREATE REPOSITORY
```

---

# 🔗 STEP 6 — Connect Local Project to GitHub

Connect your local folder to online GitHub repository.

```bash
git remote add origin https://github.com/Royalcaptain-v2/Reinforcement-Learning-Load-Balancer-.git
```

### 📼 Output

```text
✔ Remote Repository Connected
```

---

# 🌿 STEP 7 — Rename Branch to Main

```bash
git branch -m main
```

### 🧠 Why?

Modern GitHub repositories use:

```text
main
```

instead of:

```text
master
```

---

# 🚀 STEP 8 — Push Project to GitHub

Upload everything online.

```bash
git push -u origin main
```

### 📼 Output

```text
⬆ Uploading Objects...
⬆ Compressing Files...
⬆ Sending Data...
✔ PUSH COMPLETE
```

---

# 🔄 FUTURE WORKFLOW

Whenever you update your project:

```bash
git add .
git commit -m "Updated project"
git push
```

---

# 👾 TERMINAL CHEAT SHEET

| Command | Purpose |
|---|---|
| `git init` | Initialize Git repository |
| `git add .` | Add files |
| `git commit` | Save snapshot |
| `git push` | Upload project |
| `git pull` | Download latest updates |

---

# ☢️ COMMON ERRORS

## ❌ Authentication Failed

GitHub now uses:
- Personal Access Tokens
- GitHub login

NOT account passwords.

---

## ❌ Repository Not Found

Usually means:
- wrong repository URL
- repository is private
- typo in repository name

---

# 📁 Recommended Tutorial Repository Structure

```text
retro-dev-tutorials/
│
├── github-upload-guide/
│   └── README.md
│
├── fastapi-deployment/
│   └── README.md
│
├── reinforcement-learning-load-balancer/
│   └── README.md
│
└── assets/
```

---

# 🔥 Pro Tip

Use:
- screenshots
- GIFs
- terminal screenshots
- ASCII art
- badges

to make tutorials look more alive.

Example:

```md
![Python](https://img.shields.io/badge/Python-3.11-blue)
```

---

# 🎉 FINAL RESULT

Your project is now:

✅ Online  
✅ Version Controlled  
✅ Shareable  
✅ Backed Up  
✅ Developer Approved 🚀  

---

<div align="center">

```text
╔══════════════════════════════╗
║      UPLOAD SUCCESSFUL       ║
║      GITHUB :: CONNECTED     ║
║      STATUS :: ONLINE        ║
╚══════════════════════════════╝
```

</div>
