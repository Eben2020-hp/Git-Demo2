# Demonstration of Git

This Repository is used as a Demo repository that I will be accessing from VS Code for learning all about Git. In this Demo we will be creating a repo from our local machine and pushing it to GitHub.


Now the previous Repository was created by us from Github. Let's see how to create a repo from our local machine.
- First off create a Folder. Then even if you use ls -la or la you will see that there is no hidden git Folder.
- Next we will create a file.

- After that to make this into a git repo then we can use <git init>. THen we can try git status. And then add the untracked files using <git add .>.
- Then we can commit using <git commit -m "">.
- After this we can't directly push this as we didnt clone this down from a git repository. So we need to first create a repository in Github and then copy the SSH or the HTTPS url and then pass in <git remote add origin <HTTPS url>>. We can check this using <git remote -v>. 
- Now we can use <git push origin master> or we can use the shortcut which is <git push -u origin master>, This way in the future we can just use <git push>.