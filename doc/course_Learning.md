### My learning on devops course

`github shortcut key`
git config --global user.name
git config --global user.email
git config --list
git add .
git add First_File.txt
git status
git commit -m "Addition in file"
git log
git log --author="Kiran-38"
git checkout <branch_name>
git branch                   #To know which branch you are in
git branch develop
Add all the code files and then try to add to git by command <git add .>
git status 
git push
For getting the latest code from main create a pull request from github server page



***************************** git merge ***************************
git branch develop
Do all your changes here and commit and push the changes
After that change to your main branch 
git merge <branch_to_be_merged>
git commit
git push #Congrats you have successfully merged your developed branch

***************************git reset and revert*********************

git reset –soft <commit_id>
git reset –hard <commit_id>
git revert 
