# Git - linux built-in distributed version control system

* <h3> clone a repo locally </h3>
```
git clone <url>
```
* <h3> Add the new change/untracked files  </h3>
```
git add *                                // Add the change of the current folder

git add <file>                           // Add a specific file

git add .                                // Add all changes in the repo
```
* <h3> Commit the changes </h3>
```
git commit -m <commit message>

git commit                               // Add the commit message in an editor
```
* <h3> Push the changes to the original repo </h3>
```
git push origin <branch>

git push                            // If the branch to be pushed is already set
```
* <h3> Pull the changes from the original repo </h3>
```
git pull origin <branch>            // e.g.: git pull origin master
```
* <h3> Look up the current remote branch </h3>
```
git remote -v
```
* <h3> Add an upstream to the current branch </h3>
```
git remote add upstream <url>
```
* <h3> Fetch the changes from the upstream repo
```
git fetch upstream
```
* <h3> Merge the changes with the current downstream branch
```
git merge upstream/<branch>
```
* <h3> Push the changes to the origin </h3>
```
git push
```
* <h3> Look up the current branch </h3>
```
git branch
```
* <h3> Create a new branch </h3>
```
git branch <branch>
```
* <h3> Check out to another branch </h3>
```
git checkout <branch>
```
* <h3> Create and switch to a new branch at the same time </h3>
```
git checkout -b <branch>
```
* <h3> Stash the changes into the stack in order to switch to another branch </h3>
```
git stash
```
* <h3> Apply the latest stash into the current branch </h3>
```
git stash apply
```
* <h3> List all the stashed changes </h3>
```
git stash list
```
* <h3> Squash the lastest two commits into one </h3>
```
git reset --soft HEAD~2

git commit

git push
```
