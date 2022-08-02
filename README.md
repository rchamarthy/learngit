# learngit - covers absolute basics for everyone

This git repository will cover git basic commands and workflows.

## Initializing a Local git Repository

To initialize a local git repository, run the command `git init`.

``` bash
13:58:36 ❯ mkdir sample
13:58:39 ❯ git init .
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /tmp/sample/.git/
praveen on atom-lab-6 in sample on  master
drwxrwxr-x  3 praveen praveen 4.0K Aug  2 13:58 .
drwxrwxrwt 16 root    root    372K Aug  2 13:58 ..
drwxrwxr-x  7 praveen praveen 4.0K Aug  2 13:58 .git
```

## Create a Local branch

To create a local branch, run the command `git checkout -b <branch-name>`

```bash
ravi in ins15-pp24-ru11 in learngit on  main
❯ git checkout -b add-branch-command
Switched to a new branch 'add-branch-command'
```
