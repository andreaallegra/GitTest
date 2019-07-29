PyCharm In-Depth VCS #1: Getting Started
https://www.youtube.com/watch?v=jFnYQbUZQlA&t=2s

1:Local History

2: Create a local GIT repository
alt ` (backslash) == VCS operation popup -> Create git repository
The current files are in red meaning that they are not in version control,
They needs to be added in version control

Add a file to CVS
alt ` (backquote) (VCS > VCS operation pop up) +
this create a .git folder for our local repository
+ Add to VCS == Ctrl Alt A
or
CVS -> Git -> Add
or
right click on the file
or
quick search: ctrl shit A and type add to vcs

3: Push to GitHub (Share a project on github)
VCS + Import into version control + share project on github

4: checkout from github to the local computer and to pycharm
VCS -> checkout from version control -> Git

PyCharm In-Depth VCS #2: Core VCS
https://www.youtube.com/watch?v=_w9XWHDSSa4


Color coding
1: Adding files
2: Committing changes
3: Refactor
right click on the file -> refactor
4: Diff
CVS -> Git -> Compare with same repository version
5: History
6: Revert
Ctrl Alt Z
7: Update
to get changes the origin (remote) done by other devs
VCS -> update project == ctrl T (done in git)
conflicting changes (one in git)
latest change in github

next example: change in remote

PyCharm In-Depth VCS #3: Branching and Merging
https://www.youtube.com/watch?v=AHkiCKG-JhM

1: Branches
create a new branch
size = 750 (from git)

2: Merging
easy case: where no conflicting changes have come in
Make changes to branch and commit
go back to master
pull any changes from the remote repository using update project
click on marge

difficult case: where no conflicting changes have come in
3: Fetching: to fetch the data from the remote repository
4: Rebase: to re-ger the master branch into the branch3

note:
main branch on local: master
main branch on remote: origin
