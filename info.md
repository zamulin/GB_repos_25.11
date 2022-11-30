# Git start instructions
## `Base command`
> if your not know this, good idea - *DO NOT* touch Git

* `git init` - create local hub repo
* `git status` - view a info current stats
* `git add` - add selected (or all) files to repo
* `git commit` - current branch accepted
* `git log` - view tree changes tracking
  + `git log --graph` - view commits as structural tree
  + **`git log --graph --oneline --all`** - view ALL actual trees
* `git checkout XXXX` - switch to selected XXXX branch
  + `git checkout `**`master`** - switch actual branch
* `git diff` - view different query data

## `Extends command`
> This a grown mind expirience for use

* `git clean` - remove non-indexed files
* `git merge` *`<name_of>`* - join selected branches
* `git reset` - new state HEAD marker updated
* `git branch` - manipulate of branch and fork's
    1. `git branch` - this a simple view of all active trees
    2. `git branch` *`<name_of>`* - create of **new** branches
    3. `git branch` _**`-d <name_of>`**_ - delete selected branch
    4. `git branch -c <name_of>` - copy this branches

## `Further update command`
> Use if need more controls

* `git branch --merged` - view all commited and joined branches

* `git merge ` *`<name_of>`* - join selected branches and current
* `git reset` - new state HEAD marker updated

## `Handsome commands`
> if you need more informations

![Greatest Funny](pandi.jpg)

* `git blame` - View info autors of changes
* `git tag` - View or create points from editor
* `git branch -v` - View all last changes in project

## _`Online Hub repo command`_

* `git clone <name_of>` - create local repo or fork's
* `git push` - update Hub from the local commits.
* `git pull` -load and find diff with local *&&* remote repo
