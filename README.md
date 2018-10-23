# GitHub Tutorial

by Daniel Zhao

---
## Git vs. GitHub
Git takes different versions of code but it doesn't require Github. However, Github needs Git in order for it to work. Github helps user store their code in this online hard drive or also known as "clouds" in the Github website. 


---
## Initial Setup
1. [Go to Github and sign up for an account](https://github.com/join?source=header)
2. Create a username of your choice (_HSTAT students usernames are based on their HSTAT emails but exclude @hstat.org at the end_) and make sure it is not taken by checking for a green check sign on the right
3. Enter your email address. (_HSTAT student use your HSTAT email_)
4. Create a password (_Create a password of your choice)_
5. Select the _**Unlimited Public Repositories for Free Plan**_
6. Check off the boxes that applies to your workflow and preferences.

**SSH Key** -
  SSH key is used in github to make a clone of another programmers file. Under _**Clone or download repository**_ you would select SSH key, and copy the URL. Then, take the URL that you have copied and transfer it to your workspace by entering; ```git clone url``` and paste the URL that you have copied after the clone in git clone.

--- 
### Post Account setup:
   1.  On the top right corner, click on the settings option
   2.  Then click on SSH and GPG keys
   3.  After you clicked on the SSH and GPG option, you'll then click on the green that says, **New SSH Key**
   4.  Next go to cloud9 home page and click on the gear icon located at the top right 
   5.  Click on the SSH tab on the left side bar, or [click here](https://c9.io/account/ssh)
   6.  Copy all the information that is inside the first box
   7.  Lastly, go back to your Github SSH and paste it into the empty box.
    
---
#### Repository Setup
1. [Sign in to Github account](https://github.com/login)
2. Click on the green button that says _**New Repository**_
3. Under _**Repository name**_ enter a name that you would like to name your repository. It has to be the same as your file in c9
4. Select a _**Public**_ or _**Private**_ repository 
5. After selecting your preferences for your repository, click on _**Initialize this repository with a README**_
6. Then the _**Create repository**_ will turn green and click on it to create your repository

#### Collaboration
**Fork** - Forking will make a copy of someone else's remote and this will make your own person remote.   
**Clone** - Cloning is basically making a copy of your remote into your workspace by entering ```git clone (URL)``` 
**Pull Request** - Pull request is basically asking another programmer to have permission to push their Github repository. To start you have to do fork and clone from that persons repository. After making all the changes that you would like to do, you would have to ```git commit -m "message"``` and ```git push``` into your local repository.  
**Pull** - This will take all the changes that have been made and uploads it to the local repository.






---
## Workflow & Commands
**Status** ```git status```  
-  (Git status checks if certain changes are added to a file or in the staging area in order to be able to commit. Its basically checks everything that your doing)  

**Add**  ```git add.```  
-  (Git add takes all the entire directory and adds it to the changes that have been made.)  

**Commit**  ```git commit -m "message"```    
-  (Git commit is used to record changes that has been made in the repository. The message is used to describe the modifications that have been made in the current directory.)

**Push**  ```git push```  
-  (Git push is used to upload commits that have been made from a local repository and uploads it to the remote repository.)

---
## Rolling Back Changes
`git checkout -- filename`: Undo the changes in the file  
`git reset HEAD filename`: Unstage the file you had just added from staging area  
`git log`: This will undo pushes   
`git reset --soft HEAD~1`: Undo the commit you had just committed
