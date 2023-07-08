# Setting up Git and GitHub
This is the process to create a GitHub account and a Git repo and clone it and update it.

## GitHub Account
You can make an account at [github.com](https://github.com). Here are the steps:

### Create an Account
1. Go to [github.com](https://github.com)
2. Click on Signup
3. Enter info: 
   - Email
   - User name
   - password
4. Submit
    

## Github Repo

### Create a Repo
- Click on "Create a new repository"
- Give Repository Name
- Add README file
- Click on "Create Repository"

How to add README and initialize manually
```bash
echo "# fuzzy-doodle" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/VSK4000/fuzzy-doodle.git
git push -u origin main
```

How to push an existing local repository to a new github repository
```bash
git remote add origin https://github.com/VSK4000/fuzzy-doodle.git
git branch -M main
git push -u origin main
```


 
## Install Git for Windows
- Go to [git-scm.org](https://git-scm.org)
- Downloads
- Click on Windows
- Download "64-bit Git for Windows Setup"
- Install the downloaded package
- 

## Github Clone
### Clone the Repo
- On your github page, click on "Code"
- Copy link under HTTPS
- Go to Terminal
- In the Terminal window, navigate to the containing folder in which you want to put the repo
- Run command :
-  `git clone https://github.com/<User name>/<Repo Name>.git [Folder name]`
    - Eg: `git clone https://github.com/VSK4000/MyFirstRepo.git hello-world`

## VSCode
    
### Editing the README

## Github Commit Changes
### 4. Update