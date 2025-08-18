# Repo created but first commit not initiated error

1. Go to project folder in local device
2. Open Git Bash/ terminal
3. initiate git 
` git init `
4. Add the GitHub remote (copy the repo link from github):
` git remote add origin https://github.com/your-username/your-repo.git `
5. Push your code (since your local branch is master):
` git push -u origin master `


After this first push, in the future you can just run normal push commands:
` git push `