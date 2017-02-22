# GitNotes

### Notes to help navigate Github functionality

### Information:
Created on February 22, 2017 by Jean-Paul Ventura

# Creating GitHub Repo via command line using existing directory:

In the command line:

1.) Initialize local directory as git repository:

	$ git init

2.) Add files in your new local repository, then stage the first commit:

	$ git add .

	-adds files from your local repository and stages them for commit. To unstage a file use 'git reset HEAD YOUR-FILE'

3.) Commit the files youve staged in your local repository:

	$ git commit -m "first commit"

	-Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again. 