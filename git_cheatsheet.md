# Cheatsheet for Git commands

### Git commands for local repository

| Command                                  | Function                                                                |
|------------------------------------------|-------------------------------------------------------------------------|
|   git init                               |   Create an empty Git repository or reinitialize an existing one        |
|   git  status                            |   Show the working tree status                                          |
|   git add \<file> —dry-run               |   Add file contents to the staging area                                 |
|   git commit [-m \<message>]             |   Record changes to the repository                                      |
|   git diff [--staged]                    |   Show changes between commits                                          |
|   git log [--oneline] [--all] [--graph]  |   Show commit logs (history of past commits)                            |
|   git show [\<commit-hash>][:\<file>]    |   Show changes and past files                                           |
|   git restore [--staged]                 |   Discard changes in working directory or to unstage                    |
|   git reset --soft HEAD^                 |   Remove the previous commit from the history                           |
|   git revert [--no-edit] \<commit-hash>  |   Create a new commit which undoes the changes of the specified commit  |
|   git branch [-d] [\<new_branch_name>]   |   List, create, or delete branches                                      |
|   git checkout \<branch_name>            |   Switch to a branch                                                    |
|   git checkout \<commit-hash>            |   Go back to a past commit to check out                                 |
|   git checkout -b \<new_branch_name>     |   Create and switch to new branch                                       |
|   git merge \<branch_to_merge>           |   Merge the specified branch into the current branch (main)             |



### Git commands for linking local repository to remote repository

| Command                         | Function                                                                    |
|---------------------------------|-----------------------------------------------------------------------------|
|   git remote add origin \<URL>  |   Link a local repository and an online repository at the specified URL     |
|   git push -u origin main       |   Push local changes to the specified branch of the remote repository       |
|   git  push                     |   Update remote refs along with associated objects                          |
|   git pull                      |   Fetch changes from remote repository and integrate with local repository  |
|   git clone \<URL>              |   Clone a repository into a new directory                                   |