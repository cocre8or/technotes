# Git Notes
<details>
  <summary>Git Setup steps</summary>

  1. Install Git for [Windows](https://gitforwindows.org/), Mac OS should already have Git installed.

  2. Verify you have git installed by running this command in the terminal: `git --version`

  3. Initialize your git config if you have not done so already.

  		-- Run `git config --global user.email "your-email"`
  
  		-- Run `git config --global user.name "Your Name"`

  After initializing your git config file, open the `.gitconfig` file in `C:\Users\your_user_id\`.

  4. Create a directory to store repos and navigate to the folder in the terminal before running the clone commands.
</details>
<details>
  <summary>Git Commands</summary>
	
| Purpose | Command |
| --- | --- |
| See your version of git | git --version |
| Set your username for git globally for all repos | git config --global user.name "Your Name |
| Set your email for git globally for all repos | git config --global user.email "your-email" |
| Copy the files from a repo to another repo | git clone URL_TO_REPO |
| Once you have a project folder set up git for it | run git init while in dir of the new project |
| View status | git status |
| Stage a file | git add filename |
| Stage all new files or modified files | git add --all |
| Get the latest of the branch project you are in | git pull |
| Push files to origin | git push |
| Commit staged files | git commit -m "Comment" |
| View history of commits | git log |
| Create a new branch | git branch branch_name |
| Checkout a branch | git checkout branch_name |
| Merge a branch to master | git branch master <br> git merge fix_branch |
| Delete a branch | git branch -d branch_name |
</details>
