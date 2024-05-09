# GitCommand
// copy 3 line 
echo "# microservicecomunication" >> README.md
git init
git add README.md
// add all folder 
git add .
// copy 4 line to push on github
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mangesh687/microservicecomunication.git
git push -u origin main

// code allreday commit and after the push code on github follow the step 
go to floder 
git add .
git commit -m "Your descriptive commit message here"
git push


// when only provide gitlink like https://github.com/prabhatrsharma/LGMVIP-TicTacToeGame.git to downlode on local machine 
go to any folder to save code  and open terminal 
git clone https://github.com/prabhatrsharma/LGMVIP-TicTacToeGame.git


error: remote origin already exists
How to slove this issue 
ChatGPT
It seems like you're trying to add a remote repository that already exists. You can check your existing remotes with the command git remote -v. If you want to change the URL of the existing remote, you can use git remote set-url origin <new_url>.

git pull commend also use 



 
