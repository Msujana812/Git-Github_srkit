1 version control

+version control is a system that tracks the changes to a file or files or projects
over a time
+disturbuted version control system(DVCS)
  +github,mercurial
central version control system(CVCS)
  +github,apache

Uses of Git&Github:
->To complete the global certfications like goggle,udacity,courseera
->To track the files in a project

Git commands:

*cd foldername-->chnage directory
*ls-->List of files
*ls-a-->To see hidden files
*touch filename:to create a file
*nano filename-->it will create fileand open none editor
*ctrl+x-->to quit the file
 click on Enter filename to write:reg.html

Editing filename using vim editor
vim filename-->filename open with vim editor
ctrl+c
At the bottom of the file type `:w` to save the code
`:q` to exit the file

Git structure:

*untracked area
    - `git status`--> To know the status and file or project
    - `git init`--> To install git repository
    - `ls -a` --> to see hidden git repository
    - `git add filename`--> to add file to git
    - `git status`
    - `git rm` --cached filename--> Remove file from stagging area to untracked area
    - `git status`
    - `rm filename--> to remove file 
    - git commit -m "basic data"
    - Config user name and email
    - if git contains prvious user name and email 
check username with `git config --gobal user.name`,similarly check user email with
`git config --global user.email`
    - If you are not the user try to delete previous user data
        -Go to credential manager->windows creditinals-->remove git creditinals
        -To remove username `git config --global --unset user.name "previous user name"
*Stagging area/Tracking area
*Commit area