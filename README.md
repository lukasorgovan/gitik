# gitik

docs https://git-scm.com/docs

# basic flow
`git status`

`git log`

`git switch {branchName}` ===  `git checkout {branchName}`

`git switch -c {branchName}` === `git checkout -b {branchName}`

`git add {pathToFile}` 
`git add .`

`git commit -m "message"`

# merging
make sure you are on a branch where you want to merge your stuff (e.g. `git switch main`)

`git merge {targetBranchToMerge}`.     (--continue | --abort | --quit)

# working with Origin
`git fetch`

`git pull`

`git push origin {branchName}`
