# **Summary for Important Git Commmands**


## **"git push --force"**
#### **this will push even if  you change the history**
#### **like you pull and then do rebase -i and push this**
#### **not allowing because you change the history that** 
#### **in the remote but now you can**
<hr/>

## **"git push --force-with-lease"**
#### **will check first if the last commmit in the remote is**
#### **yours so you dont delete work of any body else**
### **VERY VERY GREAT OPTION** 


<hr/>

## **"git add -p fileName"**
#### **will ask you in each connected chunck of lines if**
#### **you want to add them to staging area or not**
#### **so you can add half of the file to this commit and** 
#### **another half to the second commit this usefal if there is more**
#### **that one edit the same file so you need to take just your**
#### **own changes to cur commit**

<hr/>


## **"git cherry-pick commit-hash1 commit-hash2"**
#### **add this commits changes to my carrent branch**
#### **create new commits that have this changes on top of**
#### **your current commits** 
### **you can add range of commits also**
## **"git cherry-pick commit-hash1^..commit-hash2"**
#### **powerfull command**




