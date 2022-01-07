# Hacking Git & Github
This repository contains materials and resources about Git &amp; GitHub

Set Up Git

- git config --global user.name "Your Name"

- git config --global user.email username@something.edu

- git config --global core.editor code

Confirm that you set up git properly

- git config --list

# Git Hacks
- Commits

#  Porcelain commands 
git add, git commit


To verify the commit we have just created: git log

git log --format=fuller

git log --format=raw

git log --oneline

git log --oneline --graph --decorate

git log --oneline --graph --decorate --all

git commit -am " message"

Undo a commit: git reset --hard "ef6c382"
Stepping back from a branch: git reset --hard HEAD^

Detached HEAD: git checkout HEAD^


Move me to the branch I was before switching: git checkout -
Moves a branch from the current position to a new one: git reset --hard master


#   Plumbing commands
git cat-file -p  " 5 first characters from hash"

git hash-object:echo "banana" | git hash-object --stdin



# The Git storage object model
ll .git/





# Core Reading
#1.Tutorials and Websites

https://git-scm.com/book/en/v2

http://think-like-a-git.net/

https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html









#2. Books

Git Essentials 2nd by Ferdinando Santacroce 

https://www.goodreads.com/book/show/25533645-git-essentials
