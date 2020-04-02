#### 1、上传本地项目到github
##### 1-1 创建一个本地项目
###### 创建文件夹
##### 1-2 建立本地仓库
###### 进入仓库路径：D:\repositories\diploma  
```
cd d:
cd repositories/diploma/
```

###### 初始化仓库   
```
git init
```

###### 将所有文件添加到仓库  
```
git add .
```

###### 把文件提交到仓库，双引号内是提交注释  
```
git commit -m "first commit"
```

##### 1-3 关联github仓库
###### 到github diploma_graduation仓库复制仓库地址：  git@github.com:liylin6688/diploma_graduation.git  
###### 执行以下指令：
```
git remote add origin git@github.com:liylin6688/diploma_graduation.git
```

##### 1-4 上传本地代码

```
git push -u origin master
```

  

