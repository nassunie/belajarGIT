## Daftar Tugas / Branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
 Daftar Perintah Git
...
ASUS@DESKTOP-3JKNJ1D MINGW64 ~
$ git clone https://github.com/nassunie/belajarGIT~
Cloning into 'belajarGIT~'...
remote: Repository not found.
fatal: repository 'https://github.com/nassunie/belajarGIT~/' not found

ASUS@DESKTOP-3JKNJ1D MINGW64 ~
$ git clone https://github.com/nassunie/belajarGIT.git      Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~
$ cd belajarGIT/

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ ^[[200~git branch Tugas-git
bash: $'\E[200~git': command not found

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-git

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ ls
README.md  Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'ASUS@DESKTOP-3JKNJ1D.(none)')

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ ^C

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git config --global user.email "cacatubuon04@gmail.com"
bash: $'\302\203git': command not found

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git config --global user.email "cacatubuon04@gmailcom"
git config --global user.name "Nasya"

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-Git.txt"
[Tugas-git c770ebc] Menambahkan file Tugas-Git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ notepad Tugas-Git.txt


ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git commit -m "teks berisi  'caca dan haechan' ditambahkan ke dalam file Tugas-Git.txt"
[Tugas-git 05ce0a8] teks berisi  'caca dan haechan' ditambahkan ke dalam file Tugas-Git.txt
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-Git
Updating 39f80a6..05ce0a8
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main



ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 603 bytes | 201.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/nassunie/belajarGIT.git
   39f80a6..05ce0a8  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-html

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ ls
README.md  Tugas-Git.txt  Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Html.txt

nothing added to commit but untracked files present (use "git add" to track)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-Html.txt"
[Tugas-html 09481b3] Menambahkan file Tugas-Html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git checkout Tugas-html
Already on 'Tugas-html'

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ notepad Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git commit -m "Teks berisi 'caca dan haechan'telah ditambahkan ke file Tugas-Html.txt"
[Tugas-html 1dc20d1] Teks berisi 'caca dan haechan'telah ditambahkan ke file Tugas-Html.txt
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-
Tugas-git    Tugas-html

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-html
Updating 05ce0a8..1dc20d1
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 588 bytes | 196.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/nassunie/belajarGIT.git
   05ce0a8..1dc20d1  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-css

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ touch Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ ls
README.md  Tugas-Git.txt  Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ ls
README.md  Tugas-Css.txt  Tugas-Git.txt  Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ rm Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ ls
README.md  Tugas-Css.txt  Tugas-Html.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-Css.txt"
[Tugas-css 00510c8] Menambahkan file Tugas-Css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ notepad Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git commit -m "teks baru telah ditambahkan dalam fle Tugas-css.txt"
[Tugas-css 6b78a54] teks baru telah ditambahkan dalam fle Tugas-css.txt
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
D       Tugas-Git.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-css
Updating 1dc20d1..6b78a54
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 607 bytes | 607.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/nassunie/belajarGIT.git
   1dc20d1..6b78a54  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git b
bisect   blame    branch   bundle

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-js

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'
D       Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ ls
README.md  Tugas-Css.txt  Tugas-Html.txt  Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ git commit - "Menambahkan file Tugas-Js.txt"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'Menambahkan file Tugas-Js.txt' did not match any file(s) known to git

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ notepad Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ git commit -m "text berhasil ditambahkan"
[Tugas-js 015b460] text berhasil ditambahkan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
D       Tugas-Git.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-js
Updating 6b78a54..015b460
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 271.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/nassunie/belajarGIT.git
   6b78a54..015b460  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-midProject

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'
D       Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ ls
README.md      Tugas-Html.txt  Tugas-MidProject.txt
Tugas-Css.txt  Tugas-Js.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git commit -m "file berhasil ditambahkan"
[Tugas-midProject c504eb5] file berhasil ditambahkan
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ notepad Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git commit -m "Teks berhasil ditambahkan"

[Tugas-midProject b7d2024] Teks berhasil ditambahkan
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git che
checkout      cherry        cherry-pick

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
D       Tugas-Git.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-midProject
Updating 015b460..b7d2024
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 504 bytes | 45.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nassunie/belajarGIT.git
   015b460..b7d2024  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-php

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'
D       Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ ls
README.md      Tugas-Html.txt  Tugas-MidProject.txt
Tugas-Css.txt  Tugas-Js.txt    Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ git commit -m "file berhasil ditambahkan"
[Tugas-php 115d827] file berhasil ditambahkan
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ notepad Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ git commit -m "teks berhsil ditambahkan"
[Tugas-php 78b32af] teks berhsil ditambahkan
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
D       Tugas-Git.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-php
Updating b7d2024..78b32af
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 498 bytes | 498.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nassunie/belajarGIT.git
   b7d2024..78b32af  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git branch Tugas-finalProject

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'
D       Tugas-Git.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ ls
README.md               Tugas-Html.txt        Tugas-Php.txt
Tugas-Css.txt           Tugas-Js.txt
Tugas-FinalProject.txt  Tugas-MidProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git commit -m "file berhasil ditambahkan"
[Tugas-finalProject 0688296] file berhasil ditambahkan
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ notepad Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git commit -m "teks berhasil ditambahkan"
[Tugas-finalProject f5cc988] teks berhasil ditambahkan
 1 file changed, 1 insertion(+)

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
D       Tugas-Git.txt
Your branch is up to date with 'origin/main'.

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 78b32af..f5cc988
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 454 bytes | 454.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/nassunie/belajarGIT.git
   78b32af..f5cc988  main -> main

ASUS@DESKTOP-3JKNJ1D MINGW64 ~/belajarGIT (main)
$ 
