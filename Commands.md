Initialize empty git repo
 `git init `

- To configure: email and user.email 
` git config --global user.email "username@example.com" `
` git config --global user.name "yourname" `

- To view the list of user
` git config --list `

To view the git status
-->git status

To add file to Staging area
--> git add file_name        			  //single file
-->git add file_name file2_name file3_name       //multiple files
--> git add .  					// add all files

To commit the changes
--> git commit -m "Message"		//In master branch
--> git commit -am "Message"  		//In a branch

To view git commit history
--> git log
--> git log --oneline 			//To view commits in one line

To change the file into previousstate
--> git checkout SHA_id_of_the_commit
--> git checkout master 		//To return back to present state

To add the repo path
-->git remote add orign https://github.com/codemode365/example-project.git

To push the staged file to github
--> git push origin master

To pull the file from github
--> git clone url-of-file/repo  //copy repo

To view the git difference
--> git diff
--> git diff --staged 		//view the changes

To create branch
--> git branch branch_name

To view all pulled branch from git
--> git branch -a

To delete the branch
--> git branch -d branch_name	//for merged branch only
--> git branch -D branch_name 	//for non-merged branch

To change the working branch
--> git checkout branch_name

To fetch the remote branch
--> git fetch origin <branch>

To merge the branch to with master
--> git merge branch_name  		//in master branch
--> git merge --no-ff branch_name 	//to merge with different SHA value

To list the merged branch
--> git branch --merged

To list the non merged branch
--> git branch --no-merged

To reset file to the previousState
--> git reset --hard sha-id-of-the-state

To update the repo file in local pc
--> git pull origin master

To view the command history
-->history

To show the remote path
-->git remote -v

To list the all branchs in the repo
--> git remote show origin

To give the tag name
--> git tag -a name -m "message"

To view the tag name
--> git tag

To track all your recent gits
--> git reflog

----->Important (Always create git ignore file to creat the limit while pushing the files) <---
--> add the file names in .gitignore file






