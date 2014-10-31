Version Control Will Save Your Bacon

Thursday October 30, 2014

Version control is the process of tracking changes in files to allow for time machine like behavior, and eases the collaboration process within a development team. This time travelling through code allows you to roll back changes by typing a few select keystrokes. A team of developers can jointly work on a project at the same time and not worry about using deprecated, out of date source code. Version control allows you to set up a repository, which is a fancy term for the directory that contains all of your project files and folders.

Git is a type of version control that uses your command line interface to track changes within a repository. You can tell git exactly which files to track, and which to ignore. You can update files in a repository by adding them to the stage, and then committing (read: updating) them to the branch. All commits need a message that explains what the commit does, for example: "update user login page". See the list below of a few popular git commands:

-`git init`: create a repository of the current directory (and all of its folders and files)
-`git status`: displays any current changes in the repo, since last commit
-`git add .`: adds all of the changed files to the stage
-`git add <file>`: adds a specific file or folder to the stage
-`git commit -m "message here"`: updates the staged files to the repo
-`git checkout -b <branch name>`: create a new branch
-`git checkout <branch name>`: switch to a branch

As you can see, git commands are pretty straight forward and are typically less than 5 words. Once you look past the initial intimidation of learning git, you'll find it is an essential tool for your development cycle.

GitHub is a great addition to git, as it gives you a centralized place to store your repository. On GitHub, you can choose who to share your repo with, or you can share it with the entire world. It's social-coding at its best, as users can fork and clone a repository to their local machine, hack away to optimize some code or develop a new feature, and finally submit a pull request. When the author of a repo gets a pull request, they can review it and merge it to the master branch at their discretion.