# Git-GithubMarkdown



GIT COMMAND



_Creating & deleting directories_
- To create a new directory we use: "mkdir" <directory name>
- To delete an existing directory we use: "rmdir" <directory name>
- To move the directory to another directory inside the same one we use: "cd" <directory name>

_Navigating_
- Use cd/<directory name" to navigate the existing directories

_Comparing_
- To compare two files we use "diff" <file name 1> <file name 2>
- To display the differences of two files we use "diff" <file name 1> <file name 2>

_Finding files, folders, and inside files_
- To find files with specific extensions and locations we can use "find /<location> <file name>.<extension>"
- To find empty files in the current directory we use "find.<type f> <empty>"
- To find directories we use "find.<type d>"

_Create and edit text files_
- Use "cat <file name>.txt" to create a text file
- To keep editing the file run "<this is a test> > <file name>.txt"

_Get the state of the computer_
- To get the computer's software and hardware status use "systeminfo"

_Git Branches_
- To display a list of the. branches on your repository use "git branch"
- If you want to merge a brach into your current one, use "git merge <branch>"

_Rewriting Git history_
- To change the las commit from a base to another we use "git rebase <new base>
- To display a log of changes to the local repository's head we use "git reflog"

_Git Branches_
- To switch between branches we use the command "git checkout <branch name>"
- When we need to merge two branches together use "git merge <name>", to merge <name> into the current branch.
- And then, use "git branch -d" to delete the empty merged branch.

_Synchronizing Repositories_
- We use "git fetch remote" to fetch changes from the remote but not updating tracking branches.
- To push local changes into the remote we use "git pull remote"
- To push a local branch to the remote repository we use the command "git push -u remote branch"

_Configuring Git_
- To start working with git, you must set the name that will be attached to your commits and tags with "git config --globar user.name <name>"
- Then, a valid email must be set using "git config --global user.email <email>"
 
