# git-control-flow

the first commit from remote master 

add a line from local main 

creating a new branch and check it out: git checkout -b feature

**Solving 'having no upstream branch'**

C:\Users\zhaoy\IdeaProjects\git-control-flow>git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use
    
````
    git push --set-upstream origin feature
````


**Solving merge conflit manually**


![image](https://user-images.githubusercontent.com/17804600/122664186-17406200-d1a0-11eb-8c31-6d7a74d9f33a.png)

starting from the less-than arrow and above the = is the latest change that you made from the feature branch. 

below the = and before the greater-than arrow is the target code that conflict with your commited code.

It may remove the arrows and '='signs, and merge both lines as what it should be', and then commit


