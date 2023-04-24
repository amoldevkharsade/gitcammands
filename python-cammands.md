git init #..........................to initilize git repo.
git remote add origin repo_link #...to connect / init repo connect to remote. # origin = remote name
git status #........................Shows the status of the working directory and staging area.
git add  file #.....................Adds a file or changes to the staging area.
git commit -m "message"  #..........Commits changes to the local repository with a message.
git pull branch #...................Fetches and merges changes from a remote repository into the current branch.
git push #..........................Pushes changes from the current branch to a remote repository.
git push -u <remote> <branch> #.....Pushes the local branch to a remote repository and sets the upstream branch.
git log  #..........................show the git commit history
git branch #........................Lists all local branches in the current repository.
git checkout branch #...............switch to anoter branch.
git merge #.........................Merges a branch into the current branch.
git clone #.........................Clones a remote repository to your local machine.
git remote #........................Lists all remote repositories linked to the current repository.
git diff #..........................Shows the differences between the working directory and the staging area.
git branch branchname #.............Create new branch.
git checkout -b branchname #........Create new branch
git fetch #.........................Retrieves changes from a remote repository but does not merge them.
git stash #.........................Saves changes in the working directory without committing them, allowing you to switch to another
          #.........................branch or work on a different task.
git tag tagname  #..................Creates a new tag at the current commit.
git reset #.........................Removes changes from the staging area.     
git revert commit #.................Creates a new commit that undoes changes made in a previous commit.
git remote -v #.....................Lists all remote repositories linked to the current repository along with their URLs.
git submodule #.....................Allows you to include a Git repository as a subdirectory of another Git repository.
git cherry-pick commmit #...........Applies changes made in a specific commit to the current branch.
git rm file #.......................Removes a file from the working directory and staging area.

