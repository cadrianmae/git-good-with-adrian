# git-wth-adrian
## Pratical Instructions
### Part 1: Setup
1. Install git on your machine and create a github account
2. On local machine, create a directory `C:\users\<yourname>\dev\`
2. Navigate to the directory `C:\users\<yourname>\dev\`
1. Clone this repository to your local machine in current directory
1. Pull latest changes from upstream remote repository
    - If there is no upstream remote repository, add it with the following command
        - `git remote add upstream https://github.com/AdrianCapacite/git-good-wth-adrian.git`
    - Pull latest changes from upstream remote repository
      - `git pull upstream master`

### Part 2: Make your changes
1. Create a new branch with your name
3. Create a new file with your name containing the following:
    - Your name
    - Your favorite programming language
1. Add the file to the staging area
2. Commit the file to the local repository
1. Merge changes into the master branch
1. Push changes to the remote repository

### Part 3: Create a pull request
1. Log into github
2. Navigate to the upstream remote repository
3. Create a pull request
4. Wait for approval
5. 




[brandon1024](https://gist.github.com/brandon1024)/[GITCRASHCOURSE.MD](https://gist.github.com/brandon1024/14b5f9fcfd982658d01811ee3045ff1e)

# Git Syntax
## Basic Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git clone` | `git clone <repository_url>` | Makes a copy of a remote repository onto your local machine. |
| `git pull` | `git pull <remote> <branch>` | Copies and merges changes from the remote repository to your local repository. |
| `git push` | `git push <remote> <branch>` | Copies and merges changes from your local repository to the remote repository. |
| `git add` | `git add <file_name>` | Adds changes made in the working directory to the staging area. |
| `git commit` | `git commit -m "<commit_message>"`<br>`git commit -a` | Commits changes to the local repository. |

## Branching Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git branch` | `git branch` | Lists all branches in the local repository. |
| `git branch` | `git branch <branch_name>` | Creates a new branch in the local repository. |
| `git checkout` | `git checkout <branch_name>` | Shows the specified branch or commit in the working directory. |
| `git branch -d` | `git branch -d <branch_name>` | Deletes the specified branch in the local repository. |
| `git merge` | `git merge <branch_name>` | Merges the specified branch into the current branch. |
| `git rebase` | `git rebase <branch_name>` | Replays commits from the current branch on top of the specified branch. |

## More Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git status` | `git status` | Shows the status of the working directory and staging area. |
| `git log` | `git log` | Shows the commit history for the current branch. |
| `git diff` | `git diff` | Shows the difference between the working directory and the staging area. |
| `git revert` | `git revert <commit_hash>` | Reverts the specified commit. Keeps all commits|
| `git reset` | `git reset <commit_hash>` | Resets the current branch to the specified commit. Removes all commits after the specified commit. |


More git commands [https://training.github.com/downloads/github-git-cheat-sheet/](https://training.github.com/downloads/github-git-cheat-sheet/)
