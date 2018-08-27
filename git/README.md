# Git - linux built-in distributed version control system

* <h3> clone a repo locally </h3>
```
git clone <url>
```
* <h3> Add the new change/untracked files  </h3>
```
git add *  // Add the change of the current folder

git add <file>  // Add a specific file

git add .  // Add all changes in the repo
```
* <h3> Commit the changes </h3>
```
git commit -m <commit message>

git commit  // Add the commit message in an editor
```
* <h3> Push the changes to the original repo </h3>
```
git push origin <branch>

git push // If the branch to be pushed is already set
```
* <h3> Pull the changes from the original repo </h3>
```
git pull origin <branch> // e.g.: git pull origin master
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
