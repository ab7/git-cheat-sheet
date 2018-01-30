# Git Cheat Sheet

## Configuration

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
git config --global core.editor vim
git config --list
```

[https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

## Creating a local repository

```
git init .           # initialize an empty repository
git clone <address>  # download a repo from a remote repository
git status           # check the current status of repo
```

[https://git-scm.com/docs/git-init](https://git-scm.com/docs/git-init)

## Commits

```
git diff                            # view changes against previous commit
git add .                           # stage files to be included in commit
git add <file>|<dir>                # stage specific file/dir
git commit                          # using editor saved from config
git commit -m “This is an message”  # skip the editor
git commit --amend                  # update most recent commit
```

[https://git-scm.com/docs/git-commit](https://git-scm.com/docs/git-commit)
