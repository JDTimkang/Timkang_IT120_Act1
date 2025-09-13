
lenovo@DESKTOP-D5SS6DV MINGW64 ~
$ cd desktop

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop
$ mkdir Timkang_IT120_Act1

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop
$ cd Timkang_IT120_Act1

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/lenovo/Desktop/Timkang_IT120_Act1/.
git/

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git add .

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'lenovo@DESKTOP-D5SS6DV.(none)')

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git config --global user.name "Johndave T."

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ ^C

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git config --global user.email "dzandavetimkang@gmail.com"

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Johndave T.
user.email=dzandavetimkang@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) 8e84b01] Initial commit with all files
 5 files changed, 12 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git remote add origin https://github.com/JDTimkang/Timkang_IT120_Act1.git

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git remote -v
origin  https://github.com/JDTimkang/Timkang_IT120_Act1.git (fetch)
origin  https://github.com/JDTimkang/Timkang_IT120_Act1.git (push)

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git puh origin master
git: 'puh' is not a git command. See 'git --help'.

The most similar command is
        push

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 655 bytes | 50.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/JDTimkang/Timkang_IT120_Act1.git
 * [new branch]      master -> master

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git branch -M master

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/JDTimkang/Timkang_IT120_Act1.git'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git checkout -b Timkang_B1
Switched to a new branch 'Timkang_B1'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git branch
* Timkang_B1
  master

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git add profile.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation"
On branch Timkang_B1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Profile.txt

no changes added to commit (use "git add" and/or "git commit -a")

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git add Profile.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation"
[Timkang_B1 9a7017e] Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation
 1 file changed, 7 insertions(+), 1 deletion(-)

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git push origin Timkang_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 516 bytes | 103.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Timkang_B1' on GitHub by visiting:
remote:      https://github.com/JDTimkang/Timkang_IT120_Act1/pull/new/Timkang_B1
remote:
To https://github.com/JDTimkang/Timkang_IT120_Act1.git
 * [new branch]      Timkang_B1 -> Timkang_B1

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git add Readme.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B1)
$ git checkout master
M       Readme.txt
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git checkout -b Timkang_B2
Switched to a new branch 'Timkang_B2'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B2)
$ git add Education.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B2)
$ git commit -m "Amend: updated Education.txt with details"
[Timkang_B2 f7a67f8] Amend: updated Education.txt with details
 2 files changed, 175 insertions(+), 1 deletion(-)

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B2)
$ git push origin Timkang_B2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 2.10 KiB | 357.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'Timkang_B2' on GitHub by visiting:
remote:      https://github.com/JDTimkang/Timkang_IT120_Act1/pull/new/Timkang_B2
remote:
To https://github.com/JDTimkang/Timkang_IT120_Act1.git
 * [new branch]      Timkang_B2 -> Timkang_B2

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B2)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git checkout -b Timkang_B3
Switched to a new branch 'Timkang_B3'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B3)
$ git add Background.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B3)
$ git rm Test.py
rm 'Test.py'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B3)
$ git commit -m "Amend: updated Background.txt and removed Test.py"
[Timkang_B3 a487efc] Amend: updated Background.txt and removed Test.py
 2 files changed, 3 insertions(+), 1 deletion(-)
 delete mode 100644 Test.py

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B3)
$ git push origin Timkang_B3
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (9/9), 1012 bytes | 84.00 KiB/s, done.
Total 9 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'Timkang_B3' on GitHub by visiting:
remote:      https://github.com/JDTimkang/Timkang_IT120_Act1/pull/new/Timkang_B3
remote:
To https://github.com/JDTimkang/Timkang_IT120_Act1.git
 * [new branch]      Timkang_B3 -> Timkang_B3

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B3)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (master)
$ git checkout -b Timkang_B4
Switched to a new branch 'Timkang_B4'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B4)
$ git add Readme.txt

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B4)
$ git rm Test.py
rm 'Test.py'

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B4)
$  git commit -m "Amend: updated Readme.txt and removed Test.py"
[Timkang_B4 ae5d8e1] Amend: updated Readme.txt and removed Test.py
 1 file changed, 255 insertions(+)

lenovo@DESKTOP-D5SS6DV MINGW64 ~/desktop/Timkang_IT120_Act1 (Timkang_B4)
$ git push origin Timkang_B4
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (11/11), 3.05 KiB | 208.00 KiB/s, done.
Total 11 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'Timkang_B4' on GitHub by visiting:
remote:      https://github.com/JDTimkang/Timkang_IT120_Act1/pull/new/Timkang_B4
remote:
To https://github.com/JDTimkang/Timkang_IT120_Act1.git
 * [new branch]      Timkang_B4 -> Timkang_B4

