# Git Commands Cheat Sheet

This cheat sheet is designed to help you understand and use Git more effectively.

## Getting Started

### 1. Configure Git

First, configure the global username and email address, which will be used in your commits.

```shell
git config --global user.name "Your Name"
git config --global user.email "your-email@domain.com"
```
---
## Basic Commands
### 2. Initialize a Repository

To create a new local repository.

```shell

git init
```


### 3. Clone a Repository

To clone (download) a remote repository.

```shell

git clone [url]
```


### 4. Git Status

Check the current status of your repository.

```shell

git status
```


### 5. Add Files

To add a file to the staging area.

```shell

git add [file-name]
```



To add all files to the staging area.

```shell

git add -A
```


### 6. Commit Changes

To commit your changes.

```shell

git commit -m "[commit message]"
```

---
## Branching and Merging
### 7. Create a Branch

```shell

git branch [branch-name]
```


### 8. Switch to a Branch

```shell

git checkout [branch-name]
```


### 9. Create a New Branch and Switch to It

```shell

git checkout -b [branch-name]
```


### 10. Merge a Branch

Merge another branch into your active branch (usually `master`).

```shell

git merge [branch-name]
```


### 11. Delete a Branch

```shell

git branch -d [branch-name]
```

---
## Update and Publish
### 12. Fetch and Merge Changes from the Remote

```shell

git pull
```


### 13. Push Changes

Push your changes to the remote repository.

```shell

git push origin [branch-name]
```
---

## Inspection and Comparison
### 14. View Commit History

```shell

git log
```


### 15. View Specific Commit

```shell

git show [commit]
```


## Stashing
### 16. Stash Changes

```shell

git stash
```


### 17. Apply Stashed Changes

```shell

git stash pop
```
---
## Undoing Changes
### 18. Revert Commit

```shell

git revert [commit-id]
```


### 19. Reset Changes

Discard all changes in the working directory.

```shell

git reset --hard HEAD
```


## Dealing with Merge Conflicts
### 20. View Merge Conflicts

```shell

git diff
```
---

## Advanced Topics

For more detail, check out the [Pro Git book](https://git-scm.com/book/en/v2)  online, or your favorite online Git tutorial or reference.
