##### 1、COMMIT

```
    git init 
    git add . 
    git commit -m "first commit" 
    git remote add origin git@github.com:liylin6688/hello.git
    git push -u origin master
```

##### 2、DOWNLOAD

```
    git clone git@github.com:liylin6688/hello.git
OR
    git init
    git remote add origin git@github.com:liylin6688/hello.git
    git pull origin master
```

##### 3、ERROR PROCESSING

```
    fatal: refusing to merge unrelated histories
SOLVE：
    git pull origin master --allow-unrelated-histories
```

```
    fatal: 'origin' does not appear to be a git repository
    fatal: Could not read from remote repository.
    Please make sure you have the correct access rights and the repository exist
SOLVE：
    git remote add origin git@github.com:liylin6688/hello.git
```

```
    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'git@github.com:liylin6688/hello.git'
SOLVE：
    git fetch origin master
    git merge origin master
    :wq
    git push origin master
OR
    git pull origin master
    :wq
    git push origin master
```

##### 4、ACCOUNT

```
    git config --global user.name "liylin6688"
    git config --global user.email "liylin6688@qq.com

    ssh-keygen -t rsa -C “liylin6688@qq.com”
```

