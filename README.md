# GitHub Tutorial

_by Raveena Suman_

---
## Git vs. GitHub
 _Git: is "verion control": so you can take snapshots of code and keep track of changes_  
 _Github: Github allows you to store code in a cloud, visually keep track of changed and also collaborate on files easily._ 
 


* Similarites:

 * runs on command line
 * keeps track of changes

* Differences:
 
 * Git does not require github.
 *  Github allows you to collaborate on files easily
 *  Github requires git, whereas git does not require github.
 *  Github stores code in the cloud, while git stores it in your local machine.
 *  Github allows you to visually track changes
 *  Git is "version control": snapshots of code


---
## Initial Setup
 * create an account on [github.com](github.com) in order for all changes done in code to visually be shown and to collaborate on files.
 * make sure to connect the *SSH key* in order to safely open accounts with a highly indecipherable password.
 * when setting up git, you should set up your username and email.
  * to set up your username you will be asked to type _git config --global user.name "type your name"_
  * to set up your email you will be asked to type _git config --global user.email "type your email"_
 * This will only be asked once when you use _--global_ because then git will only use the information given that you have given in that moment for all other commits.


---
## Repository Setup
 * To start up your first repositiory, you would use _git init_. This initializes your first repositiory, Git commands that a person does that is not allowed unless a person would initialize their new empty repository.
 * When pushing your changes from your local repository to the cloud, a person should use the two commands *git add* and *git commit*.
  * *git add* is used everytime a person changes their code and wants those altered code to appear in the cloud. This starts up your first commit.
  * *git commit* is used after a person adds all files they have changed. This takes a final snapshot of the code, this shows that the person is satisfied with the code they have created and is ready to submit it to the cloud. When committing it will ask for a message, this is helpful for a person to keep track of what it is that they have started, changed and committed.
 * t


---
## Workflow & Commands