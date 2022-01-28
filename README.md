# Git repo for Robosub CSULA

Download and work with this repository.

## Steps
Copy the repository link from the `green code` button. 

Open up your terminal and use the command 

`git clone <Repository Link>`

This will download the repository to your computer. Once you have the repository on your computer you can `cd` into it 
from your terminal by using the command

`cd <Repo>`

Once you are in the repository folder and ready to make changes you want to use the command

`git checkout -b <Branch Name>`

This will create a new branch you can make your changes on. <Branch Name> is whatever you want to call the branch, usually you want to have
a name related to the changes you are making. 
  
You can use the command `git status` to check what branch you are currently on.
  
Once you have done your changes it's time to save them in git, first use the command 

`git add -A` 
  
 which will add all the changes to the staging area. After they are added to the staging area you want to commit them.
  
  `git commit -m <Your message>`
  
  Once this is done you have succesfully updated your branch. <Your message> should explain what changes you committed. 
  
  Now all the changes have been done on your local computer, but your branch is not yet updated in the origin which is github.com
  
  To update the origin you want to do
  
  `git push origin` 
  
  This will probably have you set an upstream branch, so git knows what the upstream branch is. Just follow the instructions in your terminal.
  
  Once all of this is done, you can go to the repository here on github and create a pull request there, where you create a PR (pull request) mergin your own branch into main. 
 





