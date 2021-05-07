who did what changes
git config --global user.name "trupti"
git config --global user.email "trnayak11@gmail.com"

git init --> initialize
git status  --> show the movements

git add --> adding files to staging area

git commit -m "first commit for practice
 
git log
 
edit files

git diff   --> show the edited details

git status
git commit

fetch and pull

if an user commited new files  to a remote repo, than uther user can not push new chages to remote repo untill the local
repo of the user get sinced with the changes. 

git remote add origin https://github.com/trnayak11/devops.git

branching:-

git branch branch1  --> create a branch
git branch  --> show how many branch are there

git checkout branch1   --> checkout to new branch branch1

create file in br1
add commit, than check out to master, u will not see the file crated newly inside the folder

git merge br1  --> merge file on br1 branch

git branch -d br1  --> delete merged branch

git branch -D br2 --> delete unmerged branch


merge conflict  ;>

craet a branch, checkout to that branch, edit an existing file and come back to master than again edit the file and try to merge 

conflict will arise..

manually open the file and change the file

add and commit than merge 

git stashing -->

git stash save "first save"
 can apply in different branch
 git stash list
 
 git stash apply stash_header
 git stash pop   --> apply most recent stash and delete stash 
 
 git stash drop perticular stash_header  --> delete perticular stash 
 
 git stash clear --> delete all stash list
 
 
 git reabse br1 --> master branch
 
 git revert HEAD  --> revert the latest commit
					this will create a new commit id so we can revert the revert also(undo)

git rset commit_id  --> head will point o given commit id, but the all the changes will be there. Also called soft reset

git reset --hard commit_id  --> head will point to the given comimit id but the chnages will be deleted. Also caleed the hard resset
