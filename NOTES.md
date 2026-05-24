GIT NOTES  

git init  
git clone ---  
git add --all  
git add -A  
git reset  
git status  
git add .  
git add *   ( only available files staged not del ones )  
git add *.txt (except del ones)  
git config --global user.name "Your Name"  
git config --global user.email "you@example.com"  
git config --local user.email "you@example.com"  
git commit -m "first commit"  
git reset HEAD~  
git rm a.txt  
git reset --hard (to bring back deleted files)  
git rm -f a.txt (forcefully deleteing a file with uncommited changes)  
git rm --cached a.txt (remove file from stage)  
git log  
git log --oneline  
git branch  
git checkout "branchname"  
git merge dev -m "merging info from dev to me"  
git checkout commitID  
git diff commitID1 commitID2  --> Q  
git push origin "branchname"    
git push origin main  
git fetch --> git merge  
git pull  
git restore dirname -> (restore to last commit status)  
git restore .  
git restore --staged dirname -> (restore to last commit status even if some were staged)  
git stash  
git stash pop  
git stash apply  
git stash list  
git stash drop  
git stash apply stash@{0}
git revert commitID
git branch feature
git checkout feature
git rebase main


