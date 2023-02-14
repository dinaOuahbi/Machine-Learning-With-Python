# how to use git ?


 ## The most useful Git commands

        git init : convert a folder to a git repository (initialize)

        git clone : to download the source code from gitHub or others remote 

        git remote rm origin : dissociate the downloaded current repo from the origin

        Git branch <branch-name> : to create a new branch in local

        git branch : view all branches

        git branch --list

        git branch -d <branch-name> : delete a branch

        git checkout <branch-name>: switch you into the branch-name whene you create a new branch 

        the branch i want to switch must be created in local also 

        git checkout -b <branch-name> : create and switch automatically

        git add 'file' : add file to the next commit

        git add . : add all files

        git add -A

        git commit -a : commit all changes and give prompt to enter msg

        git commit -am "my  msg" : commit and enter msg

        git push <remote> <branch-name> : push changes in my remote origin

        git pull <remote> : fetch changes in git repo and merge it with my local repo

        git diff : show any uncommitted changes in my local

        git diff branch1, ... , branche2 : show differences between branches

        git stash save "msg" stach my changes whene i want to come back and restore it 

        git stash save -u : 

        git stash --list

        git status : give informations about current branch, changes, commits ... 

        git log : give commit history 

        git merge : merge my feature branch with parent branche, but before we have to switch into parent branch and pulling the updates
