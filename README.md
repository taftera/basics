# How to control GitHub

Basically you gotta check whats left to upload by this commands:

> not sure if this works
## Create projects
- **git init**
  - create "README.md"
- **git remote add** *REMOTE-NAME* *URL*
- **git push --set-upstream** *REMOTE-NAME* **master**
> not sure if this works

## Upload updates

- **git status**
  - check if something is "modified".
- **git add** *FILENAME.ext*
- **git commit** -m "*comment about the upload*"
- **git push**
  - to upload content with credentials.

## Untracked
- **git add** *<file>*
  - to include file for being tracked.

## Untrack a file
- **git checkout --** *<file>*
  - to exclude a file from being tracked.

Review the GitHub syntax format [link](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)
