#This note section is for git and Shell scripting

$BASH_VERSION
cd c:\revature
mkdir "Test Training"
mkdir Test Training -> will create 2 folders
cd dotnet\ Training\ 220328/
cd ..
 -> to go 1 level up (edited)
cd "dotnet Training 220328"
rmdir "dotnet Training 220328"/
mkdir dotnet-Training-220328
cd dotnet-Training-220328
ls -> to list all the files with in the folder
ls -l -> get more information about the listed files
ls 2107* -> listing using metacharacters
pwd -> print where directory
clear  -> clear screen
touch Notes.md -> creates a new file
rm program.java
git log --pretty=oneline


Branch Command Lines
git branch -a List all remote branches.
git branch feature-1
git checkout feature-1
git branch -m feature-x to rename the current branch
git branch -d <branch> -> This is a “safe” operation in that Git prevents you from deleting the branch if it has unmerged changes.
git branch -D <branch> This is the command to use if you want to permanently throw away all of the commits associated with a particular line of development.
git branch  List all of the branches in your repository. This is synonymous with git branch --list.
git checkout -b ＜new-branch＞simultaneously creates and checks out ＜new-branch＞