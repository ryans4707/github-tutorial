# GitHub Tutorial

_by *Ryan Santiago*_

---
# Git vs. GitHub  
* **Git** is something that runs in the command line. It is version control,  
which keeps "snapshots" of code. However, it does not require github.  

* **Github** is the thing we use to store that code in the cloud.  
It is a way to  visually track the changes we make to the code.



---
# Initial Setup  
  To set up your github account  
  1. First sign up for github by going to https://github.com  
  2. When you sign up, go to the top right of your screen to your profile icon.  
  3. Go to settings, click _SHH_ keys on the left side bar.  
  4. Go get the _SSH_ key from your IDE and copy and paste it into the key; *click add key.*  
  5. Go back to https://c9.io and in the command line type in _shh -T git@github.com_; click enter  
  6. Type yes. 
  
 `git config` is a one time set up so they know who to give credit for the changes that were made.
    
---
 # Repository Setup  
 `init` initializes git in our directory(now called a repository)for version control --  
 only do this once at the beginning   
 ## _First Github repo_  
 In your command line inside workspace, type in the following:  
 1.mkdir first-repo  
 2.cd first-repo  
 3.pdw (to make sure you are in the right directoy)
 4.git init  
 5.git config --global user.name "First Last"  
 6.git config --global user.email "username@hstat.org"  
 7.touch README.md  
      Open the README > This is my first repo  
 8.save, add  
 9.git commit -m "add readme"
### Make your Remote repo
- github > top right > new repository  
-Repository name : first-repo  
-create repository  
** MAKE SURE YOU HAVE SSH SELECTED**
- copy/paste the two lines that start with `git remote` and `git push` seperately into the command line.

  


---
# Workflow & Commands  
* `git status` is used to see what has been modified or changed. *You should use this as much as possible*. You can use this anytime to see what has been changed and is simply typed as is.
* `git add` is used to start tracking new files and to stage your changes. You type this in the file in which the file you're trying to add is in.  
This is typed as:  `git add (file you mad changes to)`
* `git commit` is used to record  your snapshots into your history. This is typed as:
`git commit -m "commit message"`
* `git push` is used to send our commits from our local repo to our remote repo. This is typed as : _`git push -u ("upstream") origin master`_(origin is the remote we are pushing to)  
(master is the main branch)
 
---
# Collaboration
- cloning is making a copy from remote to local. For this, you have to type `git clone` _URL_  
- To "fork" is creating a personal copy of someone else’s project. Forks are a connection between the original repository and your personal copy.   
- You can create a pull request to help make other people’s projects better.This is done by making your own chnages and suggesting them to the original project.  
-  To pull is to bring any changes from the remote repo down to the local repo.



