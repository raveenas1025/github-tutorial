# GitHub Tutorial

_by Raveena Suman_

---
## Git vs. GitHub
 _Git: is "verion control": so you can take snapshots of code and keep track of changes._  
 _Github: Github allows you to store code in a cloud, visually keep track of changes and also collaborate on files easily._ 
 


* Similarites:

 * runs on command line
 * keeps track of changes

* Differences:
 
 * Git does not require github.
 *  Github requires git, whereas git does not require github.
 *  Github stores code in the cloud, while git stores it in your local machine.
 *  Github allows you to visually track changes
 *  Git is "version control"; snapshots of code


---
## Initial Setup
 * create an account on [github.com](github.com) in order for all changes done in code to visually be shown and to collaborate on files.
 * make sure to connect the *SSH key* in order to safely open accounts with a highly indecipherable password.
 * when setting up git, you should set up your username and email.
  * to set up your username you will be asked to type _git config --global user.name "type your name"_.
  * to set up your email you will be asked to type _git config --global user.email "type your email"_.
 * This will only be asked once when you use _--global_ because then git will only use the information given  in that moment for all other commits.


---
## Repository Setup
 * To start up your first repositiory, you would use _git init_. This starts up your first repositiory, git commands are not allowed unless a person would initialize their new empty repository.
 * When pushing your changes from your local repository to the cloud, a person should use the two commands *git add* and *git commit* before using *git push*.
  * *git add* is used everytime a person changes their code and wants those altered code to appear in the cloud. This starts up your first commit.
  * *git commit* is used after a person adds all files they have changed. This takes a final snapshot of the code, this shows that the person is satisfied with the code they have created and is ready to submit it to the cloud. When committing it will ask for a message, this is helpful for a person to keep track of what it is that they have started, changed and committed.
 * Another important step is to set up your repository on your github account.
  * To set up a repository on github, you would click on the +, then click on "new repository" and when creating a new repo you must name it the exact name you have given the repo on your local. This allows for all the code pushed from your local to appear in the cloud, your code is then placed live and you can visually see the commits made.
 * *git remote add origin URL*, allows for the coder to connect their local repository to the repo that is on github, this is allows everyone else to see it. The *origin* part allows you to submit the URL once and any other time you would do *git push*, the server would know where the code will be pushed.



---
## Workflow & Commands
 * *git status* is an important command to use. It allows the coder to see all the files they have made and which still need to be added and committed.
 * *git add* allows the coder to add all their modifications onto the stage.
  * *git add .* allows you to add all files that have been changed.
  * *git add "file name"* (not in quotes) allows you to only add only that file.
 * *git commit* takes a snapshot of all new modifications.
 * *git push* finally sends all the commits to github where you'll see all of the new changes to your project.
