--1.Git Configuration commands

1.1git config --global user.name

SYNTAX :git config --global user.name "NAME"

PURPOSE :sets the username that will be associated with your git commands

EXAMPLE : git config --global user.name "Priyanka"

1.2git config --global user.email

Syntax : git config --global user.email "youremail@example.com"

Purpose :Sets the email address that will be associated with your Git commits.

Example : git config --global user.email "priya@example.com"

1.3 git config --list

Syntax :git config --list

Purpose : Displays all Git configuration settings including username, email, and other options.

Example : git config --list

1.4 git config --unset

Syntax: git config --unset user.name

Purpose: Removes a configuration value from Git settings.

Example: git config --unset user.name

2\. Repository Setup Commands

2.1 git init

Syntax : git init

Purpose : Initializes a new Git repository in the current directory.

Example : git init

2.2 git clone

Syntax : git clone repository-url

Purpose : Creates a copy of an existing remote repository to your local system.

Example : git clone https://github.com/username/project.git

2.3 git clone --branch

Syntax : git clone --branch branch-name repository-url

Purpose : Clones a specific branch from a repository instead of the default branch.

Example : git clone --branch main https://github.com/username/project.git

2.4 git clone --depth

Syntax : git clone --depth number repository-url

Purpose : Clones the repository with a limited commit history to reduce download size.

Example : git clone --depth 1 https://github.com/username/project.git

3\. Repository Status \& Inspection Commands

1\. git status

Syntax : git status

Purpose : Shows the current state of the repository such as modified files, staged files, and untracked files.

Execution

Example : git status

2\. git log

Syntax : git log

Purpose : Displays the complete commit history of the repository.

Execution

Example : git log

3\. git log --oneline

Syntax : git log --oneline

Purpose: Shows the commit history in a short single-line format.

Execution

Example : git log --oneline

4\. git log --graph

Syntax : git log --graph

Purpose : Displays commit history with a graphical representation of branches and merges.

Execution Example: git log --graph

5\. git show

Syntax : git show

Purpose : Displays detailed information about the latest commit including changes made.

Execution Example : git show

6\. git diff

Syntax : git diff

Purpose :Shows the differences between working directory files and staged files.

Execution Example : git diff

7\. git diff --staged

Syntax : git diff --staged

Purpose : Displays differences between staged files and the last commit.

Execution Example : git diff --staged

8\. git blame

Syntax : git blame filename

Purpose:Shows who modified each line of a file and when it was changed.

Execution Example:git blame test.txt

9\. git reflog

Syntax:git reflog

Purpose : Shows the history of all actions performed in the repository such as commits, checkouts, and resets.

Execution Example : git reflog

10\. git shortlog

Syntax : git shortlog

Purpose : Displays a summary of commits grouped by author.

Execution Example : git shortlog

4\. File Tracking Commands

1\. git add

Syntax : git add filename

Purpose : Adds a specific file to the staging area before committing.

Execution Example: git add test.txt

2\. git add .

Syntax :git add .

Purpose : Adds all modified and new files in the current directory to the staging area.

Execution Example : git add .

3\. git add -p

Syntax : git add -p

Purpose : Allows interactive staging of changes (you can choose which changes to add).

Execution Example : git add -p

4\. git restore

Syntax : git restore filename

Purpose : Restores a file in the working directory to the last committed version.

Execution Example : git restore test.txt

5\. git restore --staged

Syntax : git restore --staged filename

Purpose:Removes a file from the staging area but keeps the changes in the working directory.

Execution Example : git restore --staged test.txt

6\. git rm

Syntax : git rm filename

Purpose : Removes a file from both the working directory and the repository.

Execution Example:git rm test.txt

7\. git mv

Syntax : git mv oldname newname

Purpose : Renames or moves a file and tracks the change in Git.

Execution Example : git mv test.txt newfile.txt



