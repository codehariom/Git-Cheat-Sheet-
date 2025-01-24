### 1. Install Git with Homebrew on Mac OS
``` 
$ brew install git
``` 
### 2 .git	Install Command for Linux

```
$ sudo apt-get install 
```
### 3 .git	Install Command for Linux
Shows the current version of your Git
```
$ git –version
```	
### 4. Set your username globally.

```
git config –global user.name “Your Name”
```
 ### 5. Set your email globally.

 ```
 git config –global user.email “youremail@example.com”	
 ```
### 6. Set to display colored output in the terminal
```
git config –global color.ui auto –
```
### 7. Initializes a new Git repository in the current directory.

```
git init
```

### 8. Creates a new Git repository in the specified directory.
```
git init <directory>
```
### 9. this Clones a repository from a remote server to your local machine.
```
git clone <repository_url>
```
### 10. Clones a specific branch from a repository.
```
git clone –branch <branch_name> <repository_url>
```
### 11. Adds a specific file to the staging area.
```
git add <file>	
```
### 12. Adds all modified and new files to the staging area.

```
git add . or git add –all	
```
### 13. Shows the current state of your repository, including tracked and untracked files, modified files, and branch information.
```
git status	
```
### 14. Displays ignored files in addition to the regular status output.
```
git status –ignored	
```
### 15. # Clone and create a local copy of a remote repository
```
git clone <url>
```
### 16. # Show a summary of your Git configuration settings
```
git config --list
```
### 17. # Create a Git command alias
```
git config --global alias.<shortcut> <command>

```
### 18. Clones a specific branch from a repository.
```
git clone –branch <branch_name> <repository_url>	
```
### 19. # Remove files from working tree and staging area
```
git rm <file(s)>
```
### 20. Move or rename a file
```
git mv <old_file> <new_file>
```
### 21. Shows the changes between the working directory and the staging area (index).
```
git diff	
```
### 22. Displays the differences between two commits.
```
git diff <commit1> <commit2>	
```
### 23. Display the difference between the current directory and the last commit
```
git diff HEAD	
```
### 24.Creates a new commit with the changes in the staging area and opens the default text editor for adding a commit message.

```
git commit	
```
### 25. Creates a new commit with the changes in the staging area and specifies the commit message inline.

```
git commit -m “<message>” or git commit –message “<message>”	
```
### 26. Commits all modified and deleted files in the repository without explicitly using git add to stage the changes.

```
git commit -a or git commit –all	
```

### 27. Creates a new note and associates it with an object (commit, tag, etc.).

```
git notes add	
```
### 28. Restores the file in the working directory to its state in the last commit.

```
git restore <file>	
```
### 29. Moves the branch pointer to a specified commit, resetting the staging area and the working directory to match the specified commit.
```
git reset <commit>	
```
### 30. Create a new commit in a Git repository with a specific message to indicate a new feature commit in the repository.

```
git commit -m “feat: message”	
```
### 31. Create a new commit in a Git repository with a specific message to fix the bugs in codebases

```
git commit -m “fix: message”	
```
### 32. Create a new commit in a Git repository with a specific message to show routine tasks or maintenance.
.
```
git commit -m “chore: message”	
```
### 33. Create a new commit in a Git repository with a specific message to change the code base and improve the structure.

```
git commit -m “refactor: message”	
```
### 34. Create a new commit in a Git repository with a specific message to change the documentation.

```
git commit -m “docs: message”	
```
### 35. Create a new commit in a Git repository with a specific message to indicate test-related changes.

```
git commit -m “test: message”	
```
### 36. Create a new commit in a Git repository with a specific message to indicate performance-related changes.

```
git commit -m “perf: message”	
```
### 37. Create a new commit in a Git repository with a specific message to indicate the changes related to the build process.

```
git commit -m “build: message”	
```
### 38. Create a new commit in a Git repository with a specific message to indicate the changes related to revert a previous commit.

```
git commit -m “revert: message”	
```
### 39. Lists all branches in the repository.

```
git branch	
```
### 40. Creates a new branch with the specified name.

```
git branch <branch-name>	

```
### 41. Deletes the specified branch.

```
git branch -d <branch-name>	
```
### 42. Lists all local and remote branches.

```
git branch -a	
```
### 43. Lists all remote branches.

```
git branch -r	
```
### 44. Switches to the specified branch.

```
git checkout <branch-name>	
```
### 45. Creates a new branch and switches to it.

```
git checkout -b <new-branch-name>	
```
### 46. Discards changes made to the specified file and revert it to the version in the last commit.
```
git checkout — <file>	
```
### 47. Displays the commit history of the current branch.

```
git log	
```
### 48.Displays the commit history of the current branch in short.
```
git log	--oneline
```
### 48.Displays the commit history branch 
```
git log	--graph
```
### 49. # Create a new branch

```
git branch <branch_name>

```
### 50. Displays the commit history of all branches.

```
git log –all	
```
### 51. Stashes the changes in the working directory, allowing you to switch to a different branch or commit without committing the changes.

```
git stash	
```
### 52. Lists all stashes in the repository.

```
git stash list	
```
### 53. Applies and removes the most recent stash from the stash list.

```
git stash pop	
```
### 54. Removes the most recent stash from the stash list.

```
git stash drop	
```
### 55.  List all tags

```
git tag

```
### 56.  Create a new tag at a specific commit

```
git tag <tag_name> <commit_id>

```
### 57.  Create an annotated tag with a message

```
git tag -a <tag_name> -m "tag message"

```

### 58.  Delete a specific tag

```
git tag -d <tag_name>

```
### 59. # Show information about a specific tag

```
git show <tag_name>

```
### 60. Creates a new commit that undoes the changes introduced by the specified commit.

```
git revert <commit>	
```
### 61. Undoes the changes introduced by the specified commit, but does not create a new commit.

```
git revert –no-commit <commit>	
```
### 62. Reapplies commits on the current branch onto the tip of the specified branch.

```
git rebase <branch>	
```
### 63.Retrieves change from a remote repository, including new branches and commit.

```
git fetch	
```
### 64. Retrieves change from the specified remote repository.

```
git fetch <remote>	
```
### 65. Fetches changes from the remote repository and merges them into the current branch.

```
git pull	
```
### 66. Fetches changes from the specified remote repository and merges them into the current branch.

```
git pull <remote>	
```
### 67. Pushes local commits to the remote repository.

```
git push	
```

### 68. Pushes local commits to the specified remote repository.

```
git push <remote>	
```
### 69. Pushes local commits to the specified branch of the remote repository.

```
git push <remote> <branch>	
```
### 70. Pushes all branches to the remote repository.

```
git push –all	
```
### 71. Lists all remote repositories.

```
git remote	
```
### 72. Adds a new remote repository with the specified name and URL.

```
git remote add <name> <url>	
```
### 73. # Remove a remote repository
```
git remote rm <remote_name>

```
### 74. # Fetch updates from all remote repositories

```
git remote update

```
### 75. # Rename a remote repository

```
git remote rename <old_name> <new_name>

```
### 75. # List all files tracked by Git
```
git ls-files
```