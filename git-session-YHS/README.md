# Git Commands Guide

This guide provides an overview of essential Git commands for version control.

## Initializing and Cloning Repositories

- `git init`: Initialize a new Git repository in your project directory.
- `git clone <repo-url>`: Clone an existing repository using its URL.

## Checking Status

- `git status`: Display current status of your working directory and staging area.

## Staging Changes

- `git add .`: Stage all modified files in your project for committing.

## Committing Changes

- `git commit -m "Meaningful message"`: Commit staged changes with a descriptive message.
- `git commit --amend`: Modify the most recent commit by adding new changes or editing its message.

## Pulling and Pushing Changes

- `git pull origin main`: Fetch and merge changes from the remote main branch to the local repository.
- `git pull`: Fetch and merge changes from the remote repository into the current branch.
- `git push --force`: Force an update to a remote repository, potentially overwriting commits on that branch's history on remote server (use with caution).

## Branching

- `git checkout -b feature/branch-name`: Create and switch to a new branch named feature/branch-name.
- `git checkout main`: Switch to the main branch.

## Merging and Stashing

- `git merge feature/branch-name`: Merge changes from feature/branch-name into the current branch.
- `git stash`: Temporarily save changes that are not ready to be committed.

## Reverting and Cherry-Picking

- `git revert <commit-hash>`: Create a new commit that undoes all of the changes made in a specified commit.
- `git cherry-pick <commit-hash>`: Apply specific commits identified by their hash values from one branch into another.
