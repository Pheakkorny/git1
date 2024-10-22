Hello git command:

------------------------
Pheakkorny@DESKTOP-HPO5MFS MINGW64 ~/Desktop (master)
$ pwd
/c/Users/Pheakkorny/Desktop

Pheakkorny@DESKTOP-HPO5MFS MINGW64 ~/Desktop (master)
$ cd d:

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ pwd
/d

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ ls
'$RECYCLE.BIN'/   'OOP y4 2024-2025'/           'Web y4 2024-2025'/
 Database2024/    'Srey Oun'/                    expenses.txt
'Linux y4 2024'/  'System Volume Information'/

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ D;
bash: D: command not found

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ cd ..

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /
$ D:
bash: D:: command not found

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /
$ cd d

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ ls
'$RECYCLE.BIN'/  'Linux y4 2024'/     'System Volume Information'/
 Database2024/   'OOP y4 2024-2025'/  'Web y4 2024-2025'/
 Git/            'Srey Oun'/           expenses.txt

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d
$ cd Git

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git
$ ls
git1/

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git
$ cd git1

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ touch index.html

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ ls
index.html

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ touch readme.txt

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ mkdir api

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ cd api

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1/api
$ cd ..

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ mkdir web_react

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ cd web_react

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1/web_react
$ App.js
bash: App.js: command not found

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1/web_react
$ touch App.js

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1/web_react
$ ls
App.js

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1/web_react
$ cd ..

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ pwd
/d/Git/git1

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$ code .

Pheakkorny@DESKTOP-HPO5MFS MINGW64 /d/Git/git1
$
-------------------------------------------

PS D:\Git\git1> pwd

Path            
----            
D:\Git\git1     


PS D:\Git\git1> git init
Initialized empty Git repository in D:/Git/git1/.git/
PS D:\Git\git1> git status


Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        readme.txt
        web_react/

nothing added to commit but untracked files present (use "git add" to track)
PS D:\Git\git1> git add index.html
PS D:\Git\git1> git status
On branch master

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt
        web_react/

rm 'index.html'
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        readme.txt
        web_react/

nothing added to commit but untracked files present (use "git add" to track)
PS D:\Git\git1> git add .
PS D:\Git\git1> git status
On branch master
No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   web_react/App.js

PS D:\Git\git1> git log
fatal: your current branch 'master' does not have any commits yet
PS D:\Git\git1> git config --global user.name "Pheakkorny"  
PS D:\Git\git1> git log
fatal: your current branch 'master' does not have any commits yet
PS D:\Git\git1> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   web_react/App.js
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.txt
 create mode 100644 web_react/App.js
commit cb6f168b533ba10420be85b365a1a0283c96bcfb (HEAD -> master)
Author: Pheakkorny <pheakkorny@gmail.com>
Date:   Tue Oct 22 10:01:08 2024 +0700

    git1 v1
PS D:\Git\git1> git remote
PS D:\Git\git1> git init
Reinitialized existing Git repository in D:/Git/git1/.git/
PS D:\Git\git1> git branch -M Main
PS D:\Git\git1> git remote add origin https://github.com/Pheakkorny/git1.git
PS D:\Git\git1> git remote
origin
PS D:\Git\git1> git remote -v
origin  https://github.com/Pheakkorny/git1.git (fetch)
origin  https://github.com/Pheakkorny/git1.git (push)
PS D:\Git\git1> git push -u origin Main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 307 bytes | 307.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Pheakkorny/git1.git
 * [new branch]      Main -> Main
branch 'Main' set up to track 'origin/Main'.
PS D:\Git\git1> 
