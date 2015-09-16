# Git cheatsheet

* ```git clone <url>``` - Clone a remote repository from the web to your local
computer. Puts it into a folder of the name of the repo under your current 
directory.

* ```git pull <remote> <branch>``` - "Pull" the git repo from the specified
remote and branch. Updates the current branch with the files retrieved. Make
sure to be in the correct branch when executing (usually the pulled branch).

* ```git add <file>``` - Tell git to add the given file for the next commit.
Also called "staging for commit".

* ```git commit``` - Puts files into the git version history. Opens the default
text editor to write a commit message. Messages can be directly set with the -m
flag.

* ```git commit --amend``` - Adds the currently added files to the most recent commit.

* ```git reset HEAD <file>``` - Unstages a file undos the adding of a file.

* ```git checkout <file>``` - Undoes changes to a file since the last commit.

* ```git stash``` - Temporarily stores your changes to be reapplied later.

* ```git stash apply``` - Applies stashed changes to your files.

* ```git ```
