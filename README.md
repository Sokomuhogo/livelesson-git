#GIT notes
- ' git init' : initialize current folder as a git repository
- 'git clone <url> : brings
- git status let us know current state
- git add will add a file to the staging area
-git commit will open text editor
--adding more changes
git log
git long  --oneline
- iam adding 2 lines now
- this one is the second line I am adding
-git diff: compare current uncommited state with last known git state
-git diff --staged: runs git diff between the staging area and last known state
-git diff HEAD~<NUMBER> : compares HEAD with commit <NUMBER> ago (relative)
-git diff <HASH> : compares HEAD with the commit in <HASH>
-git remote add <NAME> <URL> : adds the <URL> as a remote with the name <NAME>
- <NAME> Is by convention called origin
- git remote rm <NAme> removes the remote called <NAME>
-git remote -v : look at all the remotes you have
-git pull <WHERE> <WHAT> : pulls the <WHAT> branch in <WHERE> to local computer
