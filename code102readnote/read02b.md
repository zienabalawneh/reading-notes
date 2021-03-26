***Version control*** is a system that allows you to visit different versions of files or return the file to the previous version or correct errors in the files
***Local version control*** There must be one database on the hard disk in order to be able to store changes to files

***Centralized version control*** A system should contain a single server that stores changes and file versions

***Distributed version control*** In this system, if the hard disk of the database is damaged, that will lead to the loss of all data and works

***Git*** creates a snapshot of the file and stores a reference to it, in addition to reducing data loss and preserving data as the data is stored securely in a local database

**Git You can use GUI tools whether you are using Linux, Mac or Windows**
# Git installed in three ways:
1. as a package
2. via another installer
3. Download and compile the source code   


* After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

# Getting Help there are three ways:
   git help command

   git command --help

   man git-command
# The local Git repository has three components 
 + Working Directory     
 + Index           
 + Head


| Track  single File      | Track all Files     |
|   -----------           |   -----------       |
|  git add filename       |  $ git add *        |