# Prerequsite before commit

* First git expects to give some basic information about the commit person

* This can be done with help of below commands

  `git config --global user.name "vijay"`
  `git config --global user.email "mail.id"`

* Then create your project folder

* CD to create folder

* Run command `git init`

* Create some empty files

## commit 1

| Task                  | Command                         | Notes                                             |
| --------------------- | --------------------------------|---------------------------------------------------|
| Check untracked files | `git status`                    | To check untracked files in repo                  |
| Stage files           | `git add basic.sh`              | use `git status` again to check if file is staged |
| Commit files          | `git commit –m "First commit"`  | commit message can be user defined                |

## commit 2

* Let's try to modify the file again and do second commit

| Task                  | Command                         | Notes                                             |
| --------------------- | --------------------------------|---------------------------------------------------|
| Modify the source     |                                 |                                                   |
| Check untracked files | `git status`                    | To check untracked files in repo                  |
| Stage files           | `git add basic.sh`              | use `git status` again to check if file is staged |
| Commit files          | `git commit –m "Second commit"` | commit message can be user defined                |

### Key commands

| Task                  | Command                                     | Notes                                             |
| --------------------- | --------------------------------------------|---------------------------------------------------|
| Check commit logs     | `git log`                                   | view history of commits                           |
| Check commit logs     | `git log --oneline`                         | view commit logs in oneline                       |
| Stage and commit      | `git commit -a -m "message"`                | Stage and commit togather multiple files          |
| Remove                | `git rm <filename>`                         | Delete file from git repo and as well as local    |
| Remove                | `git rm --cached <filename>`                | Delete file only from git repo                    |
| Force Remove          | `git rm -f <filename>`                      | Force remove staged file                          |
| Amend                 | `git commit --amend`                        | Change last commit message using amend            |
| Commit Tags           | `git tag -a <tagname> -m "message"`         | Add tagname to your commit                        |
| To view tag           | `git tag`                                   | View all the tags created                         |
| Tag existing commit   | `git tag -a <tag> <commit-id> -m "message"` | Adding tag to existing commit                     |