answer 1 
git version 2.39.2

answer 2
user.name=ericjulienhanson@penguin
user.email=eric.julien.hanson@gmail.com

ans 3
It shows all the documentation of the commands on how to use git.

ans 4

ericjulienhanson@penguin:~/2400/Labs/git-lab$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

ans 5

ericjulienhanson@penguin:~/2400/Labs/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


ans 6

ericjulienhanson@penguin:~/2400/Labs/git-lab$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

ans 7

ericjulienhanson@penguin:~/2400/Labs/git-lab$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

ans 8

ericjulienhanson@penguin:~/2400/Labs/git-lab$ git log
commit 9a5743b22b22355b0c9c8b3ca37a009372d9a2bb (HEAD -> master)
Author: ericjulienhanson@penguin <eric.julien.hanson@gmail.com>
Date:   Wed Sep 4 16:58:21 2024 -0400

    Initial commit

ans 9

On my repository was updated with the inclusion on README.md and answers.md

ans 10

The changes I made online where not recorded.

ans 11

The push did not work because I need to git pull the new repo changes.

ans 12

The Changes I made online Where reflected on my local when i did git pull.

ans 13
ericjulienhanson@penguin:~/2400/git-lab-2$ ls -a
.  ..  .git  .gitignore  README.md


DONE

