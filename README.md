# Helpers

## Command Line

* Change folder:
    * `cd FOLDER_NAME`
* Change to folder above current folder:
    * `cd ..`
* Change to HOME folder:
    * `cd ~`
* Show file contents:
    * `ls -ltr`
* Create new folder:
    * `mkdir FOLDER_NAME`
* Open VSCode for current folder:
    * `code .`


## GIT

* Clone a new repository:
    * `git clone git@ORIGIN_URL`
* Create a new branch
    * `git checkout -b MY_BRANCH_NAME`
* Switch to an existing branch
    * `git checkout BRANCH_NAME`
* Get status of current branch
    * `git status`
* Get latest info from Origin (Github)
    * `git fetch --prune`
* Get current local branches
    * `git branch`
* Get all branches
    * `git branch -a`
* Add files to commit
    * `git add FILE_PATTERN`
    * Add everything - `git add .`
    * Add everything in "CSS" folder - `git add css/`
    * Add only "index.html" file - `git add index.html`
* Commit
    * `git commit -m "Example commit message"`
* Push commits to Origin
    * `git push`