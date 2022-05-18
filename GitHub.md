# GitHub Reference
## by Shubhrendu Tripathi

<br><br>

# Frequently Used

    $ git clone https://www.github.com/username/project1
    $ cd project1
    $ git config user.email "123456+username@users.noreply.github.com"
    $ git config user.name "John Smith"
    $ git push origin main

# Create new git

    $ git init
    $ git add --all
    $ git commit -m "Message"
    $ git remote add https://github.com/gitname.git

# Git local changes

    $ git status
    $ git add --all
    $ git add -p file

# Git history

    $ git log
    $ git log -p file
    $ git blame file

# Git branch

    $ git branch -av
    $ git branch new-branch-name
    $ git checkout branch

# Git undo

    $ git reset --hard HEAD
    $ git checkout HEAD file
    $ git revert commitID

# Other commands

## List local branches

    $ git branch

## Commit

    $ git commit -am 'Commit comment'

## Create a new branch

    # go to the base branch first
    $ git checkout -b new_branch_name

# switch to an existing branch

    $ git checkout branch_name

# push a local branch to a remote (GitHub)

    $ git push -u origin branch_name

# pull changes from a remote (GitHub)

# switch to a branch to merge the remote to the local

    $ git pull

# to update my local master to match remote master

    $ git pull origin main

# see changes done before and after

If you want to see what you haven't git added yet:

    $ git diff myfile.txt

or if you want to see already added changes

    $ git diff --cached myfile.txt

# display head commit id

    $ git rev-parse HEAD

short version
    
    $ git rev-parse --short HEAD

Also,

    $ git log -1

for only commit id

    $ git log | head -n 1

Another way,

    $ git show-ref --head

by default HEAD is filtered out. Be careful about following though ; plural "heads" with a 's' at the end. The following command shows branches under "refs/heads"

    $ git show-ref --heads

# display url

    $ git config --get remote.origin.url


