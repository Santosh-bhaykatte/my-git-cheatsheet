# Git Workflow

## 🔧 Basic File & Folder Operations (Windows CMD)

```bash
echo "message" > file-name             # Create new file in current directory
mkdir folder-name                      # Create new folder inside current directory
echo "message" > folder-name/file-name # Create new file inside the new folder
start file-name                        # Open file in current directory
start folder-name/file-name            # Open file inside folder
```
## Git Commands

```bash
git status                  # status of git
git remote -v               # remote repository in use
git add file-name           # Allow git to track the new file
git commit -m "Message"     # Commit with a message
git push origin main        # Push for the first time to remote
```

## 🚀 Steps to Push Code to a New Repository (First Time)

```bash
cd path/to/your/project                # Go to the correct project directory
git init                               # Initialize the repo:
git add .                              # Add all files
git commit -m "Initial commit"         # Commit message
git remote add origin https://github.com/your-username/your-repo.git    # Connect to your GitHub repo:
git branch -M main                     # Set branch to main
git push -u origin main                # Push code to GitHub:
```


## fetch and merge changes from remote repo
```bash
git pull origin main
git add .
git commit -m ""
git push
```




