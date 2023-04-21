# Terminal cheatsheet to use 

### Directory & Files
* `mkdir` - creates new directory (folder)
* `cd` - change directory
* `cd ~` - return to home directory
* `cd -` - return to previous directory
* `pwd` shows path to current directory
* `touch` - creates new file
* `mv` - moves files from one location to another
* `pkill java` - stops running




### Lists
* `ls` - lists folders and files
* `ls -a`  - lists hidden files and directories
* `ls -l` - detailed lists





### Screen
* `control l or clear` - clears screen
* `q` - quits screen




### Removing
* `rm` - removes
* `rmdir` - removes directory if empty
* `rm -rf` - removes non-empty folder
>Note: Be careful when removing as files are difficult to recover (if at all)




### Git
* `git status` - what files have been modified
* `git log` - shows every commit with added information
* `git revert` - allows undo of specific commit
* `git reset` - undo specific commit and every commit after that
* `git rebase` - removes all commits and history
* `.gitignore` - ignored intentionally untracked files


### Git steps
1. `git init` - initialises repository
2. `git add` - stages files for next commit
3. `git commit -m""` - snapshot of staged changes
4. `git push` - pushes code to GitHub (after creating repo on GitHub)


>Note: git commit -m" " must have a message (ideally a specific description) . Git can commit all or a specific file. 




### Collaboration
(For file `owner`)
1. follow Git steps above
2. `Github` -> `Settings` -> `Collaborators` -> `Invite`




(for `collaborator` cloning the file)
1. `Git Clone` - in Terminal and chosen folder
2. Add `SSH Key` - from Github  repo
3. `Git Pull` - to pull files to local 
4. Continue with `Step 2` from `Git steps` above




### Collaboration using branches
* `git branch` + `directory name` - creates a branch
* `git checkout` + `directory name` - moves to alternative branch
* `git merge` - merges branches


>Note: merge command must occur on where you would like merge to occur e.g. main

>Note: must push/pull to corresponding branch e.g push/pull origin main




### Database
* `psql` - 
* `createdb` - creates database
* `dropdb` - removes database
* `\c` + `name of db` - creating database
* `\dt` - drops table


