P4: GitHub README and Version Tags
Aim: To create a README file, upload a Git repository to GitHub, and create version tags.

Procedure:

Step 1: Create OutputREADME.md

Step 2: Stage and commit README
git add README.md
git commit -m "Add project README"


Step 3: Create a GitHub repository
1. Open GitHub.
2. Click New Repository.
3. Enter the repository name portfolio.
4. Click Create Repository.
Step 4: Connect the local repository to GitHub
git remote add origin https://github.com/USERNAME/portfolio.git


Step 5: Push the project
git branch -M main
git push -u origin main


Step 6: Create a version tag
git tag -a v1.0 -m "First release"


Step 7: Push the tag to GitHub
git push origin v1.0


Result: Successfully created a OutputREADME file, uploaded the repository to GitHub, and created a version tag.

Terminal:

<img width="971" height="992" alt="Screenshot 2026-11-10 at 8 22 01 PM" src="https://github.com/user-attachments/assets/16cb44d7-1d78-4ccb-be0f-c8c1d3f01503" />
<img width="738" height="175" alt="Screenshot 2026-11-10 at 8 22 58 PM" src="https://github.com/user-attachments/assets/b21bbe23-d29f-49b1-8fab-6e271701b501" />

