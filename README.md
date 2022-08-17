# Git for Researchers: Tips & Tricks
The repository contains some pieces of code that I found useful when it comes writing a scientific paper or experiments



How to save changes locally before pulling from the remote
```
# 1. Stash local changes

git stash

# 2. Pull in the changes from origin.

git fetch origin

# 3. Add the stash back in to your working directory:

git stash pop
```
