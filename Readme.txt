Hello git,

I am new to git.
I am gonna learn a lot.

PS C:\Users\mail2\Documents\Gaja> cd .\chimilgit\
PS C:\Users\mail2\Documents\Gaja\chimilgit> git init
Initialized empty Git repository in C:/Users/mail2/Documents/Gaja/chimilgit/.git/
PS C:\Users\mail2\Documents\Gaja\chimilgit> git add *
PS C:\Users\mail2\Documents\Gaja\chimilgit> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   chimil.html
        new file:   chimstyle.css

PS C:\Users\mail2\Documents\Gaja\chimilgit> git add .\Readme.txt
PS C:\Users\mail2\Documents\Gaja\chimilgit> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.txt
        new file:   chimil.html
        new file:   chimstyle.css

PS C:\Users\mail2\Documents\Gaja\chimilgit> git commit -m 'chimil project'
[master (root-commit) 98889c3] chimil project
 3 files changed, 125 insertions(+)
 create mode 100644 Readme.txt
 create mode 100644 chimil.html
 create mode 100644 chimstyle.css
PS C:\Users\mail2\Documents\Gaja\chimilgit>

C:\Users\mail2\Documents\Gaja\chimilgit>git remote

C:\Users\mail2\Documents\Gaja\chimilgit>git remote add cg https://github.com/gajalakshmim/chimilgit.git

C:\Users\mail2\Documents\Gaja\chimilgit>git remote
cg

C:\Users\mail2\Documents\Gaja\chimilgit>git remote push -u cg master
error: Unknown subcommand: push
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


C:\Users\mail2\Documents\Gaja\chimilgit>git push -u cg master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.78 KiB | 365.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/gajalakshmim/chimilgit.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'cg'.

C:\Users\mail2\Documents\Gaja\chimilgit>git remote -v
cg      https://github.com/gajalakshmim/chimilgit.git (fetch)
cg      https://github.com/gajalakshmim/chimilgit.git (pus

https://github.com/gajalakshmim/chimilgit.git
cg - name for url

>git clone https://github.com/gajalakshmim/bike
Cloning into 'bike'...
remote: Enumerating objects: 34, done.
remote: Total 34 (delta 0), reused 0 (delta 0), pack-reused 34
Unpacking objects: 100% (34/34), done.

C:\Users\mail2\Documents\Gaja>dir
 Volume in drive C is OS
 Volume Serial Number is 38E7-09D1

 Directory of C:\Users\mail2\Documents\Gaja

12/20/2019  09:35 AM    <DIR>          .
12/20/2019  09:35 AM    <DIR>          ..
12/20/2019  09:35 AM    <DIR>          bike
11/16/2019  11:25 AM                20 calc.py
12/13/2019  02:50 PM             2,890 chimil.html
12/19/2019  05:23 PM    <DIR>          chimilgit
11/16/2019  11:25 AM             1,023 chimstyle.css
11/08/2019  11:38 AM            32,792 Daisy.jpg
11/01/2019  03:25 PM               385 dictexp.py
11/02/2019  10:14 AM               842 hello.py
11/16/2019  04:28 PM    <DIR>          Projects
11/13/2019  12:14 PM           413,460 rethai.jpg
11/13/2019  12:16 PM           176,765 rethai2.jpg
01/27/2018  04:05 PM                76 test.cpp
               9 File(s)        628,253 bytes
               5 Dir(s)  79,555,547,136 bytes free

C:\Users\mail2\Documents\Gaja>cd bike

C:\Users\mail2\Documents\Gaja\bike>dir
 Volume in drive C is OS
 Volume Serial Number is 38E7-09D1

 Directory of C:\Users\mail2\Documents\Gaja\bike

12/20/2019  09:35 AM    <DIR>          .
12/20/2019  09:35 AM    <DIR>          ..
12/20/2019  09:35 AM    <DIR>          aaa
12/20/2019  09:35 AM    <DIR>          bbb
12/20/2019  09:35 AM    <DIR>          Bicycles
12/20/2019  09:35 AM                39 README.md
12/20/2019  09:35 AM                 0 test.txt.txt
               2 File(s)             39 bytes
               5 Dir(s)  79,555,428,352 bytes free

C:\Users\mail2\Documents\Gaja\bike>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean


C:\Users\mail2\Documents\Gaja\chimilgit>git log
commit d504108f6fa58ae5b2fd56783c34104e783f3bc5 (HEAD -> master, cg/master)
Author: gajalakshmim <m2mgaja@gmail.com>
Date:   Fri Dec 20 09:12:25 2019 -0500

    git commit -a

commit 98889c396d5c50716501a67e85c030acd9aa2b17
Author: gajalakshmim <m2mgaja@gmail.com>
Date:   Thu Dec 19 17:24:21 2019 -0500

    chimil project

C:\Users\mail2\Documents\Gaja\chimilgit>git status
On branch master
Your branch is up to date with 'cg/master'.

nothing to commit, working tree clean

C:\Users\mail2\Documents\Gaja\chimilgit>git branch testing

C:\Users\mail2\Documents\Gaja\chimilgit>git checkout testing
Switched to branch 'testing'

C:\Users\mail2\Documents\Gaja\chimilgit>git status
On branch testing
nothing to commit, working tree clean

C:\Users\mail2\Documents\Gaja\chimilgit>git log --oneline --decorate
d504108 (HEAD -> testing, cg/master, master) git commit -a
98889c3 chimil project

C:\Users\mail2\Documents\Gaja\chimilgit>git add test.txt

C:\Users\mail2\Documents\Gaja\chimilgit>git commit -a
hint: Waiting for your editor to close the file...
[testing 1379070] git commit -a -m 'test branching'
 1 file changed, 1 insertion(+)
 create mode 100644 test.txt

C:\Users\mail2\Documents\Gaja\chimilgit>git log --oneline --decorate -graph --all
fatal: unrecognized argument: -graph

C:\Users\mail2\Documents\Gaja\chimilgit>git log --oneline --decorate --graph --all
* 1379070 (HEAD -> testing) git commit -a -m 'test branching'
* d504108 (cg/master, master) git commit -a
* 98889c3 chimil project

C:\Users\mail2\Documents\Gaja\chimilgit>git checkout master
Switched to branch 'master'
Your branch is up to date with 'cg/master'.

C:\Users\mail2\Documents\Gaja\chimilgit>git log --oneline --decorate --graph --all
* 1379070 (testing) git commit -a -m 'test branching'
* d504108 (HEAD -> master, cg/master) git commit -a
* 98889c3 chimil project

C:\Users\mail2\Documents\Gaja\chimilgit>git add test1.txt

C:\Users\mail2\Documents\Gaja\chimilgit>git commit -u -m 'added'
[master 2985cb9] 'added'
 1 file changed, 1 insertion(+)
 create mode 100644 test1.txt

C:\Users\mail2\Documents\Gaja\chimilgit>git log --oneline --decorate --graph --all
* 2985cb9 (HEAD -> master) 'added'
| * 1379070 (testing) git commit -a -m 'test branching'
|/
* d504108 (cg/master) git commit -a
* 98889c3 chimil project

C:\Users\mail2\Documents\Gaja\chimilgit>git status
On branch master
Your branch is ahead of 'cg/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\mail2\Documents\Gaja\chimilgit>git remote -v
cg      https://github.com/gajalakshmim/chimilgit.git (fetch)
cg      https://github.com/gajalakshmim/chimilgit.git (push)


bye.
