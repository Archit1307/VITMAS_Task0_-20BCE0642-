# VITMAS_Task0_-20BCE0642-

##  Git Commands

1. * ####     `git config`

This command sets the author name and email address respectively to be used with your commits.

Usage:

```git config –global user.name “[name]”```

``` git config –global user.email “[email address]”```

2. * ####    `git init`

This command is used to start a new repository.

Usage:

```git init [repository name]```

3. * ####    `git clone`

This command is used to obtain a repository from an existing URL.

Usage: 

```git clone [url]```

4. * ####    `git add`

This command adds a file to the staging area.

Usage:

```git add [file]```

This command adds one or more to the staging area.

Usage: 

```git add *```

5. * ####    `git commit`

This command records or snapshots the file permanently in the version history.

Usage:
```git commit -m “[ Type in the commit message]”```

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

Usage: 

```git commit -a```

6. * ####    `git diff`

This command shows the file differences which are not yet staged.

Usage: 

```git diff```

This command shows the differences between the files in the staging area and the latest version present.

Usage: 

```git diff –staged```

This command shows the differences between the two branches mentioned.

Usage:

```git diff [first branch] [second branch]```

7. * ####    `git reset`

This command unstages the file, but it preserves the file contents.

Usage: 

```git reset [file]```

This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: 

```git reset [commit]```

This command discards all history and goes back to the specified commit.

Usage: 

```git reset –hard [commit]```

8. * ####    `git status`

This command lists all the files that have to be committed.

Usage: 

```git status```

9. * ####    `git rm`

This command deletes the file from your working directory and stages the deletion.

Usage: 

```git rm [file]```

10. * ####    `git log`

This command is used to list the version history for the current branch.

Usage: 

```git log```

This command lists version history for a file, including the renaming of files also.

Usage: 

```git log –follow[file]```

