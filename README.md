# gitLabsRepo
# Lab 1


#### 1- Create a SSH key and put the key in GitHub
ssh-keygen -t ed25519 -C "yossr.khatab5@gmail.com"
clear
cat ~/.ssh/id_ed25519.pub
![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/ssh-key-generated.png)
![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/publiC-Key.png)
![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/add-SSH-key-in-github.png)
#### 2- Create a new local repo and a remote repo on GitHub, then make a file contains your full name, then push it to the remote repo, and send an invitation to me.
git init
git add .
git commit -m "first commit"
git remote add origin git@github.com:yossrmohammed/firstRepo.git 
git push master
git push origin master

![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/push-first-repo.png)
![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/invitation.png)
#### 3-Host your project with github pages
git clone git@github.com:yossrmohammed/yossrmohammed.github.io.git
echo "Hello World" > index.html
git add .
git commit -m "Initial commit"
 git remote add origin git@github.com:yossrmohammed/yossrmohammed.github.io.git
git push -u origin main

![UNFOUND](https://github.com/yossrmohammed/gitLabsRepo/blob/master/lab1/githubpages.png)

