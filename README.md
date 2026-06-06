# VCS Task

## Project Overview

This project demonstrates the implementation of Version Control System (VCS) operations using Git and GitHub in a Linux environment (WSL Ubuntu). The task includes creating a local project directory, adding shell script files, initializing a Git repository, connecting it to GitHub, and performing essential Git operations such as commit, push, stash, merge, and rebase.

---

## Technologies Used

* WSL Ubuntu
* Git
* GitHub
* Shell Scripting

---

## Project Structure

```
vcs-task/
│
├── script1.sh
├── script2.sh
├── script3.sh
└── screenshots/
```

---

## Shell Scripts

### script1.sh

Prints a simple message from Script 1.

### script2.sh

Prints a simple message from Script 2.

### script3.sh

Prints a simple message from Script 3.

---

## Git Operations Performed

### 1. Git Repository Initialization

Initialized a local Git repository using:

```bash
git init
```

### 2. Adding Files

Added project files to the staging area:

```bash
git add .
```

### 3. Commit Changes

Created the initial commit:

```bash
git commit -m "Initial commit with shell scripts"
```

### 4. Connect Local Repository to GitHub

Added the remote GitHub repository:

```bash
git remote add origin https://github.com/Thirulok007/vcs-task.git
```

### 5. Push Code to GitHub

Uploaded project files to GitHub:

```bash
git push -u origin main
```

---

## Git Stash Demonstration

Modified project files and temporarily stored the changes using:

```bash
git stash
```

Verified the stash list using:

```bash
git stash list
```

---

## Git Merge Demonstration

Created a feature branch and merged it into the main branch.

Commands used:

```bash
git checkout -b feature-branch
git commit -m "Updated script2 in feature branch"
git checkout main
git merge feature-branch
```

---

## Git Rebase Demonstration

Created a rebase demonstration branch and rebased it with the latest main branch changes.

Commands used:

```bash
git checkout -b rebase-demo
git commit -m "Updated script3 for rebase demo"
git checkout main
git commit -m "Main branch update"
git checkout rebase-demo
git rebase main
```

---

## Screenshots

The screenshots folder contains evidence of:

* Git Initialization
* Git Status
* Git Commit
* Git Push
* Git Stash
* Git Merge
* Git Rebase
* GitHub Repository

---

## Outcome

Successfully created and managed a Git repository, connected it with GitHub, and demonstrated Git version control operations including commit, push, stash, merge, and rebase using WSL Ubuntu and GitHub.
