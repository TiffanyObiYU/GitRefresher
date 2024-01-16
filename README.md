# Git Refresher 

## Unix Commands
- **ls** : lets us view the contents of the current folder/directory
- **mkdir dir_name** : lets us create a new folder/directory with the given name
- **cd path** : lets us navigate to the designated path (.. lets us go "up" a directory)
- **touch file_name** : creates a new file with the designated name
- **vim file_name** : lets us create or edit a file with the designated name
- **cat file_name** : lets us view the contents of a file
- hint - hitting tab can autofill file names/directories. If there are similar names, hit tab again to see all of the options
- Use arrow keys to go up and down the terminal to previous commands
- Helpful Resource: [http://mally.stanford.edu/~sr/computing/basic-unix.html](http://mally.stanford.edu/~sr/computing/basic-unix.html)

## VIM
- i : lets us insert, edit the file
- esc : takes out of insert mode
- :wq : write/quit & saves the file

# Git
Helpful Resource: [https://www.atlassian.com/git](https://www.atlassian.com/git)
- version control - controlling/managing different versions or snapshots of your code
- great for team-work, but also for solo work, keeping your code in one remote place
- merging ~ being able to take individual code/files/projects from different people
             and combining them together to create one huge project
- Github & Gitlab are websites that host projects using git
- repository - a location where your code is. Usually, a repo only contains one project or even a part of a project
- public repo - everyone can see
- private repo - only certain people can view the repository
- commit - take what we worked on and "save" it to the repo
- **git clone link** : clone or copy everything on a repo to our local machine
- **git status** : tells us which files are not committed, pushed, etc.
- **git add** : adds the changes from unstaged to staged/ready to be committed
    - **git add .** :  the period makes it that all changes made in the current directory become ready to be commited
    - **git add fileName** :  we can specify a particular file/folder whose changes are ready to be commited
- **git commit -m "message"** : commit our staged changes and tag them with the message
- We want our commit messages to be as descriptive as possible (as well as concise)
- **git push** : pushes our code to the repo
- Note: if you are using git bash for the first time, you will probably have to log in using your username and password

**Only use IF you don't already have gitbash/terminal, otherwise ignore this link**
Gitbash - Download using https://git-scm.com/downloads. Right-click anywhere on our desktop or in a folder and select "git-bash here". Then a terminal should pop up.
