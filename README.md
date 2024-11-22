# this is a playground repository for cohort 5

Session #3: Git & GitHub

Initializing a Repository
Create a new Git repository: git init
Create a new branch called main while initializing: git init -b main
Cloning a Repository
Clone an existing repository: git clone <repository_url>
Clone and rename the directory: git clone <repository_url> <new_directory_name>
Tracking Files
Check the status of your repository: git status
Track a new file: git add <file_name>
Track all files: git add -A
Committing Changes
Commit staged changes with a message: git commit -m "Your commit message"
Commit without -m for a detailed message: git commit (Enter the message in the editor)
Remote Repositories
Check remotes: git remote -v
Add a remote repository: git remote add origin <repository_url>
Show details of a remote: git remote show origin
Fetching, Pulling, and Pushing
Fetch updates from the remote repository: git fetch origin
Fetch and merge updates (pull): git pull origin <branch_name>
Pull with rebase to update local branch: git pull –rebase origin <branch_name>
Push changes to the remote repository: git push origin <branch_name>
Branching
List all branches: git branch -v
Create a new branch: git branch <new_branch_name>
Switch to a branch: git checkout <branch_name/commit id>
Create and switch to a branch: git checkout -b <new_branch_name>
Merge a branch into the current branch: git merge <branch_name>
Delete a branch: git branch -d <branch_name>
Branching Workflow
Switch to a new branch: git checkout -b feature-branch
Make changes, stage, and commit:
git add -A
git commit -m "Feature updates"
Push the branch: git push origin feature-branch

Merge Conflicts
If conflicts occur, Git will pause and show conflict markers (<<<<, =====, >>>>) in affected files. Manually resolve the conflict by editing the file. 
Then: git add <file_name>
git commit
