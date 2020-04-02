##### 一、提交

```
    git init 
    git add . 
    git commit -m "first commit" 
    git remote add origin git@github.com:liylin6688/hello.git
    git push -u origin master
```

##### 二、下载

```
    git clone git@github.com:liylin6688/hello.git
或者
    git init
    git remote add origin git@github.com:liylin6688/hello.git
    git pull origin master
```

##### 三、错误处理

```
    fatal: refusing to merge unrelated histories
解决：
    git pull origin master --allow-unrelated-histories
```

```
    fatal: 'origin' does not appear to be a git repository
    fatal: Could not read from remote repository.
    Please make sure you have the correct access rights and the repository exist
解决：
    git remote add origin git@github.com:liylin6688/hello.git
```

```
    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'git@github.com:liylin6688/second.git'
解决：
    git fetch origin master
    git merge origin master
    :wq
    git push origin master
或者
    git pull origin master
    :wq
    git push origin master
```