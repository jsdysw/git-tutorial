# git-tutorial

source : https://backlog.com/git-tutorial/kr/

| Command | example |
| --- | --- |
| init | ````git init```` |
| status | ````git status```` |
| add | ````git add -A```` |
| commit | ````git commit -m "message"```` |
| log | ````git log```` |
| clone | ````git clone url```` |
| remote list | ````git remote -v```` |
| remote add | ````git remote add origin url```` |
| pull | ````git pull origin master```` |
| fetch | ````git fetch origin```` |
| push | ````git push origin master```` |
| list branch | ````git branch```` |
| make branch | ````git branch name```` |
| delete branch | ````git branch -d name```` |
| checkout | ````git checkout name```` |
| make and checkout | ````git checkout -b name```` |
| merge(fast-forward) | ````git merge branchname ````|
| merge(non fast-forward) | ````git merge branchname```` (-> solve collision -> add,commit) |
| rebase | ````git rebase branchname```` (-> solve collision -> add -> ````git rebase --continue````) -> ````git checkout branchname```` -> ````git merge firstbranch```` |

stash


