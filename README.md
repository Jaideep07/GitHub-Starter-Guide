# GitHub Starter Guide
### Steps for making changes to your Repo
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
### Steps for making a Pull Request
#### 1. Forking the repo
Fork the repo to which you want to make a PR by clicking on this symbol ![alt text](https://github.com/Jaideep07/GitHub-Starter-Guide/blob/main/screenshots/fork.png) on the top right corner of the repo.
#### 2. Now follow the steps 2,3,4,5 mentioned in the above section.
- Your task is to add `[your-name].txt` file to the `collab` folder and then make a PR.  
#### 3. After you make these changes you need to click on the pull request button and make your PR. 
![alt text](https://github.com/Jaideep07/GitHub-Starter-Guide/blob/main/screenshots/PR1.png)
#### 4. After that you will be redirected to this page now again cilck on the `create pull request` button on this page.
<img src="https://github.com/Jaideep07/GitHub-Starter-Guide/blob/main/screenshots/PR2.png" alt="drawing" width="1200"/>

##### Now you can give a message for the PR and then create it.
#### 5. After successfull creation of the PR you will be redirected to this page.
<img src="https://github.com/Jaideep07/GitHub-Starter-Guide/blob/main/screenshots/PR3.png" alt="drawing" width="1200"/>

#### NOTE:
1. This repo displays minimal use of git and if you want to explore more then you can refer online resources. We have uploded a few of them you can check them out as well.<br>
2. Star the repo if you liked our session and for any furthur queries you can ask in the github discussion section.(avoid using teams and whatsapp)<br>
3. Try to Know more about <b>Hacktoberfest</b> [here!](https://hacktoberfest.digitalocean.com/)

##### The video [link](https://amritauniv.sharepoint.com/sites/AmritaCSStar-Studentresearch/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FAmritaCSStar%2DStudentresearch%2FShared%20Documents%2F2020%20First%20Year%20Phase%20I%2FVideos%2FSession%201%2FFirst%20Years%20AI%40amrita%20Meeting%2D20210501%5F214028%2DMeeting%20Recording%2Emp4&parent=%2Fsites%2FAmritaCSStar%2DStudentresearch%2FShared%20Documents%2F2020%20First%20Year%20Phase%20I%2FVideos%2FSession%201&p=true&originalPath=aHR0cHM6Ly9hbXJpdGF1bml2LnNoYXJlcG9pbnQuY29tLzp2Oi9zL0Ftcml0YUNTU3Rhci1TdHVkZW50cmVzZWFyY2gvRWJvS1dNa1ViWWRQcWRjSkR1eVJCTTBCQWFjbm5SSjVCV2hNcURpN1dUMkwxdz9ydGltZT1YbWlTZzhZWjJVZw) for the 1<sup>st</sup> May session.
