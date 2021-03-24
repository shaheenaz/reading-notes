version control: is a tool to keep tracking of the history of changes and modifying after making commit

cvcs:  is a system have a single server that stores all the changes and can be accessed by other programmers to learn.

dvcs: it is a system that have a backup for your files so if its goes down it will easily replace your data that was saved.

git: its a dvcs that saves your changes every time you commit a new change.(snapshot). it can also allow you to continue working even if there is no internet connection(local operaiton). also it is tracking changes and its extremly hard to loose data by git.

get starting: that what we did yesterday to install it

Tracked Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked Untracked files were not in the last snapshot and do not currently reside in the staging area.

if you want to track a single file use the command  git add filename

if you want to track all files use the command  $ git add *

if you want to commit a change use $ git commit -m “made change x,y,z”

if you want to commit to all chnges use  $ git commit -a

stashing changes: if you dont want to commit a change but you dont want to lose all the data you can use the command git stash and it will hide the changes till you ready to commit them, when you are ready use git stash apply.