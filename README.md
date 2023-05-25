# rere
j'ai d'abord créé un dossier sur mon bureau.
Ensuite j'ai ouvert mon editeur .
et j'ai fait de meme avec GIT BASH.
j'ai créé mes fichers a partir de GIT BASH avec la ligne de commande "touch + le nom du ficher que vous voulez créer"
je l'ai initialisé avec GIT INIT.
Ces commande m'ont permit de m'identifier: "git config --global user.name et git config --global user.email"
"Git add ." c'est ajouter tous les fichers presents
" git status" pour avoir une apercu de ce que nous faisons.
"git add *.html *.css" pour ajouter les derniers changements
 git commit -m "changement css et html"
"touch .gitignore" pour creer un ficher GITIGNORE 
$ git config --global user.name
baya28

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git config --global user.email
yabaye2000@gmail.com

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add index.html

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git rm --cached index.html
rm 'index.html'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch style.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git rm -r --cached
fatal: No pathspec was given. Which files should I remove?

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index.html
        deleted:    style.css


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git checkout -- .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git  commit
hint: Waiting for your editor to close the file...       0 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                                                                  494181 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                                                                                797090 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
              995842 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                           1230556 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
[master (root-commit) 12b9ec1] premiere savpremierepremiere savpremiere savee savpremiere saveee
 2 files changed, 12 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add *.html *.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git commit -m "changement css et html"
[master 2962494] changement css et html
 2 files changed, 4 insertions(+)

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch ,gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch .gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git commit -m "ajout de gitignore"
[master 20dcffb] ajout de gitignore
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch FicherJS

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git checkout FicherJS
Switched to branch 'FicherJS'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git status
On branch FicherJS
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ touch main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit "ajout du ficher JS"
error: pathspec 'ajout du ficher JS' did not match any file(s) known to git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit -m "ajout du ficher JS"
[FicherJS 7b62cc3] ajout du ficher JS
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git checkout master
Switched to branch 'master'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git merge FicherJS
Updating 20dcffb..7b62cc3
Fast-forward
 index.html | 2 +-
 main.js    | 1 +
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git remote add origin https://github.com/baya28/rere.git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git -u origin main
unknown option: -u
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git  origin main
git: 'origin' is not a git command. See 'git --help'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch - M main
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/baya28/rere.git'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin master
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (14/14), 1.38 KiB | 472.00 KiB/s, done.
Total 14 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/baya28/rere.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$
 

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git commit -m "ajout de gitignore"
[master 20dcffb] ajout de gitignore
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch FicherJS

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git checkout FicherJS
Switched to branch 'FicherJS'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git status
On branch FicherJS
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ touch main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit "ajout du ficher JS"
error: pathspec 'ajout du ficher JS' did not match any file(s) known to git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit -m "ajout du ficher JS"
[FicherJS 7b62cc3] ajout du ficher JS
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git checkout master
Switched to branch 'master'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git merge FicherJS
Updating 20dcffb..7b62cc3
Fast-forward
 index.html | 2 +-
 main.js    | 1 +
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git remote add origin https://github.com/baya28/rere.git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git -u origin main
unknown option: -u
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git  origin main
git: 'origin' is not a git command. See 'git --help'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch - M main
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/baya28/rere.git'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin master
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (14/14), 1.38 KiB | 472.00 KiB/s, done.
Total 14 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/baya28/rere.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$
$ git config --global user.name
baya28

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git config --global user.email
yabaye2000@gmail.com

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add index.html

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git rm --cached index.html
rm 'index.html'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch style.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git rm -r --cached
fatal: No pathspec was given. Which files should I remove?

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index.html
        deleted:    style.css


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git checkout -- .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git  commit
hint: Waiting for your editor to close the file...       0 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                                                                  494181 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                                                                                797090 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
              995842 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
                           1230556 [sig] bash 1063! sigpacket::process: Suppressing signal 18 to win32 process (pid 2364)
[master (root-commit) 12b9ec1] premiere savpremierepremiere savpremiere savee savpremiere saveee
 2 files changed, 12 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add *.html *.css

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git commit -m "changement css et html"
[master 2962494] changement css et html
 2 files changed, 4 insertions(+)

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch ,gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ touch .gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

nothing added to commit but untracked files present (use "git add" to track)

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git commit -m "ajout de gitignore"
[master 20dcffb] ajout de gitignore
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .gitignore

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git status
On branch master
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch FicherJS

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git checkout FicherJS
Switched to branch 'FicherJS'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git status
On branch FicherJS
nothing to commit, working tree clean

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ touch main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git add .

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit "ajout du ficher JS"
error: pathspec 'ajout du ficher JS' did not match any file(s) known to git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git commit -m "ajout du ficher JS"
[FicherJS 7b62cc3] ajout du ficher JS
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (FicherJS)
$ git checkout master
Switched to branch 'master'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git merge FicherJS
Updating 20dcffb..7b62cc3
Fast-forward
 index.html | 2 +-
 main.js    | 1 +
 2 files changed, 2 insertions(+), 1 deletion(-)
 create mode 100644 main.js

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git remote add origin https://github.com/baya28/rere.git

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git -u origin main
unknown option: -u
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git  origin main
git: 'origin' is not a git command. See 'git --help'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git branch - M main
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output


yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/baya28/rere.git'

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$ git push -u origin master
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (11/11), done.
Writing objects: 100% (14/14), 1.38 KiB | 472.00 KiB/s, done.
Total 14 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/baya28/rere.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

yabay@DESKTOP-5HTQS8B MINGW64 ~/OneDrive/Bureau/rere (master)
$
