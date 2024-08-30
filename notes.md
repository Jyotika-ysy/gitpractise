git init--------used for once only when you start working with git on new folder
git status-----this is used to check the status of the folder that all the files are part of git or not.


if you are going to add any new file in the folder then check with git status and it will show you untracked file. to make this part of git you need to perform git add and git commit


git add --a ---------when you are adding the file for the first time as part of git repository
git add .
git add *

git commit -m "initial commit"


git commit -a -m "index file change" ------this will only be used for those files who are already a part of your git.




commands for git hub repo to push data. perform the given commands for the first time only
git branch -M main
git remote add origin https://github.com/Jyotika-ysy/gitpractise.git
git push -u origin main


after this to upload or push the data in the github repo always use this command:
git push