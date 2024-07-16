# git_assignment_HeroVired
# Git LFS Integration

1. Install Git LFS:
Download it directly from the official Git LFS website https://git-lfs.com/

2. Create a new GitHub repository 'git_assignment_HeroVired' in the GitHub website

3. Clone the repository on local machine:
git clone <ssh_repository_url>

4. Change the directory to our repository directory 'git_assignment_HeroVired':
cd <repository_name>

5. Checkout and create a branch 'lfs':
git checkout -b <branchname>

6. Initialize Git LFS in Your Repository: 
Run the following command to initialize Git LFS:
git lfs install

7. Add the large file extension in order to track it
git lfs track "*.pdf"

8. Now making sure .gitattributes is tracked:
git add .gitattributes

9. Add the large file
git add <large_file_name_with_extension>

10. Commit the changes:
git commit -m "Added large file using LFS"

11. Push the changes to remote repository:
git push -u origin <branchname>

12. Clone on Another Machine: Clone the repository:
git clone <ssh_repository_url>

13. Open the file and verify that the file is downloaded correctly



