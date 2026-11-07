P4: GitHub README and Version Tags
Aim: To create a README file, upload a Git repository to GitHub, and create version tags.

Procedure:

Step 1: Create README.md
# My Portfolio

## About
This is my personal portfolio website.

## Skills
- HTML
- CSS
- JavaScript

## Projects
- Personal Portfolio
- Web Development Projects

## Author
Student Name


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


Result: Successfully created a README file, uploaded the repository to GitHub, and created a version tag.