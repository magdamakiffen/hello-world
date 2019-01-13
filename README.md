# hello-world

Hello, Yes, just another hello world repository. Feels great doesn't it?

Try with cloned repositories.

Working with branches

git branch new-branch // creates a new branch

git checkout new-branch // changes into the new branch

git branch // shows the branches and on which branch we are

git branch -a // shows also the remote branches

git remote -v // shows the urls of the remote branches

git status // shows the current status of the repository

# Workflow

git branch new-branch

git checkout new-branch

//make changes to your code

git add -A

git commit -m "The changes that I made"

git push -u origin new-branch // Push changes to the new-branch on the remote repository (e.g. to run automated tests)

git checkout master // change to master branch

git pull origin master // pull in the changes that have been made meanwhile

git merge new-branch // merge the branches

git push origin master // push the changes to master

git branch -d new-branch // delete the branch locally

git push origin --delete new-branch // delete the remote branch
