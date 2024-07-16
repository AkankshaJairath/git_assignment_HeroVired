# git_assignment_HeroVired
# Calculator Plus

Create a ‘dev’ Branch and Add Code:
Clone the repository to your local machine:

git clone <ssh_repository_url>

Create a new branch named “dev” and switch to it:

git checkout -b dev

Add the provided code snippet to a Python file (e.g., CalculatorPlus.py).

Implement the Square Root Feature:
Uncomment the square_root function in Calculator class.

Complete its implementation to calculate the square root of a number using math.sqrt(x).

Test the Square Root Feature:
Uncomment the relevant section in if name == "main": block.

Test the square root feature by providing a value for num3.

Merge ‘dev’ Branch with Main

Create a New Branch (“feature/sqrt”):

Create a new branch for the square root feature:

git checkout -b feature/sqrt

Add the Square Root Code:
Implement the square root feature in Calculator class.

Commit the changes to the feature/sqrt branch.

Handle Critical Bug in Main:
Switch back to the dev branch:

git checkout dev

Fix the bug in the divide function:

Commit the bug fix.

Create a Pull Request (“feature/sqrt” into “main”):
Push changes to GitHub:

git push origin feature/sqrt

Create a pull request targeting the main branch.


Merge “feature/sqrt” into ‘dev’: Once the pull request is approved, merge the feature/sqrt branch into dev.

Test in ‘dev’ and Merge into ‘main’:

Test the application in the dev branch.

Merge dev into main.

