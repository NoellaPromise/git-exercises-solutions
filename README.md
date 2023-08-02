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
# Bundle 3
## Exercise 1
```
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add team page"
[ft/team-page 8c4f694] Add team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 506 bytes | 506.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/team-page
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/team-page -> ft/team-page
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
Switched to branch 'ft/team-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git log
commit 8c4f694988e711407e1dd48904e94c6c5aa0ac81 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 10:45:47 2023 +0200

    Add team page

commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main, ft/contact-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file

commit 2b449a66bf0daf77d692c9d63bec2f444e61600b
Merge: a5c933a fa89497
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:26:43 2023 +0200

    Merge main with ft/service-redesign branch

commit a5c933a92b8b7b76581faaf60c25da0005cb6ec1
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 11:53:50 2023 +0200

    Add changes to the services page

commit 8c4f694988e711407e1dd48904e94c6c5aa0ac81 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 10:45:47 2023 +0200

    Add team page

commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main, ft/contact-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file

commit 2b449a66bf0daf77d692c9d63bec2f444e61600b
Merge: a5c933a fa89497
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:26:43 2023 +0200

    Merge main with ft/service-redesign branch

commit a5c933a92b8b7b76581faaf60c25da0005cb6ec1
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 11:53:50 2023 +0200

    Add changes to the services page

...skipping...

                   SUMMARY OF LESS COMMANDS

      Commands marked with * may be preceded by a number, N.
      Notes in parentheses indicate the behavior if N is given.
      A key preceded by a caret indicates the Ctrl key; thus ^K is ctrl-K.

  h  H                 Display this help.
  q  :q  Q  :Q  ZZ     Exit.
 ---------------------------------------------------------------------------

                           MOVING

  e  ^E  j  ^N  CR  *  Forward  one line   (or N lines).
  y  ^Y  k  ^K  ^P  *  Backward one line   (or N lines).
  f  ^F  ^V  SPACE  *  Forward  one window (or N lines).
  b  ^B  ESC-v      *  Backward one window (or N lines).
  z                 *  Forward  one window (and set window to N).
  w                 *  Backward one window (and set window to N).
  ESC-SPACE         *  Forward  one window, but don't stop at end-of-file.
  d  ^D             *  Forward  one half-window (and set half-window to N).
  u  ^U             *  Backward one half-window (and set half-window to N).
  ESC-)  RightArrow *  Right one half screen width (or N positions).
  ESC-(  LeftArrow  *  Left  one half screen width (or N positions).
  ESC-}  ^RightArrow   Right to last column displayed.
HELP -- Press RETURN for more, or q when done...skipping...
commit 8c4f694988e711407e1dd48904e94c6c5aa0ac81 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 10:45:47 2023 +0200

    Add team page

commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main, ft/contact-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file

commit 2b449a66bf0daf77d692c9d63bec2f444e61600b
Merge: a5c933a fa89497
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:26:43 2023 +0200

    Merge main with ft/service-redesign branch

commit a5c933a92b8b7b76581faaf60c25da0005cb6ec1
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 11:53:50 2023 +0200

    Add changes to the services page

PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
Switched to branch 'ft/team-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git cherry-pick 8c4f694988e711407e1dd48904e94c6c5aa0ac81
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'
On branch ft/team-page
You are currently cherry-picking commit 8c4f694.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

nothing to commit, working tree clean
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
warning: cancelling a cherry picking in progress
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the contact page"
[ft/contact-page 36d694e] Add changes to the contact page
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 515 bytes | 515.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/contact-page
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/contact-page -> ft/contact-page
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add faq page"
[ft/faq-page f0163c5] Add faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 469 bytes | 469.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/faq-page
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/faq-page -> ft/faq-page
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
CONFLICT (rename/delete): team.html renamed to contact.html in HEAD, but deleted in parent of 8c4f694 (Add team page).
CONFLICT (modify/delete): contact.html deleted in parent of 8c4f694 (Add team page) and modified in HEAD.  Version HEAD of contact.html left in tree.
error: could not revert 8c4f694... Add team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
error: you need to resolve your current index first
contact.html: needs merge
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
error: you need to resolve your current index first
contact.html: needs merge
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
error: you need to resolve your current index first
contact.html: needs merge
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
CONFLICT (rename/delete): team.html renamed to contact.html in HEAD, but deleted in parent of 8c4f694 (Add team page).
CONFLICT (modify/delete): contact.html deleted in parent of 8c4f694 (Add team page) and modified in HEAD.  Version HEAD of contact.html left in tree.
error: could not revert 8c4f694... Add team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
error: you need to resolve your current index first
contact.html: needs merge
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/team-page
Switched to branch 'ft/team-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git log
commit 8c4f694988e711407e1dd48904e94c6c5aa0ac81 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 10:45:47 2023 +0200

    Add team page

commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file

commit 2b449a66bf0daf77d692c9d63bec2f444e61600b
Merge: a5c933a fa89497
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:26:43 2023 +0200

    Merge main with ft/service-redesign branch

commit a5c933a92b8b7b76581faaf60c25da0005cb6ec1
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 11:53:50 2023 +0200

    Add changes to the services page

PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout faq.html
error: pathspec 'faq.html' did not match any file(s) known to git
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
CONFLICT (modify/delete): team.html deleted in parent of 8c4f694 (Add team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert 8c4f694... Add team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/contact-page
error: you need to resolve your current index first
team.html: needs merge
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
warning: cancelling a revert in progress
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 8c4f694988e711407e1dd48904e94c6c5aa0ac81
CONFLICT (modify/delete): team.html deleted in parent of 8c4f694 (Add team page) and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not revert 8c4f694... Add team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/contact-page
Switched to branch 'ft/contact-page'
warning: cancelling a revert in progress
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/faq-page
Switched to branch 'ft/faq-page'
PS C:\Users\UserNA1842\the-gym-git-exercises> git log
commit 5f207252af60210c73d389316dc73fb1a32d0695 (HEAD -> ft/faq-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 11:48:03 2023 +0200

    Revert "Add team page"

    This reverts commit 8c4f694988e711407e1dd48904e94c6c5aa0ac81.

commit f0163c57dc0382f3f2d0c4bf21d9aeb530d6d29b (origin/ft/faq-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 11:22:42 2023 +0200

    Add faq page

commit 36d694ee3ecd942b0b8a2783b9e5c8d196b4189d (origin/ft/contact-page, ft/contact-page)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Wed Aug 2 11:18:37 2023 +0200

    Add changes to the contact page

commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 5f207252af60210c73d389316dc73fb1a32d0695
[ft/faq-page 0aade71] Revert "Revert "Add team page""
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
commit a0ddbd72533d66b40477b41b9223555103531460 (origin/main, main)
Author: Noella Claire DUSHAKIMANA <dushakenoella@gmail.com>
Date:   Tue Aug 1 12:29:40 2023 +0200

    Add README file
PS C:\Users\UserNA1842\the-gym-git-exercises> git revert 5f207252af60210c73d389316dc73fb1a32d0695
[ft/faq-page 0aade71] Revert "Revert "Add team page""
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Revert the last changes"
On branch ft/faq-page
nothing to commit, working tree clean
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/faq-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 727 bytes | 727.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/NoellaPromise/git-exercises-solutions
   f0163c5..0aade71  ft/faq-page -> ft/faq-page
PS C:\Users\UserNA1842\the-gym-git-exercises>



```
# Bundle 3
## Exercise 2
```
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the home page"
[main 11e0751] Add changes to the home page
 1 file changed, 12 insertions(+)
 create mode 100644 home.html
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
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 1.31 KiB | 58.00 KiB/s, done.
From https://github.com/NoellaPromise/git-exercises-solutions
 * branch            main       -> FETCH_HEAD
   a0ddbd7..749c47f  main       -> origin/main
Merge made by the 'ort' strategy.
 contact.html | 12 ++++++++++++
 team.html    | 12 ++++++++++++
 2 files changed, 24 insertions(+)
 create mode 100644 contact.html
 create mode 100644 team.html
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 754 bytes | 754.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/NoellaPromise/git-exercises-solutions
   749c47f..bdd6121  main -> main
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase main
Auto-merging team.html
CONFLICT (add/add): Merge conflict in team.html
error: could not apply 5f20725... Revert "Add team page"
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 5f20725... Revert "Add team page"
PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase main
fatal: It seems that there is already a rebase-merge directory, and
I wonder if you are in the middle of another rebase.  If that is the
case, please try
        git rebase (--continue | --abort | --skip)
If that is not the case, please
        rm -fr ".git/rebase-merge"
and run me again.  I am stopping in case you still have something
valuable there.

PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase --continue
[detached HEAD 2bc489a] Revert "Add team page"
 1 file changed, 13 insertions(+)
CONFLICT (modify/delete): team.html deleted in 0aade71 (Revert "Revert "Add team page"") and modified in HEAD.  Version HEAD of team.html left in tree.
error: could not apply 0aade71... Revert "Revert "Add team page""
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
Could not apply 0aade71... Revert "Revert "Add team page""
PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase main
Current branch ft/home-page-redesign is up to date.
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase main
Current branch main is up to date.
PS C:\Users\UserNA1842\the-gym-git-exercises> git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'
PS C:\Users\UserNA1842\the-gym-git-exercises> git rebase main
Current branch ft/home-page-redesign is up to date.
PS C:\Users\UserNA1842\the-gym-git-exercises> git add .
PS C:\Users\UserNA1842\the-gym-git-exercises> git commit -m "Add changes to the home page"
[ft/home-page-redesign de5e3b1] Add changes to the home page
 1 file changed, 1 insertion(+)
PS C:\Users\UserNA1842\the-gym-git-exercises> git push origin ft/home-page-redesign
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 8 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 4.19 KiB | 2.09 MiB/s, done.
Total 12 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/NoellaPromise/git-exercises-solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/NoellaPromise/git-exercises-solutions
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
PS C:\Users\UserNA1842\the-gym-git-exercises>


```