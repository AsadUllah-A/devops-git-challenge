1ed6720 Merge pull request #1 from AsadUllah-A/development
01996c7 fix: resolved merge conflict
8b614f6 fix: staging label
5a3fc9f feat: updated script with staging env
b8dbe97 feat: initial commit with deploy script

Q1: Difference between Git (local tracking) and GitHub (cloud platform).   
ANSWER : Git is a distributed version control system installed locally on your computer to track changes in source code. In contrast, GitHub is a cloud-based hosting service that allows you to manage Git repositories online. While Git works independently offline, GitHub facilitates collaboration by letting multiple developers push and pull code to a centralized remote server.

Q2: Explain 3 architecture stages: Working Directory, Staging Area, Local Repository.   
ANSWER : The Working Directory is where you actively edit and modify your files on your local file system. The Staging Area (or Index) is an intermediate space where you prepare and group specific changes before committing them. The Local Repository is where Git permanently stores the snapshots of your project (commits) along with its complete history.

Q3: Difference between git stash pop and git stash apply.   
ANSWER : Both commands restore stashed changes to your working directory, but they handle the stash list differently. git stash apply keeps the changes in the stash list, allowing you to apply them to multiple branches if needed. On the other hand, git stash pop applies the changes and immediately removes them from the stash list, which keeps your temporary storage clean.

Q4: Difference between git fetch and git pull.   
ANSWER : git fetch only downloads updates (commits, files, and refs) from a remote repository into your local Git system without merging them into your current working state. It allows you to review changes safely before applying them. git pull, however, is a combination of two commands: it first runs git fetch and then immediately runs git merge to integrate those downloaded changes directly into your active branch.
