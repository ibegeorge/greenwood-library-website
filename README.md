# How I went about this project
## Firstly, I went on "github.com", logged in (because I have an account created)
## and then, I created a Repository named "greenwood-library-website" initialised
## with a ReadMe file.

## Open Terminal
## Create a project folder for this project - "mkdir greenwood-library-website"
## Enter the new directory -  "cd greenwood-library-website"
## Go back to GitHub and copy the GitHub HTTPS Url for that repository to clone ot
## Clone repository by Entering "git clone + GitHub Url"
## List the items in the repository to check whether you have cloned the repository
## in that folder

## Enter the cloned directory - cd greenwood-library-website
## Open in VS Code - Enter code . in the terminal

## On VS Code , create the following files : home.html , about_us.html, events.html,
## contact_us.html and add any random text to each of those files and save them

## Stage files for Commit Run - git add . 

## Commit files : git commit -m "setup codebase with required files"
## Push main: git push origin main

## To Simulate Morgan's Flow, I :

1. Created a Branch for Morgan : git checkout -b "add-book-reviews"
2. Created a New File called "book_reviews.html" and Add random text to it, save file
3. Staged the file for commit by running : git add book_reviews.html on the terminal
4. Commited the changes by running: git commit -m "added book reviews section"
5. Pushed branch to GitHub by running: git push origin add-book-reviews
6. On the Github repository, switched to the add-book-reviews branch and Created a Pull Request after reviewing changes and giving the Pull Request a suitable title.
7. After creating the PR, it should be visible on the GitHub repository, where I was able to merge back with the main repository.

## Simulating Jamie's Work Flow: 

## Switch back to the main branch - git checkout main
## Create a branch for Jamie's work called "update-events" - git checkout -b "update-events"
## Pull the latest changes from the main branch into update-events branch by running git pull origin main
## Add New Events to the events.html file ( anything random at all) and save file
## Stage file for commit by running - git add events.html
## Commit file by running - git commit -m "updated events page"
## Push Jamie's branch by running - git push origin update-events
 
## On the GitHub repository switch to the update-events branch and Create a New Pull Request
## Merge Pull Request 