# Contributing to GoGit-5.0

Thank you for your interest in contributing to **GoGit-5.0**. This project is designed to help you practice Git and GitHub fundamentals while following a structured workflow. Please read this document carefully before submitting any work.

---

## 1. General Contribution Rules

- Work only on issues assigned to you.
- Comment **"I would like to work on this issue"** before starting.
- Complete tasks within the given time limit (usually 2 days).
- Every PR must be linked to the issue it resolves.
- Commit messages should be meaningful and specific.
- Avoid unnecessary commits; fix or squash them before submitting.
- Be respectful while communicating with maintainers and contributors.

---

## 2. Basic Git Workflow

### Fork the Repository

Fork the repo on github to your personal account

### Clone the Repository

```
git clone https://github.com/<Your-username>/GoGit-5.0
cd GoGit-5.0
```

### Create a Branch if required in the issue

```
git switch -c <branch-name>
```

### Check Current Status

```
git status
```

### Stage and Commit Changes

```
git add .
git commit -m "<brief and meaningful commit message>"
```

### Push Your Work

```
git push origin <branch-name>
```

### Pull Latest Changes From Main

```
git pull origin main
```

### Switch Branches

```
git switch <branch-name>
```

---

## 3. Fixing Common Issues

### Update the Previous Commit Message

```
git commit --amend
```

### Squash Multiple Commits

```
git rebase -i HEAD~<number-of-commits>
```

### Undo Last Commit (without losing changes)

```
git reset --soft HEAD~1
```

---

## 4. Submitting a Pull Request

1. Push your code to GitHub on your own fork.
2. Open a Pull Request from your branch to `main`.
3. Fill out the PR template properly.
4. Wait for review and apply requested changes if needed.

---

## 5. Final Notes

- Keep contributions focused and relevant.
- Ask questions if anything is unclear.
- This repository is for learning; mistakes are acceptable as long as improvement follows.

Thank you for contributing to **GoGit-5.0**.
Your effort helps the entire community grow.
