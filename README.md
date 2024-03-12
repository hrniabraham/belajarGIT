Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…

Lenovo@DESKTOP-30M184R MINGW64 ~
$ cd /d

Lenovo@DESKTOP-30M184R MINGW64 /d
$ cd tugasWEB

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB
$ git clone https://github.com/hrniabraham/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB
$ cd belajarGIT

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git remote -v
origin  https://github.com/hrniabraham/belajarGIT.git (fetch)
origin  https://github.com/hrniabraham/belajarGIT.git (push)

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git branch
* main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ echo "GIT" > Tugas-git.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git add Tugas-git.txt
warning: in the working copy of 'Tugas-git.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
[Tugas-git 1c4f125] Menambahkan dan mengubah Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git merge Tugas-git
Already up to date.
bash: /mingw64/bin/git: Device or resource busy

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git push origin main
fatal: unable to access 'https://github.com/hrniabraham/belajarGIT.git/': Could not resolve host: github.com

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git remote -v
origin  https://github.com/hrniabraham/belajarGIT.git (fetch)
origin  https://github.com/hrniabraham/belajarGIT.git (push)

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git push origin main
Everything up-to-date

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan dan mengubah Tugas-git.txt"
On branch Tugas-git
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git push origin main
Everything up-to-date

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-git
Updating cd6faf1..1c4f125
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 104.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/hrniabraham/belajarGIT.git
   cd6faf1..1c4f125  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ echo "HTML" > Tugas-html.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
warning: in the working copy of 'Tugas-html.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-html.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan dan mengubah Tugas-html.txt"
[Tugas-html b889811] Menambahkan dan mengubah Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt
g
Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-html
Updating 1c4f125..b889811
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git origin main
git: 'origin' is not a git command. See 'git --help'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 345 bytes | 172.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/hrniabraham/belajarGIT.git
   1c4f125..b889811  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ echo "CSS" > Tugas-css.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-css.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan dan mengubah Tugas-css.txt"
[Tugas-css becb411] Menambahkan dan mengubah Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git status

On branch Tugas-css
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-css
Updating b889811..becb411
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 371 bytes | 123.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/hrniabraham/belajarGIT.git
   b889811..becb411  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ echo "JS" > Tugas-js.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-js.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan dan mengubah Tugas-js.txt"
[Tugas-js feb7d07] Menambahkan dan mengubah Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-js
Updating becb411..feb7d07
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 152.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/hrniabraham/belajarGIT.git
   becb411..feb7d07  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ echo "midProject" > Tugas-midProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-midProject.txt

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-midProject.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan dan mengubah Tugas-midProject.txt"
[Tugas-midProject 465324d] Menambahkan dan mengubah Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-midProject
Updating feb7d07..465324d
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 163.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/hrniabraham/belajarGIT.git
   feb7d07..465324d  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'
tou
Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ touch Tugas-php.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ echo "PHP" >Tugas-php.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-php.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan dan mengubah Tugas-php.txt"
[Tugas-php 7b884f0] Menambahkan dan mengubah Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-php
Updating 465324d..7b884f0
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 153.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/hrniabraham/belajarGIT.git
   465324d..7b884f0  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ echo "finalProject" >Tugas-finalProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-html.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-finalProject.txt

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ gid add Tugas-finalProject.txt
bash: gid: command not found

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-finalProject.txt


Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan dan mengubah Tugas-finalProject.txt"
[Tugas-finalProject c583dea] Menambahkan dan mengubah Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 7b884f0..c583dea
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 325 bytes | 162.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/hrniabraham/belajarGIT.git
   7b884f0..c583dea  main -> main

Lenovo@DESKTOP-30M184R MINGW64 /d/tugasWEB/belajarGIT (main)
$
