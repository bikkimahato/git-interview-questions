# Git Interview Questions
Welcome to the Git Repository Guide! This repository is designed to provide comprehensive guidance and best practices for using Git effectively. Whether you're a beginner or an experienced developer, you'll find useful information to enhance your Git skills.

## Introduction
Git is a powerful version control system used to manage code changes across projects of all sizes. This repository aims to provide clear and concise information to help you navigate and master Git.

## Getting Started
To get started with Git, follow these steps:
1. Install Git: [Git Downloads](https://git-scm.com/downloads)
2. Configure Git: 
    ```sh
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```
3. Initialize a repository:
    ```sh
    git init
    ```

## Basic Commands
Here are some fundamental Git commands:
- `git clone <repository-url>`: Clone an existing repository
- `git add <file>`: Add files to staging area
- `git commit -m "commit message"`: Commit changes
- `git push`: Push changes to the remote repository
- `git pull`: Fetch and merge changes from the remote repository

## Branching and Merging
Learn how to manage branches and merge changes:
- Create a new branch: `git checkout -b <branch-name>`
- Switch branches: `git checkout <branch-name>`
- Merge branches: `git merge <branch-name>`

## Advanced Techniques
Explore advanced Git techniques:
- Rebase: `git rebase <branch-name>`
- Stash changes: `git stash`
- Cherry-pick: `git cherry-pick <commit-hash>`

## Best Practices
Follow these best practices to ensure smooth collaboration:
- Commit frequently with meaningful messages
- Keep branches small and focused
- Use pull requests for code reviews

## Contributing

We welcome contributions from the community! If you have a question or improvement that you think should be included, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution.
3. Add your question or improvement in the appropriate category folder (`easy`, `medium`, `hard`).
4. Submit a pull request with a detailed description of your changes.

---

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

### Table of Contents
### Level : Easy
| No. | Questions |
| --- | --------- |
| 1   | [What is Git?](#1-what-is-git) |
| 2   | [How do you initialize a new Git repository?](#2-how-do-you-initialize-a-new-git-repository) |
| 3   | [How do you clone a repository?](#3-how-do-you-clone-a-repository) |
| 4   | [What is the command to check the status of your working directory?](#4-what-is-the-command-to-check-the-status-of-your-working-directory) |
| 5   | [How do you stage a file for commit?](#5-how-do-you-stage-a-file-for-commit) |
| 6   | [How do you commit changes to a repository?](#6-how-do-you-commit-changes-to-a-repository) |
| 7   | [What command do you use to view the commit history?](#7-what-command-do-you-use-to-view-the-commit-history) |
| 8   | [How do you create a new branch?](#8-how-do-you-create-a-new-branch) |
| 9   | [How do you switch to an existing branch?](#9-how-do-you-switch-to-an-existing-branch) |
| 10  | [How do you merge a branch into the current branch?](#10-how-do-you-merge-a-branch-into-the-current-branch) |
| 11  | [What is the difference between `git pull` and `git fetch`?](#11-what-is-the-difference-between-git-pull-and-git-fetch) |
| 12  | [How do you delete a branch locally?](#12-how-do-you-delete-a-branch-locally) |
| 13  | [How do you delete a branch remotely?](#13-how-do-you-delete-a-branch-remotely) |
| 14  | [How do you undo the last commit?](#14-how-do-you-undo-the-last-commit) |
| 15  | [How do you discard changes in a file?](#15-how-do-you-discard-changes-in-a-file) |
| 16  | [How do you list all branches in a repository?](#16-how-do-you-list-all-branches-in-a-repository) |
| 17  | [How do you create a new tag?](#17-how-do-you-create-a-new-tag) |
| 18  | [How do you push changes to a remote repository?](#18-how-do-you-push-changes-to-a-remote-repository) |
| 19  | [How do you pull changes from a remote repository?](#19-how-do-you-pull-changes-from-a-remote-repository) |
| 20  | [How do you set your Git username and email?](#20-how-do-you-set-your-git-username-and-email) |
| 21  | [What is a commit message and why is it important?](#21-what-is-a-commit-message-and-why-is-it-important) |
| 22  | [How do you view the changes made to a file?](#22-how-do-you-view-the-changes-made-to-a-file) |
| 23  | [How do you rename a branch?](#23-how-do-you-rename-a-branch) |
| 24  | [How do you move or rename a file?](#24-how-do-you-move-or-rename-a-file) |
| 25  | [What is the difference between `git reset` and `git revert`?](#25-what-is-the-difference-between-git-reset-and-git-revert) |

### Table of Contents
### Level : Medium
| No. | Questions |
| --- | --------- |
| 1   | [What is a Git repository?](#1-what-is-a-git-repository) |
| 2   | [Explain the difference between a local and remote repository.](#2-explain-the-difference-between-a-local-and-remote-repository) |
| 3   | [What is a commit hash?](#3-what-is-a-commit-hash) |
| 4   | [How do you resolve merge conflicts?](#4-how-do-you-resolve-merge-conflicts) |
| 5   | [Explain the difference between `git merge` and `git rebase`.](#5-explain-the-difference-between-git-merge-and-git-rebase) |
| 6   | [How do you stash changes in Git?](#6-how-do-you-stash-changes-in-git) |
| 7   | [How do you apply stashed changes?](#7-how-do-you-apply-stashed-changes) |
| 8   | [What is the purpose of the `.gitignore` file?](#8-what-is-the-purpose-of-the-gitignore-file) |
| 9   | [How do you revert a commit that has already been pushed to the remote repository?](#9-how-do-you-revert-a-commit-that-has-already-been-pushed-to-the-remote-repository) |
| 10  | [How do you cherry-pick a commit?](#10-how-do-you-cherry-pick-a-commit) |
| 11  | [What is the difference between `git diff` and `git log`?](#11-what-is-the-difference-between-git-diff-and-git-log) |
| 12  | [How do you create a new branch and push it to the remote repository in one command?](#12-how-do-you-create-a-new-branch-and-push-it-to-the-remote-repository-in-one-command) |
| 13  | [What is `git bisect` and how is it used?](#13-what-is-git-bisect-and-how-is-it-used) |
| 14  | [How do you squash commits?](#14-how-do-you-squash-commits) |
| 15  | [How do you create a bare repository?](#15-how-do-you-create-a-bare-repository) |
| 16  | [What is a detached HEAD state?](#16-what-is-a-detached-head-state) |
| 17  | [How do you configure a remote upstream branch?](#17-how-do-you-configure-a-remote-upstream-branch) |
| 18  | [How do you set up a Git hook?](#18-how-do-you-set-up-a-git-hook) |
| 19  | [How do you force push to a remote repository?](#19-how-do-you-force-push-to-a-remote-repository) |
| 20  | [What are submodules in Git?](#20-what-are-submodules-in-git) |
| 21  | [How do you clone a repository with submodules?](#21-how-do-you-clone-a-repository-with-submodules) |
| 22  | [Explain the difference between `git reset --soft`, `--mixed`, and `--hard`.](#22-explain-the-difference-between-git-reset-soft-mixed-and-hard) |
| 23  | [How do you find a specific commit in the history?](#23-how-do-you-find-a-specific-commit-in-the-history) |
| 24  | [How do you change the last commit message?](#24-how-do-you-change-the-last-commit-message) |
| 25  | [What is the difference between an annotated and a lightweight tag?](#25-what-is-the-difference-between-an-annotated-and-a-lightweight-tag) |

### Table of Contents
### Level : Hard
| No. | Questions |
| --- | --------- |
| 1   | [What is Git rebasing and what are its advantages and disadvantages?](#1-what-is-git-rebasing-and-what-are-its-advantages-and-disadvantages) |
| 2   | [How do you perform an interactive rebase?](#2-how-do-you-perform-an-interactive-rebase) |
| 3   | [How do you handle a situation where you accidentally pushed sensitive information to a public repository?](#3-how-do-you-handle-a-situation-where-you-accidentally-pushed-sensitive-information-to-a-public-repository) |
| 4   | [How do you optimize a repository for performance?](#4-how-do-you-optimize-a-repository-for-performance) |
| 5   | [Explain the internal structure of a Git repository.](#5-explain-the-internal-structure-of-a-git-repository) |
| 6   | [How do you handle large binary files in Git?](#6-how-do-you-handle-large-binary-files-in-git) |
| 7   | [What is the purpose of the `git fsck` command?](#7-what-is-the-purpose-of-the-git-fsck-command) |
| 8   | [How do you clean up a repository with a large history?](#8-how-do-you-clean-up-a-repository-with-a-large-history) |
| 9   | [Explain the concept of Git object model (blobs, trees, commits, etc.).](#9-explain-the-concept-of-git-object-model-blobs-trees-commits-etc) |
| 10  | [How do you recover from a corrupted repository?](#10-how-do-you-recover-from-a-corrupted-repository) |
| 11  | [How do you set up a Git server?](#11-how-do-you-set-up-a-git-server) |
| 12  | [What is the difference between `git archive` and `git bundle`?](#12-what-is-the-difference-between-git-archive-and-git-bundle) |
| 13  | [How do you manage multiple repositories in a single project?](#13-how-do-you-manage-multiple-repositories-in-a-single-project) |
| 14  | [How do you track changes to a specific directory?](#14-how-do-you-track-changes-to-a-specific-directory) |
| 15  | [What is the purpose of the `reflog`?](#15-what-is-the-purpose-of-the-reflog) |
| 16  | [How do you bisect a repository with many branches?](#16-how-do-you-bisect-a-repository-with-many-branches) |
| 17  | [How do you configure Git to use a different merge tool?](#17-how-do-you-configure-git-to-use-a-different-merge-tool) |
| 18  | [How do you use `git filter-branch` to rewrite history?](#18-how-do-you-use-git-filter-branch-to-rewrite-history) |
| 19  | [What are the risks of force-pushing to a shared repository?](#19-what-are-the-risks-of-force-pushing-to-a-shared-repository) |
| 20  | [How do you manage Git credentials securely?](#20-how-do-you-manage-git-credentials-securely) |
| 21  | [Explain what a Git worktree is and how to use it.](#21-explain-what-a-git-worktree-is-and-how-to-use-it) |
| 22  | [How do you enforce commit message guidelines?](#22-how-do-you-enforce-commit-message-guidelines) |
| 23  | [How do you use `git blame` to find the author of a specific line of code?](#23-how-do-you-use-git-blame-to-find-the-author-of-a-specific-line-of-code) |
| 24  | [What is the difference between shallow cloning and a full clone?](#24-what-is-the-difference-between-shallow-cloning-and-a-full-clone) |
| 25  | [How do you handle a situation where a merge introduces a bug that needs to be fixed without reverting the merge?](#25-how-do-you-handle-a-situation-where-a-merge-introduces-a-bug-that-needs-to-be-fixed-without-reverting-the-merge) |

# Easy Git Interview Questions and Answers
### 1. What is Git?

Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows multiple people to collaborate on a project, track changes, and revert to previous versions if needed.

#### **[⬆ Back to Top](#level--easy)**
---

### 2. How do you initialize a new Git repository?

To initialize a new Git repository, navigate to your project directory and use the following command:

```sh
git init
```

This command creates a new `.git` subdirectory in your project directory, which contains all the necessary metadata for the repository.

#### **[⬆ Back to Top](#level--easy)**
---

### 3. How do you clone a repository?

To clone an existing repository, use the following command:

```sh
git clone <repository_url>
```

For example:

```sh
git clone https://github.com/user/repository.git
```

This command creates a new directory with the name of the repository and copies all the repository data into it.

#### **[⬆ Back to Top](#level--easy)**
---

### 4. What is the command to check the status of your working directory?

To check the status of your working directory, use:

```sh
git status
```

This command shows which files have been modified, which files are staged for commit, and which files are not being tracked by Git.

#### **[⬆ Back to Top](#level--easy)**
---

### 5. How do you stage a file for commit?

To stage a file for commit, use:

```sh
git add <file_name>
```

For example:

```sh
git add README.md
```

You can also stage all modified files at once using:

```sh
git add .
```

#### **[⬆ Back to Top](#level--easy)**
---

### 6. How do you commit changes to a repository?

To commit changes, use:

```sh
git commit -m "Your commit message"
```

For example:

```sh
git commit -m "Add initial project files"
```

The `-m` flag allows you to add a commit message directly from the command line.

#### **[⬆ Back to Top](#level--easy)**
---

### 7. What command do you use to view the commit history?

To view the commit history, use:

```sh
git log
```

This command lists all the commits along with their messages, authors, and timestamps.

#### **[⬆ Back to Top](#level--easy)**
---

### 8. How do you create a new branch?

To create a new branch, use:

```sh
git branch <branch_name>
```

For example:

```sh
git branch feature-xyz
```
#### **[⬆ Back to Top](#level--easy)**
---

### 9. How do you switch to an existing branch?

To switch to an existing branch, use:

```sh
git checkout <branch_name>
```

For example:

```sh
git checkout feature-xyz
```
#### **[⬆ Back to Top](#level--easy)**
---

### 10. How do you merge a branch into the current branch?

To merge a branch into the current branch, use:

```sh
git merge <branch_name>
```

For example, if you are on the `main` branch and want to merge `feature-xyz`:

```sh
git merge feature-xyz
```
#### **[⬆ Back to Top](#level--easy)**
---

### 11. What is the difference between `git pull` and `git fetch`?

- `git pull` fetches changes from a remote repository and merges them into your current branch.
- `git fetch` only downloads changes from a remote repository but does not merge them into your current branch.

Example:

```sh
git fetch origin
git merge origin/main
```

is equivalent to:

```sh
git pull origin main
```
#### **[⬆ Back to Top](#level--easy)**
---

### 12. How do you delete a branch locally?

To delete a branch locally, use:

```sh
git branch -d <branch_name>
```

For example:

```sh
git branch -d feature-xyz
```
#### **[⬆ Back to Top](#level--easy)**
---

### 13. How do you delete a branch remotely?

To delete a branch remotely, use:

```sh
git push origin --delete <branch_name>
```

For example:

```sh
git push origin --delete feature-xyz
```
#### **[⬆ Back to Top](#level--easy)**
---

### 14. How do you undo the last commit?

To undo the last commit, use:

```sh
git revert HEAD
```

Or, if you want to remove the commit and the changes:

```sh
git reset --hard HEAD~1
```
#### **[⬆ Back to Top](#level--easy)**
---

### 15. How do you discard changes in a file?

To discard changes in a file, use:

```sh
git checkout -- <file_name>
```

For example:

```sh
git checkout -- README.md
```
#### **[⬆ Back to Top](#level--easy)**
---

### 16. How do you list all branches in a repository?

To list all branches, use:

```sh
git branch
```
#### **[⬆ Back to Top](#level--easy)**
---

### 17. How do you create a new tag?

To create a new tag, use:

```sh
git tag <tag_name>
```

For example:

```sh
git tag v1.0
```
#### **[⬆ Back to Top](#level--easy)**
---

### 18. How do you push changes to a remote repository?

To push changes, use:

```sh
git push <remote> <branch>
```

For example:

```sh
git push origin main
```
#### **[⬆ Back to Top](#level--easy)**
---

### 19. How do you pull changes from a remote repository?

To pull changes, use:

```sh
git pull <remote> <branch>
```

For example:

```sh
git pull origin main
```
#### **[⬆ Back to Top](#level--easy)**
---

### 20. How do you set your Git username and email?

To set your Git username and email, use:

```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
#### **[⬆ Back to Top](#level--easy)**
---

### 21. What is a commit message and why is it important?

A commit message is a brief description of the changes made in a commit. It is important because it provides context and reasoning for the changes, making it easier for others (and yourself) to understand the history and purpose of changes in the project.

#### **[⬆ Back to Top](#level--easy)**
---

### 22. How do you view the changes made to a file?

To view changes made to a file, use:

```sh
git diff <file_name>
```

For example:

```sh
git diff README.md
```
#### **[⬆ Back to Top](#level--easy)**
---

### 23. How do you rename a branch?

To rename a branch, use:

```sh
git branch -m <old_name> <new_name>
```

For example:

```sh
git branch -m old-branch-name new-branch-name
```
#### **[⬆ Back to Top](#level--easy)**
---

### 24. How do you move or rename a file?

To move or rename a file, use:

```sh
git mv <old_path> <new_path>
```

For example:

```sh
git mv old_file.txt new_file.txt
```
#### **[⬆ Back to Top](#level--easy)**
---

### 25. What is the difference between `git reset` and `git revert`?

- `git reset` moves the current branch pointer to a specified commit and can also modify the staging area and working directory.
- `git revert` creates a new commit that undoes the changes of a specified commit, preserving the commit history.

Example of `git reset`:

```sh
git reset --hard HEAD~1
```

Example of `git revert`:

```sh
git revert HEAD
```
#### **[⬆ Back to Top](#level--easy)**
---

### Summary Table

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone <repository_url>` | Clone an existing repository |
| `git status` | Check the status of the working directory |
| `git add <file_name>` | Stage a file for commit |
| `git commit -m "message"` | Commit changes to the repository |
| `git log` | View the commit history |
| `git branch <branch_name>` | Create a new branch |
| `git checkout <branch_name>` | Switch to an existing branch |
| `git merge <branch_name>` | Merge a branch into the current branch |
| `git pull` | Fetch and merge changes from a remote repository |
| `git fetch` | Fetch changes from a remote repository |
| `git branch -d <branch_name>` | Delete a branch locally |
| `git push origin --delete <branch_name>` | Delete a branch remotely |
| `git revert HEAD` | Undo the last commit |
| `git checkout -- <file_name>` | Discard changes in a file |
| `git branch` | List all branches |
| `git tag <tag_name>` | Create a new tag |
| `git push <remote> <branch>` | Push changes to a remote repository |
| `git pull <remote> <branch>` | Pull changes from a remote repository |
| `git config --global user.name "name"` | Set Git username |
| `git config --global user.email "email"` | Set Git email |
| `git diff <file_name>` | View changes made to a file |
| `git branch -m <old_name> <new_name>` | Rename a branch |
| `git mv <old_path> <new_path>` | Move or rename a file |
| `git reset` | Move the current branch pointer |
| `git revert` | Create a new commit that undoes changes |

This comprehensive guide should provide you with a solid understanding of Git commands and their usage.

#### **[⬆ Back to Top](#level--easy)**
---

# Medium Git Interview Questions and Answers
### 1. What is a Git repository?

A Git repository is a storage space where your project files and their history of changes are stored. It includes all the project’s files and the entire history of changes made to those files, which allows you to track versions, revert to previous states, and collaborate with others.

#### **[⬆ Back to Top](#level--medium)**
---

### 2. Explain the difference between a local and remote repository.

- **Local Repository**: A repository stored on your local machine. You interact with this repository using Git commands.
- **Remote Repository**: A repository hosted on a remote server. It is often used for collaboration where multiple users push and pull changes.

For example, you clone a remote repository to create a local copy on your machine.

#### **[⬆ Back to Top](#level--medium)**
---

### 3. What is a commit hash?

A commit hash is a unique identifier for a specific commit in the Git history. It's a 40-character SHA-1 hash that ensures each commit can be uniquely identified.

Example of a commit hash:

```
e1a1d3e8b8e3a1b5a1f3c1c8d8e8d8c8c8c8d8d8
```
#### **[⬆ Back to Top](#level--medium)**
---

### 4. How do you resolve merge conflicts?

To resolve merge conflicts:
1. Identify the files with conflicts using `git status`.
2. Open the conflicting files and manually resolve conflicts.
3. Stage the resolved files using `git add <file_name>`.
4. Commit the resolved changes using `git commit`.

Example:

```sh
git add resolved_file.txt
git commit -m "Resolve merge conflict in resolved_file.txt"
```
#### **[⬆ Back to Top](#level--medium)**
---

### 5. Explain the difference between `git merge` and `git rebase`.

- **`git merge`**: Combines the changes from one branch into another, creating a merge commit.
  
  ```sh
  git merge feature-branch
  ```

- **`git rebase`**: Moves or combines a sequence of commits to a new base commit. It creates a linear history.

  ```sh
  git rebase main
  ```
#### **[⬆ Back to Top](#level--medium)**
---


### 6. How do you stash changes in Git?

To stash changes, use:

```sh
git stash
```

This command saves your local modifications away and reverts the working directory to match the HEAD commit.

#### **[⬆ Back to Top](#level--medium)**
---

### 7. How do you apply stashed changes?

To apply stashed changes, use:

```sh
git stash apply
```

Or to both apply and remove the stash:

```sh
git stash pop
```
#### **[⬆ Back to Top](#level--medium)**
---

### 8. What is the purpose of the `.gitignore` file?

The `.gitignore` file specifies which files and directories Git should ignore and not track. It helps prevent committing unnecessary files like temporary files, build artifacts, and sensitive information.

Example `.gitignore`:

```
*.log
node_modules/
.env
```
#### **[⬆ Back to Top](#level--medium)**
---

### 9. How do you revert a commit that has already been pushed to the remote repository?

To revert a pushed commit, use:

```sh
git revert <commit_hash>
```

This creates a new commit that undoes the changes of the specified commit.

#### **[⬆ Back to Top](#level--medium)**
---

### 10. How do you cherry-pick a commit?

To cherry-pick a commit, use:

```sh
git cherry-pick <commit_hash>
```

This command copies the changes from the specified commit and applies them to your current branch.

#### **[⬆ Back to Top](#level--medium)**
---

### 11. What is the difference between `git diff` and `git log`?

- **`git diff`**: Shows the changes between commits, branches, files, etc.

  ```sh
  git diff
  ```

- **`git log`**: Shows the commit history.

  ```sh
  git log
  ```

#### **[⬆ Back to Top](#level--medium)**
---

### 12. How do you create a new branch and push it to the remote repository in one command?

To create a new branch and push it to the remote repository:

```sh
git checkout -b <branch_name> && git push -u origin <branch_name>
```
#### **[⬆ Back to Top](#level--medium)**
---

### 13. What is `git bisect` and how is it used?

`git bisect` helps you find the commit that introduced a bug by performing a binary search through your commit history.

Example usage:

```sh
git bisect start
git bisect bad
git bisect good <commit_hash>
```

Mark each commit as good or bad until you find the problematic commit.

#### **[⬆ Back to Top](#level--medium)**
---

### 14. How do you squash commits?

To squash commits, use interactive rebase:

```sh
git rebase -i HEAD~n
```

Replace `pick` with `squash` (or `s`) for the commits you want to squash, then save and close the editor.

#### **[⬆ Back to Top](#level--medium)**
---

### 15. How do you create a bare repository?

To create a bare repository, use:

```sh
git init --bare <repository_name>.git
```

A bare repository is typically used as a central repository for collaboration.

#### **[⬆ Back to Top](#level--medium)**
---

### 16. What is a detached HEAD state?

A detached HEAD state occurs when your HEAD is pointing to a commit instead of a branch. This means you are not on any branch.

Example:

```sh
git checkout <commit_hash>
```
#### **[⬆ Back to Top](#level--medium)**
---

### 17. How do you configure a remote upstream branch?

To configure a remote upstream branch, use:

```sh
git branch --set-upstream-to=<remote>/<branch>
```

For example:

```sh
git branch --set-upstream-to=origin/main
```
#### **[⬆ Back to Top](#level--medium)**
---

### 18. How do you set up a Git hook?

Create a file in the `.git/hooks` directory with the appropriate hook name (e.g., `pre-commit`, `post-commit`). Write your script in this file.

Example `pre-commit` hook:

```sh
#!/bin/sh
echo "Running pre-commit hook"
```

Make the script executable:

```sh
chmod +x .git/hooks/pre-commit
```
#### **[⬆ Back to Top](#level--medium)**
---

### 19. How do you force push to a remote repository?

To force push, use:

```sh
git push --force
```
#### **[⬆ Back to Top](#level--medium)**
---

### 20. What are submodules in Git?

Submodules allow you to keep a Git repository as a subdirectory of another Git repository. This is useful for managing dependencies.

Adding a submodule:

```sh
git submodule add <repository_url> <path>
```
#### **[⬆ Back to Top](#level--medium)**
---

### 21. How do you clone a repository with submodules?

To clone a repository with submodules:

```sh
git clone --recurse-submodules <repository_url>
```
#### **[⬆ Back to Top](#level--medium)**
---

### 22. Explain the difference between `git reset --soft`, `--mixed`, and `--hard`.

- **`--soft`**: Moves HEAD to the specified commit, but leaves the staging area and working directory unchanged.

  ```sh
  git reset --soft HEAD~1
  ```

- **`--mixed`** (default): Moves HEAD to the specified commit and resets the staging area, but leaves the working directory unchanged.

  ```sh
  git reset --mixed HEAD~1
  ```

- **`--hard`**: Moves HEAD to the specified commit and resets both the staging area and working directory.

  ```sh
  git reset --hard HEAD~1
  ```

#### **[⬆ Back to Top](#level--medium)**
---

### 23. How do you find a specific commit in the history?

To find a specific commit, use:

```sh
git log --grep="<search_term>"
```
#### **[⬆ Back to Top](#level--medium)**
---

### 24. How do you change the last commit message?

To change the last commit message, use:

```sh
git commit --amend -m "New commit message"
```
#### **[⬆ Back to Top](#level--medium)**
---

### 25. What is the difference between an annotated and a lightweight tag?

- **Annotated Tag**: Stores extra metadata such as the tagger name, email, date, and a tagging message. It's stored as a full object in the Git database.

  ```sh
  git tag -a <tag_name> -m "Tag message"
  ```

- **Lightweight Tag**: A simple pointer to a specific commit. It does not store any extra metadata.

  ```sh
  git tag <tag_name>
  ```
#### **[⬆ Back to Top](#level--medium)**
---

### Summary Table

| Command | Description |
|---------|-------------|
| `git init` | Initialize a Git repository |
| `git clone <repository_url>` | Clone a repository |
| `git commit -m "message"` | Commit changes |
| `git status` | Check the status of the working directory |
| `git add <file_name>` | Stage changes |
| `git log` | View commit history |
| `git diff` | View changes |
| `git branch <branch_name>` | Create a new branch |
| `git checkout <branch_name>` | Switch branches |
| `git merge <branch_name>` | Merge branches |
| `git rebase <branch_name>` | Rebase branches |
| `git stash` | Stash changes |
| `git stash apply` | Apply stashed changes |
| `git revert <commit_hash>` | Revert a commit |
| `git cherry-pick <commit_hash>` | Cherry-pick a commit |
| `git bisect` | Perform binary search to find a commit |
| `git rebase -i HEAD~n` | Squash commits |
| `git init --bare` | Create a bare repository |
| `git branch --set-upstream-to=<remote>/<branch>` | Set upstream branch |
| `git push --force` | Force push to a remote repository |
| `git submodule add <repository_url>` | Add a submodule |
| `git clone --recurse-submodules <repository_url>` | Clone repository with submodules |
| `git reset --soft` | Reset with soft option |
| `git reset --mixed` | Reset with mixed option |
| `git reset --hard` | Reset with hard option |
| `git log --grep="<search_term>"` | Search commit history |
| `git commit --amend -m "New message"` | Amend last commit message |
| `git tag -a <tag_name> -m "message"` | Create an annotated tag |
| `git tag <tag_name>` | Create a lightweight tag |

This guide should provide a comprehensive understanding of advanced Git commands and concepts.

#### **[⬆ Back to Top](#level--medium)**
---

# Hard Git Interview Questions and Answers
### 1. What is Git rebasing and what are its advantages and disadvantages?

**Git Rebasing** is the process of moving or combining a sequence of commits to a new base commit. It allows you to maintain a linear project history.

#### Advantages:
- **Clean History**: Rebasing results in a cleaner, more linear commit history.
- **Easier Merging**: Reduces the complexity of the merge process by avoiding merge commits.

#### Disadvantages:
- **History Rewriting**: Can be dangerous if not used carefully, especially with shared branches, as it rewrites commit history.
- **Loss of Context**: Merge commits provide a context of when branches were combined, which is lost with rebasing.

**Example:**

```sh
git checkout feature-branch
git rebase main
```
#### **[⬆ Back to Top](#level--hard)**
---

### 2. How do you perform an interactive rebase?

Interactive rebase allows you to edit, reorder, squash, or drop commits.

**Example:**

```sh
git rebase -i HEAD~3
```

This command opens an editor where you can specify actions for the last three commits.

```sh
pick 1234567 Commit message 1
squash 89abcdef Commit message 2
pick fedcba9 Commit message 3
```
#### **[⬆ Back to Top](#level--hard)**
---

### 3. How do you handle a situation where you accidentally pushed sensitive information to a public repository?

1. **Remove the sensitive data from history**:

```sh
git filter-branch --force --index-filter \
  'git rm --cached --ignore-unmatch <file_path>' \
  --prune-empty --tag-name-filter cat -- --all
```

2. **Force-push the changes**:

```sh
git push origin --force --all
```

3. **Invalidate old references**:

```sh
git push origin --force --tags
```
#### **[⬆ Back to Top](#level--hard)**
---

4. **Inform collaborators**: Notify all collaborators to re-clone the repository.

### 4. How do you optimize a repository for performance?

- **Garbage Collection**: Run `git gc` to optimize the repository by compressing file history.
- **Pack Files**: Use `git repack` to create more efficient pack files.
- **Prune Unreachable Objects**: Remove unreachable objects with `git prune`.

**Example:**

```sh
git gc --aggressive --prune=now
```
#### **[⬆ Back to Top](#level--hard)**
---

### 5. Explain the internal structure of a Git repository.

A Git repository consists of several components:

- **Objects**: Blobs, Trees, Commits, and Tags.
- **Refs**: Branches and Tags.
- **Index**: The staging area.
- **HEAD**: A pointer to the current branch.

**Example:**

```sh
.git/
  ├── objects/
  ├── refs/
  ├── index
  └── HEAD
```
#### **[⬆ Back to Top](#level--hard)**
---

### 6. How do you handle large binary files in Git?

Use **Git LFS (Large File Storage)** to manage large binary files.

**Example:**

1. **Install Git LFS**:

```sh
git lfs install
```

2. **Track large files**:

```sh
git lfs track "*.bin"
```

3. **Add and commit**:

```sh
git add .gitattributes
git add largefile.bin
git commit -m "Add large file using LFS"
git push
```
#### **[⬆ Back to Top](#level--hard)**
---

### 7. What is the purpose of the `git fsck` command?

`git fsck` checks the integrity of the Git repository, identifying any corrupted objects.

**Example:**

```sh
git fsck
```
#### **[⬆ Back to Top](#level--hard)**
---

### 8. How do you clean up a repository with a large history?

Use `git filter-branch` to rewrite history and remove unwanted data.

**Example:**

```sh
git filter-branch --prune-empty --tree-filter 'rm -rf unnecessary_directory' -- --all
```
#### **[⬆ Back to Top](#level--hard)**
---

### 9. Explain the concept of Git object model (blobs, trees, commits, etc.).

- **Blobs**: Store file data.
- **Trees**: Represent directories and contain pointers to blobs and other trees.
- **Commits**: Hold metadata and pointers to tree objects and parent commits.
- **Tags**: Annotated tags provide metadata for a specific commit.

#### **[⬆ Back to Top](#level--hard)**
---

### 10. How do you recover from a corrupted repository?

1. **Check repository**:

```sh
git fsck
```

2. **Recover lost commits**:

```sh
git reflog
```

3. **Restore from backup**: If available, restore from a backup.

#### **[⬆ Back to Top](#level--hard)**
---

### 11. How do you set up a Git server?

**Example using SSH:**

1. **Initialize a bare repository**:

```sh
git init --bare /path/to/repo.git
```

2. **Set up SSH access**: Ensure SSH is configured on the server.

3. **Push to the remote repository**:

```sh
git remote add origin user@server:/path/to/repo.git
git push -u origin main
```
#### **[⬆ Back to Top](#level--hard)**
---

### 12. What is the difference between `git archive` and `git bundle`?

- **`git archive`**: Creates a tar or zip archive of the repository.

  ```sh
  git archive --format=tar HEAD | gzip > repository.tar.gz
  ```

- **`git bundle`**: Creates a single file containing the repository data.

  ```sh
  git bundle create repository.bundle main
  ```

#### **[⬆ Back to Top](#level--hard)**
---

### 13. How do you manage multiple repositories in a single project?

Use **submodules** or **monorepos**:

**Submodules Example:**

```sh
git submodule add <repository_url> <path>
```
#### **[⬆ Back to Top](#level--hard)**
---

### 14. How do you track changes to a specific directory?

Use `git log` with the directory path:

```sh
git log -- <directory_path>
```
#### **[⬆ Back to Top](#level--hard)**
---

### 15. What is the purpose of the `reflog`?

`reflog` records changes to the tips of branches and other references, allowing you to recover lost commits.

**Example:**

```sh
git reflog
```
#### **[⬆ Back to Top](#level--hard)**
---

### 16. How do you bisect a repository with many branches?

1. **Start bisect**:

```sh
git bisect start
```

2. **Mark the bad commit**:

```sh
git bisect bad
```

3. **Mark a good commit**:

```sh
git bisect good <commit_hash>
```
#### **[⬆ Back to Top](#level--hard)**
---

4. **Continue until the problematic commit is found**.

### 17. How do you configure Git to use a different merge tool?

Set the merge tool in your Git configuration:

```sh
git config --global merge.tool <tool_name>
git config --global mergetool.<tool_name>.path <path_to_tool>
```
#### **[⬆ Back to Top](#level--hard)**
---

### 18. How do you use `git filter-branch` to rewrite history?

Rewriting history to remove a file:

```sh
git filter-branch --index-filter 'git rm --cached --ignore-unmatch <file_path>' -- --all
```
#### **[⬆ Back to Top](#level--hard)**
---

### 19. What are the risks of force-pushing to a shared repository?

- **Overwriting Changes**: You might overwrite others' changes.
- **History Rewriting**: Force-push rewrites history, which can lead to inconsistencies.

#### **[⬆ Back to Top](#level--hard)**
---

### 20. How do you manage Git credentials securely?

- **Use SSH keys** for authentication.
- **Use credential helpers** to securely store credentials.

**Example:**

```sh
git config --global credential.helper cache
```
#### **[⬆ Back to Top](#level--hard)**
---

### 21. Explain what a Git worktree is and how to use it.

A **Git worktree** allows you to have multiple working directories attached to a single repository.

**Example:**

```sh
git worktree add <path> <branch>
```
#### **[⬆ Back to Top](#level--hard)**
---

### 22. How do you enforce commit message guidelines?

Use a **commit-msg hook**:

1. **Create the hook**:

```sh
echo -e '#!/bin/sh\nexec <script_path>' > .git/hooks/commit-msg
chmod +x .git/hooks/commit-msg
```

2. **Write the script** to enforce guidelines.

#### **[⬆ Back to Top](#level--hard)**
---

### 23. How do you use `git blame` to find the author of a specific line of code?

Use `git blame` with the file path:

```sh
git blame <file_path>
```
#### **[⬆ Back to Top](#level--hard)**
---

### 24. What is the difference between shallow cloning and a full clone?

- **Shallow Cloning**: Clones the repository with limited history, reducing download size.

  ```sh
  git clone --depth=1 <repository_url>
  ```

- **Full Clone**: Clones the entire repository history.

#### **[⬆ Back to Top](#level--hard)**
---

### 25. How do you handle a situation where a merge introduces a bug that needs to be fixed without reverting the merge?

1. **Identify the bug** and create a new branch:

```sh
git checkout -b fix-branch
```

2. **Make necessary changes and commit**:

```sh
git commit -m "Fix bug introduced in merge"
```

3. **Merge the fix branch back**:

```sh
git checkout main
git merge fix-branch
```
#### **[⬆ Back to Top](#level--hard)**
---

### Summary Table

| Command | Description |
|---------|-------------|
| `git rebase -i` | Perform an interactive rebase |
| `git filter-branch` | Rewrite history |
| `git fsck` | Check repository integrity |
| `git gc` | Optimize repository |
| `git lfs` | Manage large files |
| `git reflog` | Record changes to refs |
| `git bisect` | Find a commit introducing a bug |
| `git worktree` | Manage multiple worktrees |
| `git blame` | Find the author of a line |
| `git clone --depth=1` | Shallow clone repository |

This guide provides an in-depth understanding of advanced Git concepts and commands with examples.

#### **[⬆ Back to Top](#level--hard)**
---