______________Git Commands Page_______________
git :- show all git commands.
pwd :- Present work directory.
ls :- To check items in present work directory.
git log :- To check the commit history.
git status :- To Check Status of your files.
git init :- Allow git to track your files.
git config --global user.name "FarrukhSajjad46".
git config --global user.email "farrukhsajjad46@gmail.com"
git config --list :- To check your name & email connectivity status.
git add --a :- Allow you to add file in staging area.
git add . : Perform above same work.
git add fileName : Perform above same work with specific file.
git commit -m "first commit" :- Commit allow you to save in git repository.
git commit -a -m "first commit" :- Save data direct in repository.
git restore fileName :- recover your last staging data.
git restore --staged fileName :- Un-staged to staged files.
git checkout -f :- Recover your data with your last commit.
git checkout fileName :- ap ko akhri commit se match karwa deta he.
git mv fileName newFileName :- Rename your tracked file or folder by get.
git rm fileName :- Delete your tracked file by git.
git rm --cached fileName :- Delete file cached history by Git.
git clone 'url' :- Clone a project in your local disk.
git diff :- cwd ko last time staged data sy compare karta he.
git diff --staged :- Ye staged data ko last commit data sy compare karta he.
.gitignore :- This type of named file allow git to ignore specified name.
git push origin master :- ye push ker dy ga origin master me.

3 step to create private ssh key from git hub:
first: key generate karna
ssh-keygen -t ed25519 -C "farrukhsajjad46@gmail.com"
second: ensure that ssh agent is running if no then run it with command.
eval "$(ssh-agent -s)"
third: agent ko apni identity karwana
ssh-add ~/.ssh/id_ed25519
fourth: clip for copy and tail for show key in bash
clip < ~/.ssh/id_ed25519.pub

ssh key:
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIMRYpVRMJD4TYyEmvzTvac02srlT5g09xqlpoOrisVHj farrukhsajjad46@gmail.com

