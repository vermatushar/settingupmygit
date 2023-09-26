Just setting up my git

1. Initialise local repo with git : git init
2. Check status : git status
3. Stage Changes : git add .
4. Commit changes : git commit -m "message"
5. Add bracnch : git branch -M main
6. Add remote repo : git remote add origin "SSH"
7. Pull changes and rebase head : git pull --rebase origin <branch> 
8. Push changes to remote : git push -u origin <branch>
9. Adding GIT LFS
   After initialising git LFS (only have to do this once)
   git lfs track "<file to track>"
   Stage changes and push as usual


