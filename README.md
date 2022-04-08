# VITMAS_Task0_-20BCE0642-

##  Git Commands

####    git config

This command sets the author name and email address respectively to be used with your commits.

Usage: git config –global user.name “[name]”

Usage: git config –global user.email “[email address]”

####    git init

This command is used to start a new repository.

Usage: git init [repository name]

####    git clone

This command is used to obtain a repository from an existing URL.

Usage: git clone [url]

####    git add

This command adds a file to the staging area.

Usage: git add [file]

This command adds one or more to the staging area.

Usage: git add *

####    git commit

This command records or snapshots the file permanently in the version history.

Usage: git commit -m “[ Type in the commit message]”

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

Usage: git commit -a

####    git diff

This command shows the file differences which are not yet staged.

Usage: git diff

This command shows the differences between the files in the staging area and the latest version present.

Usage: git diff –staged

This command shows the differences between the two branches mentioned.

Usage: git diff [first branch] [second branch]

####    git reset

This command unstages the file, but it preserves the file contents.

Usage: git reset [file]

This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: git reset [commit]

This command discards all history and goes back to the specified commit.

Usage: git reset –hard [commit]

####    git status

This command lists all the files that have to be committed.

Usage: git status

####    git rm

This command deletes the file from your working directory and stages the deletion.

Usage: git rm [file]
