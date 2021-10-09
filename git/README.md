---
title: Git
author: education.github.com
firstColor: "#23292F"
secondColor: "#FFFFFF"
thirdColor: "hsl(124, 100%, 95%)"
---

# Git

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer. This cheat sheet features the most important and commonly used Git commands for easy reference.

+++

## Setup

**Configuring user information used across all local repositories**

`git config --global user.name “[firstname lastname]”`
set a name that is identifiable for credit when review version history

`git config --global user.email “[valid-email]”`
set an email address that will be associated with each history marker

`git config --global color.ui auto `
set automatic command line coloring for Git for easy reviewing

## Setup & Init

**Configuring user information, initializing and cloning repositories**

`git init`
initialize an existing directory as a Git repository

`git clone [url]`
retrieve an entire repository from a hosted location via URL

## Stage & Snapshot

**Working with snapshots and the Git staging area**

`git status`
show modified files in working directory, staged for your next commit

`git add [file]`
add a file as it looks now to your next commit (stage)

`git reset [file]`
unstage a file while retaining the changes in working directory

`git diff`
diff of what is changed but not staged

`git diff --staged`
diff of what is staged but not yet committed

`git commit -m “[descriptive message]”`
commit your staged content as a new commit snapshot
