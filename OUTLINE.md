
- history
- What is version control
- How is GIT diff?
    - Distributed 
    - Saves full copies of files if there is a change

	 git config --global user.email "you@example.com" 
	 git config --global user.name "Your Name"
	 git config --global core.editor vim

- How to create a repo
- git status / Cover stages a file can be in / committed / modified / staged 
- git add
- change contents of files, don’t stage new changes
- git diff shows one delta, git diff --staged shows another
- git commit 
- stage and commit next file

   PRACTICE
Create a git repo
Add a file
Commit the new file
Change the file, commit the new changes

Branching + Merging

Theory
git checkout -b <branch name> 
Add some data + commit
Look at contents of files
Checkout master branch
Look at contents of files
Add some contents to a different master branch file
Merge new branch into master
See that master now has both files
Add a “secret” file
Add .gitignore to ignore secret file

GitHub
Explain github
Create GitHub account 
Create ssh key
Copy ssh key to GitHub settings
Create repo in GitHub
Set up remote 
Push to remote and display
