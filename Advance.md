 1) add all file and commit
 -->git commit -am 'Message'

 2) update the latest commit
-->git commit --amend -m "message"

 3) add files to last commit
-->git commit -amend -no-edit

 4) overwrite history on remote
-->git push origin master --force

 5) undo a commit with a new commit
-->git revert commit-id

## (Bonus Tip) //go to anyones repo and press --> .

6) save a commit for later use without actually commiting
-->git stash

7) to add the stashed commit
-->git stash pop

8) to save stashed commit for later use
-->git stash save anyName

9) to view stashed list
-->git stash list

10) to work on stashed commit
-->git stash apply indexOfStashed

11) to set the root branch name
-->git branch -M branchName

12) to view commits in more readable way
git log --graphy --oneline --decorate

13) to fetch last commit in remote repo
git fetch origin

14) overwrite the local code with remote code
git reset --hard origin/master

15) clean random untracked file
git clean -df

16) to switch to recent working branch
git checkout -

17) to add a chunk of change(piece)
--> git add -p "file_name"
