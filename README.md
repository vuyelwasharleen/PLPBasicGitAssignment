# PLPBasicGitAssignment

# PLP Basic Git Assignment

## Requirements

- A GitHub accountof which already i had one.
- Git installed already.


## Task 1: Repository Setup

### GitHub Repository Creation

1. Log in to your GitHub account.
2. Create a new repository on GitHub named `PLPBasicGitAssignment`.
3. Initialize the repository with a README file.

## Task 2: Local Setup

### Local Folder Setup

1. Create a new folder on your local machine named `PLPBasicGitAssignment`.
   - **Windows:**
     - Open Git Bash.
     - Run: 
       ```bash
       mkdir PLPBasicGitAssignment
       cd PLPBasicGitAssignment
      
### Git Initialization

1. Initialize a new Git repository in your local folder.
   ```bash
   git init

 
### connecting to GitHub
git remote add origin https://github.com/vuyelwasharleen/PLPBasicGitAssignment.git

### Creating a File
echo "Hello, Git!" > hello.txt

### Commiting Changes
git add hello.txt
git commit -m "Add hello.txt with a greeting"

### Pushing to GitHub
git push -u origin main
got an error 
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/vuyelwasharleen/PLPBasicGitAssignment.git'
how to solve this issue.

git branch
git push -u origin master

### Verify the Repository
Confirm that the hello.txt file and commit message are visible.



