P2: Portfolio Repository with an Initial Commit


Aim: To create a Git repository for a portfolio project and make the initial commit.

Procedure:
1. Create a project folder.
2. Navigate into the folder.
3. Initialize Git.
4. Create an HTML file.
5. Add the file to the staging area.
6. Commit the changes.

Commands:
mkdir portfolio
cd portfolio
git init


Create an index.html file:(touch index.html 
open -e index.html
//writing the code there


<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
</head>
<body>
    <h1>Welcome to My Portfolio</h1>
    <p>This is my personal portfolio website.</p>
</body>
</html>


Check the Git status:
git status


Add the file:
git add index.html


Commit the changes:
git commit -m "Initial portfolio commit"


Check commit history:
git log


Result: Successfully created a portfolio Git repository and made the initial commit.
