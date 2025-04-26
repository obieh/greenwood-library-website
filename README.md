# Greenwood-library-website
This project demonstrates Team collaboration enhancing Green wood community website

## Create a Repository on Github
* Login to your github account and create a repo named greenwood-library-website

![create-repo](./img/create-repo-in-github.png)

## Clone the Repo to your local system 
* Change directory to the project directory and clone the repository you just created.

* `cd projects`
* `git clone <repo url>`

![clone](./img/capeston-clone.png)

* run `code .` to open the project directory in vscode editor

### Create the files below on vscode editor

* home.html
* about_us.html
* events.html
* contact_us.html

![html files](./img/files-in-vscode.png)


### Stage, Commit and push chnages to main branch(The team.s existing code base for the website)

#### Before staging run `git status` to verify branch and see untracked files(changes)

![stage](./img/first-staging.png)

#### Run `git add .` to stage the new created files

![first-add](./img/first-add.png)

### Run `git commit -m'commit message'` to commit the changes.

![first-commit](./img/first-commit.png)

### Run `git push origin main` to push changes to remote main branch.

![first push](./img/first-push.png)

## Morgan's Work(Adding Book Reviews)

1. Create a branch named add-book-reviews for Morgan
* Run `git checkout -b add-book-reviews` to create and switch to the branch

![add-branch](./img/created&switch-to-add.png)


* Add book_reviews.html file to the project root folder

![add-book-review-page](./img/add-book-review-file.png)



* Run `git add book_reviews.html` on the terminal to stage the chnages made on the book_reviews.html


![stage-review](./img/stag-book-reviews-file.png)

* Run `git commit -m'commit message'` to commit the changes made(Recall that all these is Morgan's work on the add-book-reviews branch)

![stage-book](./img/commit-book-reviews.png)



* Run `git push origin add-book-reviews` to push changes from local to remote add-book-reviews branch


![push](./img/push-book-reviews-to-remote.png)



## Create a Pull Request for Morgan's Work in the add-book-reviews Branch


### Go to your github account Select the add-book-reviews branch.

![gui-switch](./img/switch-to-add-gui.png)


### Click on 'Contribute' then click 'Open pull request'

![contribute](./img/contribute-open-pull-gui.png)

### Before creating a pull request for Morgan's contribution be sure to review the difference from the main branch and ascertain everything is okay!
* Review changes made by Morgan

![diff](./img/diff-btw-main-&reviews-gui.png)

*  Proceed to add description and  create the Pull request for Morgan's contribution 

![](./img/add-desc-create-PR-review-gui.png)

* After creating the pull request and there is no conflick with the base branch. Click on 'merge pull request' to merge Morgan's pull request.

![](./img/if-no-conflict-merge-PR-review-gui.png)

### Git will require you to confirm merge before actual merging the PR with main

* Write a commit message and click confirm merge

![](./img/write-comit-msg-confirm-merge-reviews-gui.png)

### Git performs merging and confirm that PR has been merged successfully


![commit-merge](./img/PR-success-merge-review-gui.png)


## Jamie's Work 'Updating Events page'

* On the terminal run `git checkout -b update-events` to create and switch to jamie's branch update-events

![update](./img/create&switch-to-update-branch-term.png)

### Pull the changes merged to main into Jamie's branch

* Run `git pull origin main` while in Jamie's branch(update-events). This will fetch and merge the latest changes to Jamie's local repo.

![pullevent](./img/git-pull-into-updateevents-branch-tem.png)

* Recall that Jamie's branch is now up to date from after the pull from main. Now add events.html file which is jamie's contribution.

![updatehtml](./img/update-eventspage-on%20event-branch.png)


 Run `git status` to view untracked / Modified files

 ![](./img/git-status-afta-working%20on%20eventpage.png)

* Run `git add evets.html` to stage the event.html file changes


![add-event](./img/git-add-events-page.png)


* Run `git status again to verify the file have been staged.

![](./img/git-status-afta-adding-events-page.png)

### File color in green signifies the events.html file have been staged ready to commit.

* Run `git commit -m'commit message'` to commit the changes to local repo branch.

![](./img/first-git-commit-events-branch.png)

* Run `git push origin update-events` to push the changes to remote update-events branch.

![](./img/push-events-to%20remote-term.png)


## Create a Pull Request to merge Jamie's Contribution which has just been pushed to his remote branch(update-events)

### Go to your github account Select the update-events branch.

![event-gui](./img/switch-to-update-branch4PR-gui.png)


### Click on 'Contribute' then click 'Open pull request'

![contribute](./img/contri-open-PR-update-gui.png)

### Before creating a pull request for Jamie's contribution be sure to review the difference from the main branch and ascertain everything is okay!

* Review changes made by Jamie

![diff](./img/diff-btw-main-update-gui.png)


*  Proceed to add description and  create the Pull request for Jamie's contribution 

![](./img/add-desc-create-PR-gui.png)


* After creating the pull request and there is no conflick with the base branch. Click on 'merge pull request' to merge Jamie's pull request.

![no-conflict](./img/no-conflict-click-merge-update-gui.png)


### Git will require you to confirm merge before actual merging the PR with main

* Write a commit message and click confirm merge

![confirm](./img/commit-msg-confirm-merge-update-gui.png)


### Git performs merging and confirm that PR has been merged successfully

![](./img/PR-success-merge-update-gui.png)
