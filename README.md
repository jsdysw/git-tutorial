# git-tutorial

source : https://backlog.com/git-tutorial/kr/

### Glosary
- work tree : work place
- index : space for ````add````s, staging
- repository : space for ````commit````s
- stash : temporary space to save current work without commit and checkout another branch

### remote repository
| Command | example |
| --- | --- |
| init | ````git init```` |
| status | ````git status```` |
| add all | ````git add -A```` |
| add file | ````git add filename```` |
| commit | ````git commit -m "message"```` |
| log | ````git log```` |
| clone | ````git clone url```` |
| remote list | ````git remote -v```` |
| remote add | ````git remote add origin url```` |
| pull(merge commit) | ````git pull origin master```` (-> solve collision -> commit) |
| fetch | ````git fetch origin```` |
| push | ````git push origin master```` |

### branch
| Command | example |
| --- | --- |
| list branch | ````git branch```` |
| make branch | ````git branch name```` |
| delete branch | ````git branch -d name```` |
| checkout | ````git checkout name```` |
| make and checkout | ````git checkout -b name```` |
| merge(fast-forward) | ````git merge branchname ````|
| merge(non fast-forward) | ````git merge branchname```` (-> solve collision -> add,commit) |
| rebase | ````git rebase branchname```` (-> solve collision -> add -> ````git rebase --continue````) -> ````git checkout branchname```` -> ````git merge firstbranch```` |

### change commit
| Command | example |
| --- | --- |
| amend | ````git commit --amend```` |
| revert (need to revert recent commit first) | ````git revert HEAD```` |

### tag
| Command | example |
| --- | --- |
| make tag | ````git tag tagname```` |
| tag list | ````git tag```` |
| tag list with comment | ````git tag -n```` |
| log with tag name | ````git log --decorate```` |
| make tag with comment | ````git tag -a tagname```` |
| make tag with comment2 | ````git tag -am "message" tagname```` |
| delete tag | ````git tag -d tagname```` |




