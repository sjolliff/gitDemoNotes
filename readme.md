## Commands


```
git init                           # initializes the repo
git add <fileName>				   # add specific file to stage
git add -A						   # add all files not on ignore to stage, and removals
git commit -m "<msg>"			   # commits with inline msg
git checkout - b <name>			   # creates new branch
git checkout <branchName>		   # change to target branch
git status                         # HELP!
git merge <branchName>             # integrates target branches commit history

git tag -a "<semVersion>" -m "<msg>"  # make a tag
git remote add <origin> <url>         # connect to github
git pull origin <branchName>		  # fetches and merges changes from target remote branch
git push origin <branchName>		  # integrates local branch into the remote
git push origin --tags				  # tags push separately

git reset --hard <id>                 # send branch to target id. [soft, mixed, hard]
git log                               # show git history of commits
git reflog							  # show last few git commands and related ids
```
