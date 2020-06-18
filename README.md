Emiliano's steps

* Created repo from github 
* Cloned it to local machine
* Made sure that git file was in the repo, which it was because when repo is created in github, it automatically gets one.
* Added .gitignore file using `$vim .gitignore` and added:
    > node_modules
    > .DS_Store
    This is done so that huge files in nodemodules won't be pushed to github and unecessarlily be clone into another contributor's local machine. 
                    **1st COMMIT**
* Added these steps
* Learned about how to see the unstaged changes in vim with:
    `git diff`
* Git diff is a tool to use when comparing differences before committing 
                    **2nd COMMIT**

**To unstage a unstaged file**
* `git reset HEAD <file>`
After typing this, I went ahead and staged lines 17-18, then used that command to unstage and this went back to green lines. Cool.