__clone:__ it makes a exact copy of a remote repository 

__checkout:__ manage branches, navigate commit history, and restore files to a previous state

__*-b:__ You can create and switch to a new branch in one step using the -b flag: git checkout -b <new-branch-name>.

__status:__ Shows which files have changed or are staged (is shows the courrent status of your files in ln realtion to the changes that you made.)

__push:__ upload local repository changes to the remote repository,

__*-u:__ or --set-upstream Sets a persistent tracking relationship. This allows you to use shorthand git push or git pull in the future without specifying the remote or branch.

__pull:__ Retrieves the latest changes from the remote repository and integrates them into your local branch. It is used to keep your local environment up to date with work done by others.

__add:__  It tells Git that you want to include updates to specific files in the next commit. 

__add . :__ It gonna include all the changes of the workspace on the next commit.

__commit:__ to capture a snapshot of a project's currently staged changes and save them permanently to the local repository's history
(Every commit acts as a "checkpoint" or "save point," allowing you to track progress or revert to previous versions if needed)

__*-m:__ Commits staged changes with a descriptive one-line message. (_git commit -m "message"_)

__*-a:__ Automatically stages all modified and deleted files (but not new files) and commits them in one step. (git commit -a) 

__*-am:__ Modifies the most recent commit, allowing you to add forgotten changes or fix a typo in the message (git commit --amend):

__branch:__ Serves as a general-purpose __branch management__ tool. Its primary function is to create, list, rename, and delete branches within a repository.

__*-a:__  is to list all branches in your repository that your local Git client is currently aware of (git branch -a)

__*-d__  It is used to delete a branch. With a -d or -D option, <branch-name> will be deleted. You may specify more than one branch for deletion. If the branch currently has a reflog then the reflog will also be deleted. (git branch -d <branch-name> )

__merge:__ To integrate independent lines of development (branches) into a single branch. It unifies the histories of two or more branches, allowing developers to combine isolated features, bug fixes, or experiments back into a main codebase.