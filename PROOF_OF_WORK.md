Name: Hamzah Ahsan  |  SAP ID: 56187  |  SECTION: SE 7-1 
    d7eb825 Merge pull request #1 from HamzahAhsan/development
    dfb22c0 fix: resolved merge conflict
    2baca1c fix: staging label
    9de5e6f feat: updated script with staging env
    12885db feat: initial commit with deploy script

Q1: Difference between Git (local tracking) and GitHub (cloud platform).
Ans: Git (Local Tracking): Git is a software that we install on our computer and it tracks changes locally. It works offline and we can commit, create branches and see history without internet.
GitHub (cloud platform): GitHub is a website that hosts our Git repositories on cloud. It is used for backup and for team collaboration. So Git is the tool and GitHub is the platform where we push our code.

Q2: Explain 3 architecture stages: Working Directory, Staging Area, Local Repository.
Ans: Working Directory is where we actually work and edit our files in our project folder. It is the current state of files before we tell Git to track them. Staging Area is the second stage, when we do git add, files go there. It is like a waiting area where we select which files we want to commit. Local Repository is the third stage, after git commit the files are saved permanently in .git folder. This is our local database of all commits.

Q3: Difference between git stash pop and git stash apply.
Ans: Both commands are used to bring back stashed code. git stash apply will apply the stash but it will still keep the stash saved in the stash list. So we can use it again if we want. git stash pop will apply the stash and also delete it from the stash list. I mostly use pop when I am sure I do not need that stash again.

Q4: Difference between git fetch and git pull.
Ans: Git Fetch downloads new data from remote like GitHub but it does not merge it with our current branch. It is safe because it does not change our working files. Git Pull does fetch plus merge automatically in one command. So pull directly updates our local branch with remote changes. Fetch is for checking first, pull is for direct update.

