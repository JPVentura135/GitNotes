# GitNotes

### Notes to help navigate Github functionality

### Information:
Created on February 22, 2017 by Jean-Paul Ventura

# Creating GitHub Repo via command line using existing directory:

1.) Create a new repository on GitHub. To avoid errors, do not initialize 		the new repository with README, license, or gitignore files. You can add 
	these files after your project has been pushed to GitHub.

2.) Open Terminal.

3.) Change the current working directory to your local project.

4.) Initialize the local directory as a Git repository


In the command line:

5.) Initialize local directory as git repository:

	$ git init

6.) Add files in your new local repository, then stage the first commit:

	$ git add .

	-adds files from your local repository and stages them for commit. To unstage a file use 'git reset HEAD YOUR-FILE'

7.) Commit the files youve staged in your local repository:

	$ git commit -m "first commit"

	-Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again. 

At the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.

8.) In Terminal, add the URL for the remote repository where your local 
	repository will be pushed:

	$ git remote add origin remote repository URL
		-Sets the new remote
	$ git remote -v
		-Verifies the new remote URL

9.) Push the changes in your local repository to GitHub.

	$ git push -u origin master
    
    - Pushes the changes in your local repository up to the remote repository you specified as the origin