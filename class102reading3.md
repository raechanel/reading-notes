# What is git?
Git is  version control system that stores your data in snapshots of where you are in a certain point in time. Also, git allows multiple developers to work on the same code at the same time. 
### Stages
Files in github reside in three main states: `committed`, `modified`, and `staged`. 

*`Committed`* means data is securely stored in a local database. 

*`Modified`* means the file has been changed but not committed to the database. 

*`Staged`* means flagged a file's changed version to be commmitted in the next snapshot.
### Downloading Git 
Git can be downloaded various ways:
1. Install as a package
2. Install via another installer 
3. Download and complete the source code 

#### Downloading via Terminal 
If you are using mac the easiest way to download git is from the terminal.
#### Git website 
If you are using a mac you can download Git by clicking [here](http://git-scm.com/download/mac) and following the directions. If you are using Windows you can click [here](http://git-scm.com/download/win). If you are using Linux, click [here](http://git-scm.com/download/linux). 
#### Github 
A third options is to install git as part of the GitHub. For mac, click [here](http://mac.github.com/). For Windows, click [here](http://windows.github.com/)

#### Package Manager
Linux you can install Git via your distribution’s inherent package management tool.
`For Fedora`: '$ sudo yum install git'
`For Ubuntu`: '$ sudo apt-get install git'
#### Github Process 
Add - Commit - Push 
This process allows git to `add` the README.md file or the name of the file. Then `commit` the file and records changes made. `Push` allows you to push the changes or the final file to a remote repository. 
#### Commands and their function
`git help 'command'`/ `git 'command' --help`/ `man git-'command'` are all three ways to get more information on a particular command. 

`cd 'hello-world` imports and existing project into git

`git clone 'https://github.com'` creates a copy of an existing Git repository by using this clone command with the repository's URL
`git status` checks the status of the file
`git commit -m 'made change to a,b,c` this command commits the file and adds a message to serve as a memo to yourself or anyone else what has  been added or changed in this file. 
`git commit -a` allows you to commit all changes made to the file
`git push orgin master` pushes changes from the local "master" branch to the remote repository named "orgin". 





[<--Back](README.md) 
