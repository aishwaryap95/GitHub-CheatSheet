# GitHub-CheatSheet
 GitHub Cheatsheet - Complete Reference for GitHub Commands
 
Welcome to the GitHub Cheatsheet repository! Here, you will find a comprehensive collection of commands, tips, and best practices for effectively using GitHub.

This repository serves as a handy reference guide for both beginners and experienced users who want to quickly access and learn about various GitHub commands and functionalities. It aims to provide a centralized resource that covers a wide range of GitHub operations, enabling users to navigate through the intricacies of version control, collaboration, and repository management.

Happy coding and collaborating with GitHub!

# Why should we use pull requests?
- Anyone with read access to a repo, can create a pull request
- If we want to create a new branch for pull request and do not have write permission to the repo,
  you can fork the repo first.

# push
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<your-github-username>/<your-repo-name>.git
git push -u origin main


git push -u origin main

# Merge master branch into main
git branch main
git checkout main
git pull origin master --allow-unrelated-histories
git push --set-upstream origin main
