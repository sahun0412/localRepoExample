# GitTutorial
Learning Git and GitHub
# Author
 Naresh Sahu
 # Setting up GIT
  1. Install Visual Studio Code .
  2. Windows  (Git Bash)
      Chek Version on Successfull download .
      open cmd (git --version )
# Configuring Git 
  1. Open Git Bash
  2.  git config --global user.name "My Name"
  3.  git config --global user.email "Email used to create GitHub"
  4.  Check the configuration :  git config --list
# Open Visual Studio Code
 1.Open Folder in VS Code
 2. Open Terminal (ctrl + ` or ctrl + j )
# Clone and Status
  
  Clone: to clone a repo on local machine
   ssh or http 
  git clone <project link>
 # Remote
  repo on GitHub

# Status
  1. displays the state of code
   git status
  
  2. untracked: new files that git does not tracked  yet .

  3. modified : changed in existing files .

  4. staged: file is ready to be committed .

  5. unmodified : unchanged .

# Add and Commit
  1. Add : adds new changed files/file in your working directory to the Git staging area (i.e. on GitHub Repo) .

  git add <- file name -> or git add . 

  2. Commit : it is the record of change .
   git commit -m "some meaningful message"

  # Push 
   1. Push : upload local repo into remote repo .
    git push origin main 

  # Init Command
   1. mkdir: make new dir in local machine .
   2. init : used to create a new git repo .
     git init
   3. Add  : adds all new files or instead of . you can use file name .
    git add . 

  4. create a new repo on GitHub
  5. add local repo to repo on github
    git remote add origin <- link ->
  
  6. Verify Remote : git remote -v

  7. to check branch : git branch 

  8. to rename branch : git branch -M main 

  9. git push -u origin main : upstream 