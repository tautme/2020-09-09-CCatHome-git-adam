# 2020-09-09-CCatHome-git-adam
Carpentry Con at Home Git workshop Part 2

- git clone <url>
 - make sure you are not in another repo
 - just like git init do only one per repo

- `git branch <branch_name>`: create a new branch where you are (`HEAD`)
- `git checkout <branch_name>`: move to another branch
 - `git switch <branch_name>`: for windows

- shortcuts for creating branches, will create and move to them in 1 go: 
	- `git checkout -b <branch_name>  
	- `git swith -c <branch_name> 
- `git branch -d <branch_name>`: this will delete <branch_name> on your local computer 
- `git fetch --prune`: will update your local git tree with the remote 
	- the prune will also delete references to branches that were deleted on the remote

- Each pull request si independent
