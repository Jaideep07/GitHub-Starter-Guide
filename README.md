# GitHub-Starter-Guide
#### 1. Making sure that you installed git correctly
Check out the version installed by using `git --version` command, the output must be similar to this 2.31.1 
#### 2. Setting up git
- Configure it so that the generated commit messages will contain your correct information.
- Use `git config --global user.name "Your Name"` and `git config --global user.email "youremail@domain.com"` and replace with your name and email.
- To check details that you have entered use `git config --list`.
#### 3. Cloning a repo
- Now create a new repo GUI and clone it using the command `git clone repo-address` and replace the address ie. copied from the GUI.
- Now go to the directory that has been created by cloning, use `cd repo-name`.
#### 4. Adding and commiting a file to your reop
- Create any file in this directory and add some contents to it. Check the status of the directory by using `git status`.
- Stage the files using `git add .` here '.' indicates all files, but if you want a single file to be commited you can use `git add filename`.
- Commit the staged files using `git commit -m 'add discription to the commit'`.
#### 5. Pushing the changes to the remote repo
- Once commited, push changes to remote repo using `git push`
- Now that you have pushed you will be prompted to enter you GitHub username and password.
- Go to the GUI and you will find your changes.


