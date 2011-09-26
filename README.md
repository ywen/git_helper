A collection of bash scripts helping on different git tasks

## Scripts descriptions
* gitcreatebranch (branch-name) - It creates a branch with branch-name on the remote, and then track the branch locally
* delete_git_branch (branch-name) - It reverts what gitcreatebranch does (remove both remote and local branch)
* gitci - Do a git diff and git status, asking if the user wants to continue given the information being presented. If the suer says Yes, the script will commit and push the changes
