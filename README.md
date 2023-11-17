# Notes on using Github

## Prerequisites

- Make sure you have a Github account
- Make sure you have Git installed on your computer

## Creating a New Project

- Create a new project directory on your computer
- Create a new README.md file in the project directory [Github-Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- Create a new repository on your computer with `git init`
- Add the README.md file to the repository with `git add README.md` and commit the changes with `git commit -m "Verify commit"`
- Verify the status of the repository with `git status`
- Make sure your user and email are set in the repository with 'git config user.name' and `git config user.email`
- Create a new repository on GitHub
- Add the GitHub repository as a remote with `git remote add origin`
- Rename the current branch to main with `git branch -M main`
- Push the local repository to GitHub with `git push -set-upstream origin main`
- Enable Github Pages in the repository settings for the main branch
- Verify the page is live at `https://username.github.io/repository-name`
- Add an index.html file to the project directory and a .no_jekyll file to turn off Jekyll processing
- Commit the changes and push to Github
- Verify the changed page is live at `https://username.github.io/repository-name`