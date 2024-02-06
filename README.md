# AI_Lab2

In this repository we are going to study how to remotely connect git with github

Configure the project folder as a Git repository:

git init

This initializes a new Git repository in the current folder, and will see a .git folder (which is hidden) created in project folder.

Now the project is set up as a Git repository, and proceed to add files, commit changes, and push to GitHub.

git add .

And then, if you haven't created a repository on GitHub yet, create one. If you have, you can add the remote and push your changes:

git commit -m "Initial commit"

git remote add origin https://github.com/princedalmet/AI_Lab_2.git

git branch -M main

git push -u origin main

git branch feature-branch

git checkout feature-branch

git checkout -b feature-branch

git commit -m "Add example Python script to feature branch"

git push -u origin feature-branch

git push origin feature-branch
