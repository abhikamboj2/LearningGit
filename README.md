Ola Amigos 
1. Git Initialization (git init)
What It Does:
Initializes a new Git repository in your current directory. It creates a .git folder that tracks your project.
Command:

git init

Use Case:
Use this when starting a new project to set it up as a Git repository.
---------------------------------------------------------------------------------------------------------------------------
3. Adding Changes (git add)
What It Does:
Stages changes (modified, deleted, or new files) for the next commit. Files must be staged before committing.
Command:

Edit

git add <file>
git add .  # Stages all changes in the current directory
Use Case:
Use this to prepare specific changes for a commit while leaving others untracked.
---------------------------------------------------------------------------------------------------------------------------
4. Committing Changes (git commit)
What It Does:
Saves the staged changes into the repository's history with a message explaining what was done.
Command:


git commit -m "Your commit message here"

Use Case:
Use this to create a checkpoint in your project’s development.
---------------------------------------------------------------------------------------------------------------------------
5. Git Restore (git restore)
What It Does:
Discards changes in the working directory or un-stages changes from the staging area.
Commands:

git restore <file>  # Discards changes in the working directory
git restore --staged <file>  # Un-stages changes

Use Case:
Use this to revert unwanted changes or un-stage changes you don’t want to commit yet.
---------------------------------------------------------------------------------------------------------------------------
6. Stashing Changes (git stash)
What It Does:
Temporarily saves your uncommitted changes so you can work on something else or switch branches cleanly.
Commands:

git stash       # Save changes to the stash
git stash list  # View all stashed changes
git stash pop   # Apply and remove stashed changes

Use Case:
Use this to save your work temporarily when switching contexts.
---------------------------------------------------------------------------------------------------------------------------
7. Git Push (git push)
What It Does:
Uploads your local commits to a remote repository (e.g., GitHub).
Command:

git push origin <branch>

Use Case:
Use this to share your work or collaborate with others by updating the remote repository.
---------------------------------------------------------------------------------------------------------------------------
8. Git Pull (git pull)
What It Does:
Fetches changes from a remote repository and merges them into your local branch.
Command:

git pull origin <branch>
Use Case:
Use this to ensure your local branch is up-to-date with the remote repository.
---------------------------------------------------------------------------------------------------------------------------
9. Adding Remote Repositories (git remote add origin)
What It Does:
Links your local repository to a remote repository (e.g., GitHub).
Command:

git remote add origin <remote-repository-URL>

Use Case:
Use this to set up collaboration by associating your local project with a GitHub repository.
---------------------------------------------------------------------------------------------------------------------------
10. Branching in Git (git branch)
What It Does:
Creates and manages branches in your project, allowing you to work on features or bug fixes independently.
Commands:

git branch <branch-name>  # Create a new branch
git checkout <branch-name>  # Switch to a branch
git branch -d <branch-name>  # Delete a branch

Use Case:
Use this to work on new features without affecting the main branch.
---------------------------------------------------------------------------------------------------------------------------
11. Forking a Repository
What It Is:
Creates a copy of someone else’s repository under your GitHub account. Forking is specific to GitHub, not Git.
Use Case:
Use this to contribute to open-source projects by making changes in your copy and submitting them via pull requests.
---------------------------------------------------------------------------------------------------------------------------
13. Rebasing (git rebase)
What It Does:
Reapplies commits from one branch on top of another, creating a cleaner commit history.
Command:

git rebase <branch-name>

Use Case:
Use this to integrate changes from one branch into another with a cleaner, linear history.
---------------------------------------------------------------------------------------------------------------------------
14. Additional Key Commands
git status: Shows the status of your working directory and staging area.

git status

git log: Displays commit history.

git log

git clone: Creates a copy of an existing repository.

git clone <repository-URL>
---------------------------------------------------------------------------------------------------------------------------
Summary
Mastering these basics gives you a solid foundation for working with Git and GitHub.
These commands allow you to manage your code, collaborate with others, and maintain a clean project history effectively.
Now you’re ready to apply this knowledge to real-world projects!
