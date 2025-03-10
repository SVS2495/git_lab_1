# git_lab_1
first lab

Step 1 : clone the remote repository 
1) by using following command clone the remote reposiotry to your local machine "git clone git@github.com:SVS2495/git_lab_1.git"
2) go to the directory path " cd <repository path>

Step 2 : Create new branch for feature1
1) create new branch for feature1 by using following command " git checkout -b feature1 "

Step 3 : updated feature1 branch
1) completed the required changes on project a+b=c

Step 4 : add the the updated file to staging area and then commit the changes
1) git add abc.txt
2) git commit -m "Updated a+d=e" -> committed the changes with message

Step 5 : make sure feature branch is up to date with main branch
1) to avoid confilcts update your main branch 
     git checkout main
     git pull origin main
2) merge feature1 branch with main branch
     git checkout feature1
     git merge main     

Step 6 : push feature1 branch to remote repo
1) git push origin feature1

Step 7 : Create pull request
1) before creating pull request make sure your branch is up to date with main branch
2) the create pull request
3) after review merge with main branch 