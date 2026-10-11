# PROOF OF WORK

## 1. Git Commit History

The following command displays the commit history of the repository:

```bash
git log --oneline
```

**Actual output:**

- 10d85e2 (HEAD -> main, origin/main) Merge pull request #1 from HaroonAbbas12/development
- 320191d (origin/development, development) fix: resolve deployment script conflict
- 9b11e9d (origin/staging, staging) fix: update staging environment label
- c3c778e feat: update deployment environment
- e8b2bc2 feat: add initial project files


## 2. Reflection Questions

### Q1. What is the difference between Git and GitHub?

Git is a version control tool that runs locally and records changes to files over time. It allows developers to maintain different branches, create commits, and manage project history. GitHub is a cloud-based service that hosts Git repositories and enables developers to share code, review changes, and collaborate through Pull Requests.

### Q2. Describe the Working Directory, Staging Area, and Local Repository.

The Working Directory is where project files are created and modified. The Staging Area contains the changes selected for inclusion in the next commit using `git add`. The Local Repository stores the committed versions of the project. Together, these stages provide a structured process for preparing and recording changes.

### Q3. How do `git stash pop` and `git stash apply` differ?

Both commands restore changes that were previously stored with Git stash. The `git stash pop` command normally removes the restored entry from the stash list after applying it successfully, whereas `git stash apply` keeps the entry available for future use. Therefore, apply is useful when the saved changes may need to be restored again.

### Q4. What is the difference between `git fetch` and `git pull`?

The `git fetch` command retrieves information about changes available in the remote repository without integrating those changes into the current branch. The `git pull` command retrieves remote changes and integrates them into the current branch, usually through a merge or rebase. Fetch is useful for inspecting remote updates before deciding how to integrate them.
