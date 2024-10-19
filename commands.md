# Git Commands Cheat Sheet

This cheat sheet includes the most commonly used Git commands to help you work efficiently with Git.

---

## Git Configuration

- **Set your name:** `git config --global user.name "Your Name"`
- **Set your email:** `git config --global user.email "your-email@example.com"`
- **Check current configuration:** `git config --list`

---

## Repository Management

- **Initialize a new Git repository:** `git init`
- **Clone an existing repository:** `git clone <repository-URL>`
- **Check the status of your repository:** `git status`

---

## Staging & Committing

- **Add a specific file to the staging area:** `git add <file-name>`
- **Stage all changes:** `git add .`
- **Commit changes with a message:** `git commit -m "Your commit message"`

---

## Branching

- **List all branches:** `git branch`
- **Create a new branch:** `git branch <branch-name>`
- **Switch to a different branch:** `git checkout <branch-name>`
- **Create and switch to a new branch:** `git checkout -b <branch-name>`

---

## Merging Branches

- **Merge a branch into the current branch:** `git merge <branch-name>`
- **View all branches including merged ones:** `git branch --merged`

---

## Logs and History

- **View commit history:** `git log`
- **View commit history in one line:** `git log --oneline`

---

## Remote Repositories

- **Add a remote repository:** `git remote add origin <remote-URL>`
- **View all remotes:** `git remote -v`
- **Push changes to the remote repository:** `git push origin <branch-name>`
- **Pull changes from the remote repository:** `git pull origin <branch-name>`

---

## Tagging

- **Create a new tag:** `git tag <tag-name>`
- **List all tags:** `git tag`

---

## Undoing Changes

- **Unstage a file:** `git reset <file>`
- **Revert last commit but keep the changes:** `git reset --soft HEAD^`
- **Revert last commit and discard the changes:** `git reset --hard HEAD^`

---

## Helpful Git Workflow

1. **Create a new branch:** `git checkout -b feature-branch`
2. **Make changes and stage them:** `git add .`
3. **Commit your changes:** `git commit -m "Add new feature"`
4. **Switch back to the main branch:** `git checkout master`
5. **Merge the feature branch:** `git merge feature-branch`

---

## Other Useful Commands

- **Check current directory:** `pwd`
- **List files in the current directory:** `ls`
