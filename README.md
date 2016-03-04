# Git Reviewer

`git-reviewer` is a git extension that helps you figure out a reasonable code reviewer for changes based on most who most recently also touched the files that have been changed.

## Install

Add `git-reviewer` anywhere onto your `$PATH`.

## Usage

`usage: git reviewer [ref]`

`git-reviewer` by default looks for uncommited changes in your working copy and uses those changes to determine reviewers. If there are no uncommited changes, it will use the last commit.

`git-reviewer` can also take an arbitrary git ref to use as the base of comparison for determining reviewers.
