# Git

Git is a distributed version control system (DVCS) that allows multiple users to work on the same code, while keeping track of changes. The system allows users to make synced copies on their computers, which provides security if the main server fails.

## Git Features

Git has many features includeing:

 - Snapshots - Git stores versions of the project allowing one to restore to a previous version.
 - Local Ops - A user can store a synced version of the project on their local pc, which removes the need to wait for the server.
 - Tracking changes - All changes to the project are tracked and can be checked by the user.
 - Corruption detection - Git will detect file corruption and data loss.

## Customisation

These commands help link you to your commits:

    - git config --global user.name "Jane Smith"

    - git config --global user.email "example@email.com"

## Tracking and saving changes

    - "git status" 
Tells you which files have been modified

    - "git add filename"
Adds 'filename' to staging

    - "git add *"
Adds all files to staging

    - "git commit -m "made change..."
Commits changes with comment

    - "git commit -a"
Commits all files.

    - "git push origin master"
Pushes all changes from the local 'master' to the 'origin' server

*"git stash" can be used to temporarily hide changes then "git stash apply" can be used to retrieve them.*