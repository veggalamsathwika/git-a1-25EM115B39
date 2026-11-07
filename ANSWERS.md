Q1.Git says "nothing added to commit but untracked files present "because the files have not been added to the staging area.The next command should be git add filename,followed by git commit.

Q2.git diff shows changes that are not staged.git diff --staged shows changes that are staged and ready to commit.In this assignment,I used git diff after changing the canteen menu and git diff --staged after running git add menu.txt.

Q3.No.Adding an already tracked manager.env file to .gitignore will not stop Git from tracking it.The command git rm --cached manager.env stops tracking the file but keeps it on the computer.

Q4.git restore filename discards unstaged changes and restores changes and restores the file from the latest commit.git restore --staged filename removes a file from the staging area but keeps the chanes in working directory.

Q5.I used the commit message "Update canteen menu with new items and prices" instead of a general message like "update".A clear commit message explains what changed and makes the project history easier to understand.