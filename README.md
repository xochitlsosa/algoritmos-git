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
 
_Reverting changes in Git_
- We use "git reset --hard" to have all changes discarded
- To do it in a specific branch, use "git reset <target reference>" so any difference will stay as an uncommited change
- To create a new commit reverting the changes from a specific one use "git revert <commit sha>"

BASH COMMANDS

- To quickly view all files in a specified directory we use "ls"
- "mkdir" is a command we use to create directories.
- To print the directory you are currently in, you can use "pwd"
- To move ore rename a directory use "mv"
- "cat" is one of the most versatile commands and serves three main functions: displaying the file, merging copies, and creating new ones.
- Use "exit" to close a terminal window
- When there are a lot of commands on your console or terminal window use "clear" to erase everyting.
 

CODE SNIPPETS 
 
Code snippets are pieces of reusable code that can be used for bigger projects to help with functionality and efficiency when programming.

_Example 1_

 "Area of rectangle"

#include <iostream> 

using namespace std; 

const double pi = 3.14159; 

int main() 
{ 
float length, width, area; 

cout << "Enter The Length Of The Rectangle: "; 

cin >> length; 

cout << "Enter The Width Of Rectangle: "; 

cin >> width; 

area = length*width; 

cout <<"The area of the rectangle is : "<< area << endl;

return 0; 
}

- This code snippet is used to calculate the are of a rectangle; you would just need to substitute the values that you need and put it into your program for it to run.

_Example 2_

 "Average"

 #include <iostream.h>

#include <math.h> 

int main()
{
int number1,number2,number3;

double average;

cout<<"Enter three integers and I will display the average"<<endl;

cin>>number1>>number2>>number3;

average = (number1 + number2 + number3) / 3.0;

cout<<"The average is "<<average<<endl;

return 0;
}

- This piece of code will be useful to recycle when we are working on a program that needs to calculate averages, just put your values into the code and change the name of the variables if you want.

_Example 3_ 
 
"Multiplying numbers by a potence"

 #include <iostream> 

using namespace std; 

int main() 
{ 
int number,power,count,i; 

cout << "Enter Number: "; cin >> number; 

cout << "Enter the power: "; cin >> power; 

count = 1; 

for (i=1; i <=power; i++) 

count = count*number; 

cout << count << endl; 

return 0; 
}

- This snippet would be useful when working with numbers, it is used to multiply a single number into a potence in a faster way and making the code a lot smaller and compact. 

 

