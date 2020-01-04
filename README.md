# My first repo
My first repo

## commands
```
Windows PowerShell
Copyright (C) 2015 Microsoft Corporation. All rights reserved.

PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\Code\first_repo> git add .\README.md
PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

PS D:\Code\first_repo> git add --all
PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html

PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        sample.txt

PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

PS D:\Code\first_repo> git add --all
PS D:\Code\first_repo> git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        modified:   README.md
        new file:   index.html

PS D:\Code\first_repo> git commit

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'PrasaHewa@DESKTOP-EQTERIL.(none)')
PS D:\Code\first_repo> git config --global user.email "prasa.hewa@gmail.com"
PS D:\Code\first_repo> git config --global user.name "prasahewa"
PS D:\Code\first_repo> git commit -m "My first commit"
[master 8a147e8] My first commit
 3 files changed, 16 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 index.html
PS D:\Code\first_repo> git log --oneline
8a147e8 (HEAD -> master) My first commit
a707fb3 (origin/master, origin/HEAD) Initial commit
PS D:\Code\first_repo> git log
commit 8a147e89e5055c4a50778c432213df48ce0a32a2 (HEAD -> master)
Author: prasahewa <prasa.hewa@gmail.com>
Date:   Sat Jan 4 20:22:23 2020 +0530

    My first commit

commit a707fb3afbc66de6089063b9ae78500c60ea75bc (origin/master, origin/HEAD)
Author: prasahewa <59506473+prasahewa@users.noreply.github.com>
Date:   Sat Jan 4 19:09:31 2020 +0530

    Initial commit
PS D:\Code\first_repo> git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 533 bytes | 533.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/prasahewa/first_repo.git
   a707fb3..8a147e8  master -> master
PS D:\Code\first_repo>
```

