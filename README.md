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


if modify on the same line;????? ++++---- modification from feature branch


**Solving merge conflit**


![image](https://user-images.githubusercontent.com/17804600/122664186-17406200-d1a0-11eb-8c31-6d7a74d9f33a.png)

starting from the less-than arrow and above the =, it is the latest change. 

below the = and before the greater-than arrow is the conflicted one

removing the arrows and = signs, and merge both line to be expected and then commit


Introducing changes at the branch main; modified at the same line at the new-feature branch.

something new from new feature branch