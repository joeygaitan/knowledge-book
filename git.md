# how to add your code a git hub repo

* ```git add .``` adds current folder you are in 
* ```git commit -m "message of your choice``` message that will be displayed saying what you changed on github
* ```git push origin nameOfBranch``` push changes to the current branch you're working on

## how to create and switch branches

* ```git checkout -b newBranchName``` creates new branch
* ```git checkout branchYouAreMoving too``` go to another branch

## Tips

* So your computer can be out of sink with github. So you need git pull or update your end with the most up to date end by pulling it down from github
- You do this by doing ```git pull origin nameOfCurrentBranch```

<br/>

* if you wish too merge please use visual studio code and then ```git pull origin mergingBranch``` in the branch you are merging with. It will then show either merge conflicts on the 3 node looking tree in github. So, fix those then try it again and it should work. After that git checkout into that branch go into the branch. Then do ```git checkout merge lastBranchYouWereIn```. 