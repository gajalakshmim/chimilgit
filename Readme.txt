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
cg      https://github.com/gajalakshmim/chimilgit.git (push)

https://github.com/gajalakshmim/chimilgit.git
cg - name for url

bye.
