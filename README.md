# IT-114

Because I have a mac, and downloading git is a different process, this tutorial is for Mac Users.

1. Download homebrew throuh the Terminal.
2. Download Git through the Terminal using "brew install git"
3. Next, download Webstorm.
4. After, go to System Preferences, Version Control, Git, and enter the path to your git file. Because MacOS doesn't use .exe file, it should automatically detect the git and already have the path file.
5. Then, don't exit out of System Preferences just yet. Go to System Settings, passwords, and add a location for your password file, and click OK.
6. Create a GitHub account. After creating an account, click the + in the top right corner, and click "Create New Repository"
7. When creating the repository, make it public, and choose to add the readme file.
8. After creating the repository, go back to WebStorm, specfically the Main page.
9. Select Checkout from Version Control, then Git. Enter the github repository link, and enter local path name.
10. To test out the connectivity between WebStorm and GitHub, create a file by right clicking the area where files are located in WebStorm, choose File, HTML, HTML5, and give it a name ending with ".html".
11. A window will pop up asking you to add files to Git. Click Add.
12. Now, click Git on the top, and Commit. Now, select the file you want to commit, and click Commit.
13. Now, select the commited file, and click Push.
14. Sometimes it takes a moment, but your html file should be on GitHub now in the same repository.

- **Branch** : unique set of code changes with a unique name.
- **Clone** : copy of a repository with a full copy of the data
- **Commit** : individual change to a file with a message.
- **Fetch** : used to add changes from the remote repository to the local working branch
- **GIT** : open source program for tracking changes in text files
- **Github** : a platform where users can work together on or adopt open source code projects, fork code, share ideas, and more.
- **Merge** : takes changes from one branch, and applies them into another.
- **Merge Conflict** : a conflict that arises when merging and the user made different changes to the same line of the same file
- **Push** : sending committed changes to a remote repository
- **Pull** : fetching in changes and merging them
- **Remote** : version of a repository or branch that is hosted on a server
- **Repository** : contains all of the project files, and stores each file's revision history