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
```

##### 三、错误处理

*`fatal: refusing to merge unrelated histories`*

###### 解决：

```
git pull origin master --allow-unrelated-histories
```



*`fatal: 'origin' does not appear to be a git repository`*
*`fatal: Could not read from remote repository.`*
*`Please make sure you have the correct access rights and the repository exists`*

###### 解决：

```
git remote add origin git@github.com:liylin6688/hello.git
```

