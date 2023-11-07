
# Basic git commands

**Init a container**

`mkdir test`

`cd test`

`git init`

**Creating a branch**

`git checkout -b my-branch`

**Switch a branch**

`git switch my-branch`

or

`git checkout my-branch`


**Merge two branches**

`git switch main`
`git merge my-branch`

**Delete a branch**

`git branch -d my-branch`

**Adding a remote repository with name origin**

`git remote add origin https://github.com/myaccount/myrepo`


**Clone a remote repository**

`git clone https://github.com/azure/bicep`

**To see what changes your remote repository has use fetch**

*origin is the remote repository and main is the local branch*

`git fetch origin main`

**Push your changes on the remote repository**

`git push --set-upstream origin main`

`git remote add origin https://github.com/myaccount/myrepo`

