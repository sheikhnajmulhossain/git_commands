# Push First code from terminal 

Setup Git
1. Create Github Account
` https://github.com/ `
2. Download & Install git
` https://git-scm.com/downloads `

Initialize Your Git Account 
1. Navigate/Open Git Bash
2. Connect your github account 
` git config user.email "niloy@example.com" `
` git config user.name "username" `

Create repo from github and push code/file/folder using terminal
1. Go to Github's webside
` https://github.com/ `
2. click on new repo
or, 
Navigate to "Your repositories" and press on "New" option
3. Give you repo a name, choose the privacy of the repo "Public/Private" and press "Create Repository"
4. Copy HTTPS Link
5. Open Git Bash/terminal
6. Navigate to your project folder/the folder you want to push
7. run the command written in the github website after creating the repo stating "…or create a new repository on the command line"
or, 
Use those commands after replacing the https link with the copied link
` echo "# draft" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sheikh-niloy/draft.git
git push -u origin main `

Your code has sucessfully pushed if all the steps has been followed properly. 