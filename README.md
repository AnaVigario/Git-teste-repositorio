# Git Commands README

## Introduction

Welcome to the Git Commands repository! This README provides an overview of essential Git commands to help you get started with version control and collaborative development.

## Table of Contents

1. [Git Basics](#git-basics)
2. [Repository Setup](#repository-setup)
3. [Branching](#branching)
4. [Committing Changes](#committing-changes)
5. [Updating Changes](#updating-changes)
6. [Merging](#merging)
7. [Remote Repositories](#remote-repositories)
8. [Undoing Changes](#undoing-changes)
9. [Git Extras](#git-extras)
10. [Resources](#resources)

## Git Basics

### Initialize a Repository

```bash
git init
```

### Clone a Repository

```bash
git clone <repository-url>
```

## Repository Setup

### Add Changes to Staging

```bash
git add <file1> <file2> ...
```

### Commit Staged Changes

```bash
git commit -m "Commit message"
```

## Branching

### Create a New Branch

```bash
git branch <branch-name>
```

### Switch to a Branch

```bash
git checkout <branch-name>
```

### Create and Switch to a Branch

```bash
git checkout -b <branch-name>
```

## Committing Changes

### View Changes

```bash
git status
```

### View Changes in Diff Format

```bash
git diff
```

## Updating Changes

### Fetch Latest Changes

```bash
git fetch
```

### Pull Latest Changes

```bash
git pull
```

### Push Changes to Remote

```bash
git push
```

## Merging

### Merge Branch into Current Branch

```bash
git merge <branch-name>
```

## Remote Repositories

### Add a Remote Repository

```bash
git remote add <remote-name> <remote-url>
```

### Fetch Changes from a Remote Repository

```bash
git fetch <remote-name>
```

### Pull Changes from a Remote Repository

```bash
git pull <remote-name> <branch-name>
```

## Undoing Changes

### Discard Changes in Working Directory

```bash
git checkout -- <file>
```

### Discard Changes in Staging Area

```bash
git reset <file>
```

### Undo the Last Commit

```bash
git reset --soft HEAD^
```

## Git Extras

### View Commit History

```bash
git log
```

### View a Specific Commit

```bash
git show <commit-hash>
```

### View Remote Branches

```bash
git remote show <remote-name>
```

## Resources

- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Git Cheat Sheet](https://education.github.com/git-cheat-sheet)
