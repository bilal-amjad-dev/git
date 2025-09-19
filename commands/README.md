

**Download git**
```bash
https://git-scm.com/downloads
```


**Git version**
```bash
git --version
```


**Git configure**
```bash
git config --global user.name "Your Name"
git config --global user.email "Your email"
```



**Git init**
```bash
git init
```

**Git clone**
```bash
git clone <repository-url>
```

**or** 

**Git remote add origin**
```bash
git remote add origin https://github.com/your-github-username/your-repo-name.git
```



**To add files from working directory to staging area**
```bash 
git add <file-name>
```

**To commit files from staging ara to local repository**
```bash
git commit -m "commit message"
```

**To push files from local repository to remote repository**
```bash
git push -u origin main
```




**To see git status**
```bash
git status
```


**To see changes between working directory and staging area**
```bash
git diff
```


**To see commit logs**
```bash
git log
```


**To create new branch**
```bash
git branch <branchname>
```

**Switch to new branch**
```bash
git checkout <branchname>
```
```bash
touch test2.txt
```
```bash
git add .
```
```bash
git commit -m "added test2.txt"
```
```bash
git push -u origin <branchname>
```


**To merge new branch into main**

> Notice here when you are merging to master you have to first ` git checkout master` and then you have to say `git merge and <branchname>` 

```bash
git merge <branchname>
```
```bash
git push -u origin main
```


**Delete branch**
```bash
git branch -d <branchname>
```
```bash
git push origin --delete <branchname>
```










