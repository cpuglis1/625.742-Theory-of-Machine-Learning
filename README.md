# 625.742-Theory-of-Machine-Learning
Theory of Machine Learning Final Project Code Base

Hey Friends- I thought to provide a breif reminder on git basics to ensure using 
the tool is as simple and effective as possible. Please text if you run into any errors. 

thanks! -chris p.

Installing Git: 
1. Download the Git installer here: https://git-scm.com/downloads
2. Install using default settings.
3. Verify by running git --version in your cmd prompt.
	a. Note, a common issue is that cmd doesn't recognize the command git
	This usually means git is not in your PATH. To add:
	
	To add Git to your PATH environment variable on Windows:
	
	Open the Start menu and search for "Environment Variables".
	Click on "Edit the system environment variables".
	Click on the "Environment Variables" button.
	In the "System Variables" section, find the "Path" variable and click "Edit".
	Click "New" and add the path to the Git executable. The default path is C:\Program Files\Git\bin.
	Click "OK" to close all the windows and save your changes.

Cloning the Repo:
0. Make a GITHUB account
1. Navigate to the directory of interest in the cmd prompt using the command cd <file/path>
2. Run command: git clone https://github.com/cpuglis1/625.742-Theory-of-Machine-Learning.git
3. Run cd 625.742-Theory-of-Machine-Learning to enter the repo

- This should clone the repo and you should have all needed files here.

Making Changes:
1. Make sure you start on the 'main' branch. You can see what branch you are on using 'git branch'
2. Run command git checkout main if not on main.
3. Run 'git pull origin main' in order to pull the latest changes from the remote repo
4. Once you have the most up to date repo, create your branch that you will make your changes on using
the command 'git branch -b <feature-branch>'
	a. for example, i made the feature branch 'feature-unsupervisedlearning'
5. From here you can open up a new script/jupyter notebook in the folder that the repo was created in.
Make all your edits in that script.
6. Once done, run 'git status' to see what files are staged or unstaged.
7. Run git add <file_name> to stage the file prior to commit. Run 'git add .' to add all
8. Run git commit -m 'Message about commit' to lock in your file changes.
9. Push code by running: 'git push --set-upstream origin <feature-branch>' 

Pull Request
1. Once you pushed your code, go into github
2. Go to the pull request tab
3. Create new pull request
4. Make base:main and compare:<feature-branch> and submit for team to review