Setting Up a Repository
Initialize a new Git repository:


git init
Clone an existing repository:

bash

git clone <repository_url>
Staging and Committing Changes
Check status of files (to see changes):

bash

git status
Add a file to the staging area:

bash

git add <file_name>
Add all files to the staging area:

bash

git add .
Commit changes with a message:


git commit -m "your commit message"
Working with Branches
Create a new branch:


git branch <branch_name>
Switch to a branch:


git checkout <branch_name>
Create and switch to a new branch:


git checkout -b <branch_name>
Merging and Updating
Merge a branch into the current branch:


git merge <branch_name>
Pull latest changes from remote repository:


git pull
Working with Remotes
Add a remote repository:


git remote add origin <remote_repository_url>
Push changes to the remote repository:


git push origin <branch_name>
Undo Changes
Unstage a file (remove from staging area):

bash
Copy code
git reset <file_name>
Revert the latest commit:

bash
Copy code
git revert <commit_hash>
