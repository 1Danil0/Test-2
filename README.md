# Using of the GIT  

## Initializing Local GIT repository  

Local GIT repository is initialized by command **git init**    
And it may be unitialized by command **rm -rf .git**    

---  

## Commands  

### To create a file:  
1) *touch* is used to create a file  
2) *mkdir* is used to create a directory  

### To remove a file:  
1) *rm* is used to remove a file  
2) *rmdir* is used to remove a empty directory  
3) *rm -r* is used to remove a not empty directory  

### To move in the console  
1) *cd~* to move in the main directory  
2) *cd /Users/../..* to move in a particular directory
3) *cd ..* to move up  
4) *pwd* to find out myself  
5) *ls* to see a files in a directory
6) *ls -a* to see hidden files in a directory  

### To copy and move  
1) *cp* to copy a file - cp file.txt /c/Users/User/Desktop  
2) *mv* to move a file - mv file.txt /c/Users/User/Desktop  

---  

You have created a local repository.  
*git add* prepares a file from git repository to sending  
*git status* checks a git status  
*git commit -m "Description"* saves version of a file
*git log* to see operation history  

Now you should create a remote repository. Ypu have to sign in on GitHub.  
After that push a button "New" to make a remote repository. 
*git remote add origin*  
*git remote -v*