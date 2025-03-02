Git branches 

* Main or master branch has the latest version
* Create your own branch and work on it which will be the personal copy of the master branch
* Do the testing and development on the your branch
* After the code review if it is approved do the pull request so that we merge it with master branch

1. git init
2. git remote add origin <repository_name>
3. git add . 
4. git commit -m "Message"
5. git branch -M main
6. git push origin main
7. git checkout -b <branch_name>    (To create a new branch i.e new-feature)
8. git branch -a   (To view all branches)
9. git push origin new-feature     (To push the branch to the github)
10. Make changes or add some code
11. git add .
12. git status     (To see the status)
13. git log        (To see the previous commits)
14. git commit -m "Message"
15. git push origin new-feature          (This adds changes only to the new-feature branch) 
