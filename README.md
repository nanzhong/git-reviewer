# Git Reviewer

`git-reviewer` is a get extension that helps you figure out a reasonable code reviewer for changes based on most who most recently also touched the files that have been changed.

## Install

Add `git-reviewer` anywhere onto your `$PATH`.

## Usage

`usage: git reviewer [ref]`

`git-reviewer` by default looks for uncommited changes in your working copy and uses those changes to determine reviewers. If there are no uncommited changes, it will use the last commit.

`git-reviewer` can also take an arbitrary git ref to use as the base of comparison for determining reviewers.

## License

```
The MIT License (MIT)

Copyright (c) 2016 Nan Zhong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
