---
title: Git
author: education.github.com
firstColor: "gray"
---

# Git

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer. This cheat sheet features the most important and commonly used Git commands for easy reference.

+++

## Setup

**Configuring user information used across all local repositories**

```bash
git config --global user.name “[firstname lastname]”
```

set a name that is identifiable for credit when review version history

```bash
git config --global user.email “[valid-email]”
```

set an email address that will be associated with each history marker

```bash
git config --global color.ui auto
```

set automatic command line coloring for Git for easy reviewing

+++

## Setup & Init

**Configuring user information, initializing and cloning repositories**

```bash
git init
```

initialize an existing directory as a Git repository

```bash
git clone [url]
```

retrieve an entire repository from a hosted location via URL

+++

## Stage & Snapshot

**Working with snapshots and the Git staging area**

```bash
git status
```

show modified files in working directory, staged for your next commit

```bash
git add [file]
```

add a file as it looks now to your next commit (stage)

```bash
git reset [file
```

unstage a file while retaining the changes in working directory

```bash
git diff
```

diff of what is changed but not staged

```bash
git diff --staged
```

diff of what is staged but not yet committed

```bash
git commit -m “[descriptive message]”
```

commit your staged content as a new commit snapshot
