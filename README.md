XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo     
$ mkdir my_repo

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo     
$ cd my_repo

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo
$ git init
Initialized empty Git repository in D:/Git_Demo/my_repo/.git/


Run

MINGW64 /d/Git_Demo/my_repo (master)
$ git config --global user.email "vinaychotia2002@gmail.com"

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git config --global user.name "vinaychotia12"

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git init
er.name "vinaychotia12" 

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git init
 1 file changed, 0 insertions(+), 0 deletions(-) create mode 100644 first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git log
commit 58dce6ad6aab8180aaca1e34adc9bac47f961642 (HEAD -> master)
Author: vinaychotia12 <vinaychotia2002@gmail.com>
Date:   Sun Oct 6 17:07:55 2024 +0530

    adding first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ touch second.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git add second.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git commit -m "adding second.txt"
[master 0f368ed] adding second.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 second.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ rm first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git add first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git commit -m "removing first.txt"
[master 1dc8232] removing first.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git log
commit 1dc82324d9bfd33a7efd0d58414d166f794b5c58 (HEAD -> master)
Author: vinaychotia12 <vinaychotia2002@gmail.com>
Date:   Sun Oct 6 17:15:16 2024 +0530

    removing first.txt

commit 0f368ede841390c3298ca10a27a32ad46c5d23a6
Author: vinaychotia12 <vinaychotia2002@gmail.com>
Date:   Sun Oct 6 17:10:58 2024 +0530

    adding second.txt

commit 58dce6ad6aab8180aaca1e34adc9bac47f961642
Author: vinaychotia12 <vinaychotia2002@gmail.com>
Date:   Sun Oct 6 17:07:55 2024 +0530

    adding first.txt

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (master)
$ git remote add origin https://github.com/Vinaychotia12/my_repo.git
git branch -M main
git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 642 bytes | 214.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Vinaychotia12/my_repo.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (main)
$ git remote add origin https://github.com/Vinaychotia12/my_repo.git
error: remote origin already exists.

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (main)
$ commit
bash: commit: command not found

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (main)
$ git commit
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (main)
$ git push origin main
Everything up-to-date

XPRISTO@DESKTOP-005PTJ9 MINGW64 /d/Git_Demo/my_repo (main)
$
