# Git Syntax
## Basic Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git clone` | `git clone <repository_url>` | Makes a copy of a remote repository onto your local machine. |
| `git pull` | `git pull` | Copies and merges changes from the remote repository to your local repository. |
| `git push` | `git push` | Copies and merges changes from your local repository to the remote repository. |
| `git add` | `git add <file_name>` | Adds changes made in the working directory to the staging area. |
| `git commit` | `git commit -m "<commit_message>"` | Commits changes to the local repository. |
| `git checkout` | `git checkout <branch_name>` | Shows the specified branch or commit in the working directory. |

## Branching Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git branch` | `git branch` | Lists all branches in the local repository. |
| `git branch` | `git branch <branch_name>` | Creates a new branch in the local repository. |
| `git branch -d` | `git branch -d <branch_name>` | Deletes the specified branch in the local repository. |
| `git merge` | `git merge <branch_name>` | Merges the specified branch into the current branch. |

## More Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git revert` | `git revert <commit_hash>` | Goes back to a previous commit, preserving the changes made in the previous commit with a new commit. |
| `git reset` | `git reset <commit_hash>` | Goes back to a previous commit, destroying any changes made after the specified commit. |
| `git rebase` | `git rebase <branch_name>` | Reapplies changes from one branch to another. |
| `git tag` | `git tag <tag_name> <commit_hash>` | Labels a specific commit with a name, making it easier to reference in the future. |

## Other Commands
| --- | --- | --- |
| `git remote` | `git remote` | Lists all remote repositories. |
| `git remote add` | `git remote add <remote_name> <repository_url>` | Adds a remote repository to the local repository. |
| `git remote remove` | `git remote remove <remote_name>` | Removes a remote repository from the local repository. |
| `git status` | `git status` | Shows the status of the working directory and staging area. |
| `git log` | `git log` | Shows the commit history for the current branch. |
| `git diff` | `git diff` | Shows the difference between the working directory and the staging area. |