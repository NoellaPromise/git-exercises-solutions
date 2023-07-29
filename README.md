# the-gym-git-exercises-solutions
# Bundle 1 #Exercise1 #exercise2
```bash
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Users\UserNA1842\the-gym-git-exercises> git init
Initialized empty Git repository in C:/Users/UserNA1842/the-gym-git-exercises/.git/
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch -M main
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .\README.md
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add README file"
[main (root-commit) b87e26a] Add README file
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
PS C:\Users\UserNA1842\the-gym-git-exercises> git remote add origin https://github.com/NoellaPromise/git-exercises-solutions
PS C:\Users\UserNA1842\the-gym-git-exercises> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
To https://github.com/NoellaPromise/git-exercises-solutions
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/NoellaPromise/git-exercises-solutions'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git git add .
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Change README file"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
To https://github.com/NoellaPromise/git-exercises-solutions
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/NoellaPromise/git-exercises-solutions'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\UserNA1842\the-gym-git-exercises> git pull origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 612 bytes | 30.00 KiB/s, done.
From https://github.com/NoellaPromise/git-exercises-solutions
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
To https://github.com/NoellaPromise/git-exercises-solutions
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/NoellaPromise/git-exercises-solutions'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\UserNA1842\the-gym-git-exercises> git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "change README file"
[main f0e794a] change README file
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
To https://github.com/NoellaPromise/git-exercises-solutions
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/NoellaPromise/git-exercises-solutions'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\UserNA1842\the-gym-git-exercises> git pull origin main
From https://github.com/NoellaPromise/git-exercises-solutions
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
To https://github.com/NoellaPromise/git-exercises-solutions
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/NoellaPromise/git-exercises-solutions'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b dev
Switched to a new branch 'dev'
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch -d main
Deleted branch main (was f0e794a).
PS C:\Users\UserNA1842\the-gym-git-exercises> git fetch
PS C:\Users\UserNA1842\the-gym-git-exercises> git fetch origin
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b main origin/main
Switched to a new branch 'main'
branch 'main' set up to track 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the REDME"
[main d94947e] Add changes to the REDME
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NoellaPromise/git-exercises-solutions
   d79e639..d94947e  main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch -d dev
error: The branch 'dev' is not fully merged.
If you are sure you want to delete it, run 'git branch -D dev'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch -D dev
Deleted branch dev (was f0e794a).
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch dev
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout dev
Switched to branch 'dev'
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b test
Switched to a new branch 'test'
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout dev
Switched to branch 'dev'
PS C:\Users\UserNA1842\the-gym-git-exercises> git branch -d test
Deleted branch test (was d94947e).
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .\home.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash list
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash
Saved working directory and index state WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash list
stash@{0}: WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash
No local changes to save
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .\about.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash
Saved working directory and index state WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash list
stash@{0}: WIP on dev: d94947e Add changes to the REDME
stash@{1}: WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .\team.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash
Saved working directory and index state WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash list
stash@{0}: WIP on dev: d94947e Add changes to the REDME
stash@{1}: WIP on dev: d94947e Add changes to the REDME
stash@{2}: WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop --stash@{1}
error: unknown option `stash@'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop stash@{1}
error: unknown switch `e'
usage: git stash pop [--index] [-q | --quiet] [<stash>]

    -q, --quiet           be quiet, only report errors
    --index               attempt to recreate the index

PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop 1
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped refs/stash@{1} (23e27f3e17dc464217456b9f3f52ce0def0aef10)
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop 1
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Dropped refs/stash@{1} (cebd41ed3f1abfc2818e52f936f9fd4139d42617)
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Stash poped About and home files"
[dev e084587] Stash poped About and home files
 3 files changed, 26 insertions(+), 1 deletion(-)
 create mode 100644 about.html
 create mode 100644 home.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin dev
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 639 bytes | 639.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/dev
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      dev -> dev
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash list
stash@{0}: WIP on dev: d94947e Add changes to the REDME
PS C:\Users\UserNA1842\the-gym-git-exercises> git stash pop 0
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (53d9301f9a67bc8b492d96e4446f47d5ff8c20d5)
PS C:\Users\UserNA1842\the-gym-git-exercises> git reset --hard
HEAD is now at e084587 Stash poped About and home files
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Modify README file"
[dev fa3044d] Modify README file
 1 file changed, 240 insertions(+), 1 deletion(-)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.44 KiB | 2.44 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NoellaPromise/git-exercises-solutions
   e084587..fa3044d  dev -> dev
PS C:\Users\UserNA1842\the-gym-git-exercises>
```
