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
# Bundle2 #exercise 2
```
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 2 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
PS C:\Users\UserNA1842\the-gym-git-exercises> git pull origin main
From https://github.com/NoellaPromise/git-exercises-solutions
 * branch            main       -> FETCH_HEAD
Updating d94947e..682442c
Fast-forward
 README.md | 255 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 1 file changed, 253 insertions(+), 2 deletions(-)
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the service page"
[ft/service-redesign fa89497] Add changes to the service page
 1 file changed, 19 insertions(+)
 create mode 100644 services.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 568 bytes | 568.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/service-redesign
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/service-redesign -> ft/service-redesign
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the services page"
[main a5c933a] Add changes to the services page
 1 file changed, 19 insertions(+)
 create mode 100644 services.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 573 bytes | 573.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NoellaPromise/git-exercises-solutions
   682442c..a5c933a  main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
PS C:\Users\UserNA1842\the-gym-git-exercises> git diff ft/service-redesign..main
diff --git a/services.html b/services.html
index 00e3939..c2d1d4d 100644
--- a/services.html
+++ b/services.html
@@ -10,7 +10,7 @@
     <p>This page contains The services we provide to our clients</p>
     <h2> Here are some of our services </h2>
     <ul>
-        <li>Coaching</li>
+        <li>Coaching and Teaching</li>

         <li>Training</li>
     </ul>
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git merge ft/service-redesign
Auto-merging services.html
CONFLICT (add/add): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Merge main with ft/service-redesign branch"
[main 2b449a6] Merge main with ft/service-redesign branch
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 621 bytes | 621.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NoellaPromise/git-exercises-solutions
   a5c933a..2b449a6  main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises>


```
# Bundle 4
## Exercise 1
```
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git remote add origin https://github.com/NoellaPromise/git-copy1
error: remote origin already exists.
PS C:\Users\UserNA1842\the-gym-git-exercises> git remote add https://github.com/NoellaPromise/git-copy1
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from

PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises>  git remote
origin
PS C:\Users\UserNA1842\the-gym-git-exercises> git remote add git-copy https://github.com/NoellaPromise/git-exercises-clone.git
PS C:\Users\UserNA1842\the-gym-git-exercises> git remote
git-copy
origin
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .\home.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the home page"
[main d183e80] Add changes to the home page
 1 file changed, 2 insertions(+)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 406 bytes | 406.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/NoellaPromise/git-exercises-solutions
   bdd6121..d183e80  main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises> git push git-copy
Enumerating objects: 41, done.
Counting objects: 100% (41/41), done.
Delta compression using up to 8 threads
Compressing objects: 100% (35/35), done.
Writing objects: 100% (41/41), 8.94 KiB | 1.49 MiB/s, done.
Total 41 (delta 15), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (15/15), done.
To https://github.com/NoellaPromise/git-exercises-clone.git
 * [new branch]      main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises>

```
# Bundle 4
## Exercise 2
```
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/footer
Switched to a new branch 'ft/footer'
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add Footer"
[ft/footer e5d05ab] Add Footer
 1 file changed, 11 insertions(+)
 create mode 100644 ft/footer.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/footer
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 503 bytes | 503.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/footer
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/footer -> ft/footer
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the footer"
[ft/footer 2e0fc26] Add changes to the footer
 1 file changed, 1 insertion(+)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/footer
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 398 bytes | 398.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/NoellaPromise/git-exercises-solutions
   e5d05ab..2e0fc26  ft/footer -> ft/footer
PS C:\Users\UserNA1842\the-gym-git-exercises> git pull origin main
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 621 bytes | 31.00 KiB/s, done.
From https://github.com/NoellaPromise/git-exercises-solutions
 * branch            main       -> FETCH_HEAD
   9933859..5be4a6d  main       -> origin/main
Updating 2e0fc26..5be4a6d
Fast-forward
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is behind 'origin/main' by 3 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'
PS C:\Users\UserNA1842\the-gym-git-exercises> git merge --squash ft/footer
Updating 9933859..5be4a6d
Fast-forward
Squash commit -- not updating HEAD
 ft/footer.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 ft/footer.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git log
commit 99338595eda043310174937283bcba04f8bf3fbf (HEAD -> ft/squashing, git-copy/main, main)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Thu Aug 3 11:27:04 2023 +0200

    Add README file

commit d183e804eed37642130455f708061993a10468e0
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Thu Aug 3 11:25:02 2023 +0200

    Add changes to the home page

commit bdd612100cb706ac3f3c3d9b4dc84961621b1310
Merge: 11e0751 749c47f
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 20:30:06 2023 +0200

    Merge branch 'main' of https://github.com/NoellaPromise/git-exercises-solutions

commit 11e0751508e870572b7657daa15b2006049c7d97
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 20:29:10 2023 +0200
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit - "footer changes squashing"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'footer changes squashing' did not match any file(s) known to git
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "footer changes squashing"
[ft/squashing 36cdf68] footer changes squashing
 1 file changed, 12 insertions(+)
 create mode 100644 ft/footer.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/squashing
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 531 bytes | 531.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/squashing
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/squashing -> ft/squashing
PS C:\Users\UserNA1842\the-gym-git-exercises>

```