# Miniproject1-601--001
# Vito DePalo IS601-852
## Usage of GIT, Docker, automated testing, and conituous integration improves productivity and competitiveness of a company.
1. GIT is a source code management tool, basically software that manages changes or a type of verison control. GIT is distributed Linux operating system software developed by the founder of Linux Linus Torvalds. GIT allowas developers to collaborate in software teams, revert changes and keep track of code, like an index through comments. Because GIT is a open collaborative tool it allows alot more flwxibility to the team that increases productivity and competitiveness as you can see changes and make comments dynamically tha also allows to adapt to changes more effectively and more efficiently.
2. Docker is a software containerization platform, meaning you can build your application, package them along with their dependencies into a container and then these containers can be easily shipped to run on other machines. As stated by Vineet Chaturvedi in the Docker Tutorial.The biggest advantage for productivity is that developers or other team members like testers can use docker without installing a special software application and using Docker on an open platform, and once again it is more effective and efficient to develop and modify code and get it into prodcuction.
3. Automated testing that can be acheived by using both Git and Docker can expand your testing capacity, the number of test cases, get faster feedback as the results are readily avaialble to the interested parties, and improve quality through more substantial testing opposed to manual testing.
4. Continuous Integration allows the developer to continuously integrate code into a single shared and easy to access repository. This leads to smaller code changes, faster times to debug, more test reliability, faster release dates and usually better customer satisfactiom which is key for better productivity and effective competitiveness in a company.
## Vi Command and usage
vi is the text editor that comes with UNIX operating systems that allows you to create and edit files.The following are some basic commands for the vi editor and for moving around the file system. To start the Vi editor you type in command mode "vi <filename>" If the filename exist it will open it and be ready for editing, if it dose'nt exist it will create a new file. 
 1. Some basic editing commands include i - insert at cursor; a - write after cursor; A - write at the end of the line; ESC - terminates the insert mode; u-undo last change; U - undo allchanges to the entire line; dd - delete line; dw - delete word; x - delete characterat the cursor. Moving within a file includes k - to move cursor up; j - to move cursor down; h - to move cursor left; and l - to move cursor right. To save and close file: Shift+zz - save the file and quit; :w - save the file but keep it open;:q - quit without saving and :wq - save the file and quit.
## Linux and basic commands
1. The **cd** command means change directory you use it to change levels of directories in a file struture and you use it by typing on the command line "cd" followed by the name of the directory you wna to switch to.
2. The **mkdir** command is when you need to create a folde or directory, use it by typing "mkdir directory name".
3. The **cp** command is used to copy files through the command line. "cp <location of the file to be copied> <where to copy>.
4. The **pwd** command is the path that starts from the root directory which is the base of the Linux system. You can tye this command to start from here regardless of where you are in the file structure.
5. The **mv** command allows you to move files through the command line and you can also use it to rename a file by "mv old new", thereby changing the fileaname old to new.
6. The **rm** command allows you to delete files and directories using "rm filename" and "rm -r folder name" to dlete both the folder and files.
7. The **history** command allows you to provide a list of previously used commands that is saved in the history file.
8. The **Home Directory and ~**, you can do a "cd" to get back to the home directory or use the tilde "cd ~"
9. The **file paths** in Linux use directories or folders. All files on the computers drive are in the root directory. Files and folders on Linux are given the usual filenames, but when a file is inside a folder, or a folder is inside another folder, the / character shows the relationship between them.For example, /usr/bin/python indicates that one item is stored inside the item preceding it.
10. **using the tab key to complete file paths** on a command line allows you to save time when typing in long path and filenames by simply typing in the first few letter and then press TAB to automatically complete either the folder or filename. It will cycle through each similar name eac time you press TAB.
11. **using up and down arrow for history** allows you to press the up arrow key from the command prompt to see the most recently used command and each additional press moves further back into history, and the down arrow key moves forward in the history file.
## gitFlow and Git commands and terminology
The gitFlow Workflow is a lightweight branch based workflow built around the core Git commands used by teams around the globe. There are six steps to the Workflow. 1) Create a branch, 2) Add commits, 3) open a pull request, 4) Discuss and review code, 5) Merge, and 6) Deploy.
## gitflow illustration ##
![GitFlow Diagram](https://datasift.github.io/gitflow/GitFlowFeatureBranches.png)
1. **git init** - initializes a brand new GIT repository and begins tracking on existing directory.
2. **git clone** - creates a local copy or Clone of a project that already exists remotely. 
3. **git fork** - is a copy of a repository that allows you to freely experiment with changes without affecting the original project.
4. **git branch** - shows the branches being worked on locally.
5. **git commit** - saves the snapshot to the project history and completes the change tracking process.
6. **git merge** - merges lines of development together. This command is typically used to combine changes made on two distinct branches.
7. **git checkout** - allows you to navigate between the branches created by git branch. Checking out a branch updates the files in the working directory to match the version stored in that branch.
8. **git push** - updates the remote repositorywith any commits made locally to a branch.
9. **git pull** - updates the local line of development with updates from ts remote counterpart.
10. **git remote** - helps you to manage connections to remote repositories, allowing you to show which are currently connected, but also add new connections or remove existing ones.
11. **git status** - shows the status of changes as untracked, modified or staged.
12. **Master Branch** - in git, master is the naming convention for a branch, it is a repository default branch. When developers make changes to a branch and a merge is executed the changes in that featured branch combune their changes to the master branch for deployment.
## Sources ##
1. https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
2. https://datasift.github.io/gitflow/IntroducingGitFlow.html
3. https://www.git-tower.com/learn/git/glossary
