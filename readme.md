<!--
Marked Style: Github
-->

# GitRuler Section C

This repository is section C of the [GitRuler exercises](https://github.com/UOL-CS/gitruler-exercises). If you do not already have a your own repository for these exercises [fork this repository](https://help.github.com/articles/fork-a-repo/). 

In this exercise we will learn about moving and removing files within a repository and telling git to ignore a set of files.

## Ignoring Files

If there are many files in our directories that we never want to track using git then we can tell git to ignore them. This often happens while programming because we don't want to commit compiled files. 

Imagine that the [text editor](https://en.wikipedia.org/wiki/Text_editor) used by our shop-keeper creates backup files whenever he edits one. The `files/ideas` folder is full of these `.bak` files. Rather than having to keep deleting these and so that we can easily commit the  `ideas` directory, we want git to ignore all of them.

There is also a `files/ideas/drafts` folder where he keeps files that are not yet ready to commit. We want git to always ignore files within this folder.

1. Run GitRuler to initialise the exercise.
1. Create the necessary file and contents so that git will ignore all files ending with `.bak` in the `files/ideas` folder and everything in the `files/ideas/drafts` folder.
2. Commit this file with the commit message "Ignore draft and backup ideas".
3. Commit all of the `.txt` files in the `files/ideas/` folder (you should now be able to stage them all with a single `git add` command) with the commit messages "Add extra ideas".

## Moving and removing files in git

It's decided to create a folder for great ideas and to remove some of the worst ones.

1. Create a folder `files/ideas/great` (this is not a git action just creating a folder on your machine).
2. [Use git to move](https://githowto.com/moving_files) `new-website.txt`, `better-signs.txt` and `put-locks-on-the-doors.txt` to the `files/ideas/great` folder.
3. Commit the moved files with the message "Move great ideas".
4. [Remove](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository) the files `smaller-plums.txt` and `blue-uniforms.txt` from git and commit this with the message "Remove bad ideas".
5. Commit the removal of files with the message "Remove bad ideas".

## Submitting the results

Once the exercise is complete, push this repository to the remote. If there are multiple branches for an exercise, make sure that you push them all. 

To ensure that you have you correctly pushed everything that you need to, you could clone the remote repository into a separate folder and re-run gitruler.

## Resources

1. There are many resources about how to tell git to ignore files or folders. One example is in the [Atlassian git tutorial](https://www.atlassian.com/git/tutorials/saving-changes/gitignore)
2. There are also many resources for moving and removing files. Just Google.