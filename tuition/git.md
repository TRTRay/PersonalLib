#### 初始化版本库

将当前目录初始化成git管理的本地仓库

```bash
git init
```



#### 添加管理文件

添加单个文件

```bash
git add filename
```

添加全部文件

```bash
git add .
```



#### 提交至git仓库

提交文件改动

```bash
git commit -m "message content"
```



#### 远程库管理

创建远程库

```bash
//git remote add RepositoryName address
git remote add origin git@github.com:TRTRay/PersonalLib.git
```



#### 推送本地库内容

将master分支的推送至远程库origin

```bash
git push -u origin master
```

