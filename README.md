# Project01
Good stuffs reside here. Just my first
Trying some more changes.
## GIT Crash Course
Watching tutorial via youtube also through copilot.
Git is the version control system VCS, github hosts repositories

## 
git codes:

git --version

##
git clone
To clone a repository from a remote source (like GitHub) to your local machine.
git clone https://github.com/Slyall01/Project01.git


## 
git status
To show the current status of your working directory and staging area, including tracked and untracked files.
Output: Lists modified files, untracked files, and files staged for commit.

##
git add .
To add all changes in your working directory to the staging area.
The . (dot) signifies all files and changes. You can also add specific files:
git add filename.txt


##
git commit -m "write your message here"
To commit the changes in the staging area with a descriptive message.
git commit -m "Add feature X"
Note: The message should describe the changes you made.

##
git commit -am "write your message"
To add modified files and commit changes in one step (skips the staging area). Only works for files already tracked by Git.
git commit -am "Update README with new information"


##
git push
To push the committed changes from your local repository to the remote repository.
Note: This command pushes changes to the default remote and branch.


##
git push origin main
To push committed changes to a specific branch (main) on the remote repository (origin).


##
git init
To initialize a new Git repository in your current directory.
Note: This creates a .git directory in your current folder, which is now tracked by Git.


##
git remote add origin https://.../.....git
To add a remote repository (e.g., on GitHub) to your local repository.
git remote add origin https://github.com/Slyall01/project02.git


##
git push -u origin main
To push the committed changes to the main branch on the origin remote and set upstream tracking.
Note: The -u flag sets the upstream branch for the local branch, so future git push commands can be used without specifying the branch.


##
git pull
Pull changes from the default remote and branch
Automatic Merge: git pull will automatically attempt to merge the changes. If there are conflicts, you will need to resolve them manually.

git pull origin main
Pull changes from a specific branch (e.g., main) of the remote repository (e.g., origin)



#Change directory - from project01 to project 02
cd ../Project01

Branching & Merging

