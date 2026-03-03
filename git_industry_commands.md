## GIt configuration commands

## commmand name: git config --global user.name
**syntax:**
git config --global user.name "username"
## purpose:sets the global username for git commits on your system.
**screenshot:**
![git config username](screenshots/command11.png)



## commmand name: git config --global user.email
**syntax:**
git config --global user.name "e-mail"
## purpose: Sets your global Git email,which will be shown in commit author info.
**screenshot:**
![git config useremail](screenshots/command12.png)



## commmand name: git config --list
**syntax:**
git config --global user.name "username"
## purpose:Displays current Git configuration values including global, local and sysytem
**screenshot:**
![git config list](screenshots/command13.png)



## commmand name: git config --unset
**syntax:**
git config --global user.name "username"
## purpose:Removes a configuration value, useful if you set wrong details.
**screenshot:**
![git config unset](screenshots/command14.png)



## 2 Repository setup commands



## commmand name: git init
**syntax:**
git init
## purpose:Initializes a new Git repository in the current directory by creating a .git folder to track project history.
**screenshot:**
![git init](screenshots/command21.png)




## commmand name: git clone
**syntax:**
git clone repository-url
## purpose:Creates a local copy of an existing remote repository along with its complete commit history.
**screenshot:**
![git clone](screenshots/ommand22.png)




## commmand name: git clone --branch
**syntax:**
git clone --branch branch-name repository-url
## purpose:Clones only a specific branch from the remote repository instead of the default branch.
**screenshot:**
![git branch](screenshots/command23.png)






## commmand name: git clone --depth
**syntax:**
git clone --depth number repository-url
## purpose:Performs a shallow clone by downloading limited commit history to make cloning faster and lighter.
**screenshot:**
![git depth](screenshots/command24.png)


## 3 repository status and information commands


## commmand name: git status
**syntax:**
git status
## purpose:Shows the current state of the working directory including modified, staged and untracked files.
**screenshot:**
![git status](screenshots/command31.png)



commmand name: git log
syntax:
git log
purpose:Displays complete commit history including commit id, author, date and message.
screenshot:
![git log](screenshots/command32.png)



commmand name: git log --oneline
syntax:
git log --oneline
purpose:Shows commit history in a short single-line format for quick viewing.
screenshot:
![git oneline](screenshots/command33.png)



commmand name: git log --graph
syntax:
git log --graph
purpose:Displays commit history in graphical tree format showing branch structure and merges.
screenshot:
![git graph](screenshots/command34.png)



commmand name: git show
syntax:
git show commit-id
purpose:Displays detailed information about a specific commit including changes made.
screenshot:
![git show](screenshots/command35.png)



commmand name: git diff
syntax:
git diff
purpose:Shows differences between modified files and the last committed version.
screenshot:
![git diff](screenshots/command36.png)



commmand name: git diff --staged
syntax:
git diff --staged
purpose:Displays differences between staged files and the last commit before committing.
screenshot:
![git staged](screenshots/command37.png)



commmand name: git blame
syntax:
git blame filename
purpose:Shows who last modified each line of a file along with commit details.
screenshot:
![git blame](screenshots/command38.png)



commmand name: git reflog
syntax:
git reflog
purpose:Displays history of all HEAD movements including commits, checkouts and resets.
screenshot:
![git reflog](screenshots/command39.png)



commmand name: git shortlog
syntax:
git shortlog
purpose:Summarizes commit history grouped by author showing contribution count.
screenshot:
![git shortlog](screenshots/command310.png)




## 4 File tracking commands



commmand name: git add
syntax:
git add filename
purpose:Adds a specific file from working directory to staging area before committing.
screenshot:
![git add file](screenshots\command3_11.png)

commmand name: git add .
syntax:
git add .
purpose:Adds all modified and new files in the current directory to the staging area.
screenshot:
![git add .](screenshots\command3_11.png)

commmand name: git add -p
syntax:
git add -p
purpose:Allows staging changes interactively by selecting parts of modifications instead of the entire file.
screenshot:
![git add -p](screenshots\command3_11.png)

commmand name: git restore
syntax:
git restore filename
purpose:Discards changes in the working directory and restores file to last committed version.
screenshot:
![git restore](screenshots\command3_11.png)

commmand name: git restore --staged
syntax:
git restore --staged filename
purpose:Removes a file from staging area without deleting changes in working directory.
screenshot:
![git restore --staged](screenshots\command3_11.png)

commmand name: git rm
syntax:
git rm filename
purpose:Removes a file from both working directory and Git tracking system.
screenshot:
![git rm](screenshots\command3_11.png)

commmand name: git mv
syntax:
git mv oldfilename newfilename
purpose:Renames or moves a file while keeping Git history intact.
screenshot:
![git mv](screenshots\command3_11.png)






## 5 Commit Commands



commmand name: git commit
syntax:
git commit
purpose:Creates a new commit with the staged changes.
Opens the default text editor to write a commit message.
screenshot:
![git mv](screenshots\command3_11.png)


commmand name: git commit -m
syntax:
git commit -m "commit message"
purpose:Creates a commit with a message directly from the command line (without opening editor).
This is the most commonly used commit command in industry.
screenshot:
![git mv](screenshots\command3_11.png)


commmand name: git commit --amend
syntax:
git commit --amend
purpose:Modifies the most recent commit.
Add missed fil
correct small mistakes
screenshot:
![git mv](screenshots\command3_11.png)


commmand name: git commit --no-edit
syntax:
git commit --amend --no-edit
purpose:Amends the previous commit without changing the existing commit message.
Useful when you forgot to add a file but message is correct.
screenshot:
![git mv](screenshots\command3_11.png)