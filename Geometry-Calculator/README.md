# git_assignment_HeroVired
# Geometry Calculator

Create a New Branch (“feature/circle-area”):

git checkout -b feature/circle-area

Stash Changes for Circle Area Feature:
git stash save "WIP: Area of Circle feature"

Verify that your working directory is clean:

git status

Create a New Branch (“feature/rectangle-area”):
git checkout -b feature/rectangle-area

Stash Changes for Rectangle Area Feature:
git stash save "WIP: Area of Rectangle feature"

Verify the working directory:

git status

Switch Back to Circle Area Branch:
git checkout feature/circle-area

Retrieve the stashed changes:

git stash list

git stash apply stash@{1}

Complete the circle area feature implementation and save the changes.

Commit and Push Circle Area Feature:
git add .

git commit -m "Implement circle area feature"

git push origin feature/circle-area

Switch Back to Rectangle Area Branch:
git checkout feature/rectangle-area

Retrieve the stashed changes:

git stash list

git stash apply stash@{0}

Complete the rectangle area feature implementation and save the changes.

Commit and Push Rectangle Area Feature:
git add .

git commit -m "Implement rectangle area feature"

git push origin feature/rectangle-area

Create Pull Requests:
Create pull requests for both branches targeting the ‘dev’ branch on GitHub.

Review and Merge to main






