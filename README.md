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
