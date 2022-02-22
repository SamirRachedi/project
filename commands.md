Video 6:

create and upload files to github ...

first clone git repo to a local repo : 
git clone https_URL_of_git_repo local_repo

git status :  Lists in red the files that have been changed, but not yet comminted to git repository 

git add file.zzz : adds changed file to git branch 

git commit : commits changes (confirm changes in the added files in the branch)
	-m : Add message to the commit

git push origin main : push all changes to the origin branch in the master directory of git repo (use git token code for authentication )


In git status: 
	Changes not staged => existing files on git have been chaged but not yet pushed changes to git repo
	untracked files => new files not yet pushed to git repo


Video 7:
git log : history of commits : Date + commit ID

git checkout commit_ID => allows to undo all commits after the commit whose ID is commit_ID  (NEVER use it unless no other solution is there hahaha)

lg command: 
Allows to better show logs 
Add lg in ~/gitconfig : under [alias]
lg = log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %>>
Video 6:

create and upload files to github ...

first clone git repo to a local repo : 
git clone https_URL_of_git_repo local_repo

git status :  Lists in red the files that have been changed, but not yet comminted to git repository 

git add file.zzz : adds changed file to git branch 

git commit : commits changes (confirm changes in the added files in the branch)
	-m : Add message to the commit

git push origin main : push all changes to the origin branch in the master directory of git repo (use git token code for authentication )


In git status: 
	Changes not staged => existing files on git have been chaged but not yet pushed changes to git repo
	untracked files => new files not yet pushed to git repo


Video 7:
git log : history of commits : Date + commit ID

git checkout commit_ID => allows to undo all commits after the commit whose ID is commit_ID  (NEVER use it unless no other solution is there hahaha)

lg command: 
Allows to better show logs 
Add lg in ~/gitconfig : under [alias]
lg = log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %>>
