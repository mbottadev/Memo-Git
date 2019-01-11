# Mémo sur les gits

##  create & clone

create new repository               **git init**

clone local repository              **git clone /path/to/repository**

clone remote repository                 **git clone usemame@host:/path/to/repository**


##    add & remove

add changes to INDEX                 **git add <filename>**

add all changes to INDEX                  **git add**

remove/delete             **git rm <filename>**


##   commit & synchronize

commit changes              **git commit -m "Commit message"** 

push changes to remote repository                    **git push origin master**

connect local repository to remote repository                      **git remote add origin <server>** 

update local repository with remote changes                       **git pull**


##     branches

create new branch                   **git checkout -b <branch>**
                                                                                e.g. git checkout -b feature_x

switch to master branch                      **git checkout master**

delete branch                 **git branch -d <branch>** 

push branch to remote repository                          **git push origin <branch>**


##   merge

merge changes from another branch **git merge <branch>io**

view changes between two branches **git diff <source_branch> <target branch>**
 e.g. git diff feature_x feature_y



## tagging 

create tag **git tag <tag> <mmit ID>**


                                      
                                           
