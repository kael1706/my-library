## Chapter 1. Basic commands
### `git init`
Initialize a local repository

### `git clone <url_of_repository>`
Download a copy of the repository

### `git status`
View the status of your local repository

### git add
Save changes to the local registry
-	`git add .`
Consider changes of modification and creation. In advanced versions it takes into account deletion changes
-	`git add -A`
Consider changes of modification and creation, and elimination

### `git commit -m <"msg">`
Packages local changes registered to a save point. The name of the save point is the message, and each save point has an id. It is important that messages provide effective information.

### `git push`
It is used to send information to the remote repository. It is usually used to send save points to remote branches. When the branch is not specified, the remote branch that has connection to the current local branch is used.

- `git push <branch_name>`
I upload the changes to the specified branch
	- `git push origin --delete <branch_name>`
delete a remote branch

