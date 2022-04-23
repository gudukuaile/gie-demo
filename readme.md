## 初始化本地库

> git init

![image-20220423171746597](https://gitee.com/nntt/md-img/raw/master/img/202204231717418.png)



## 查看状态

> git status

![image-20220423172440554](https://gitee.com/nntt/md-img/raw/master/img/202204231724150.png)



## 添加文件到暂存区

> git add 文件名(或者.)



## 删除暂存区文件

删除掉git add 添加到暂存区的文件，但不会删除本地文件。

> git rm --cached 文件名称

![image-20220423174546852](https://gitee.com/nntt/md-img/raw/master/img/202204231745891.png)



## 提交版本

> git commit -m "提交信息" 文件名称

![image-20220423175727269](https://gitee.com/nntt/md-img/raw/master/img/202204231757301.png)



## 查看版本信息

1. 简单查看

   > git reflog

   ![image-20220423180038438](https://gitee.com/nntt/md-img/raw/master/img/202204231800473.png)

2. 详细查看

   > git log

   ![image-20220423180252579](https://gitee.com/nntt/md-img/raw/master/img/202204231802610.png)



## 版本穿梭

> git reset --hard 版本号

![image-20220423211940927](https://gitee.com/nntt/md-img/raw/master/img/202204232130196.png)



![image-20220423212103548](https://gitee.com/nntt/md-img/raw/master/img/202204232130524.png)



![image-20220423212126485](https://gitee.com/nntt/md-img/raw/master/img/202204232130945.png)



## 分支

1. 查看分支

   > git branch -v

   ![image-20220423213543535](https://gitee.com/nntt/md-img/raw/master/img/202204232135571.png)

2. 创建分支

   创建分支后，使用查看分支命令，查看是否成功

   > git branch 分支名称

   ![image-20220423213811787](https://gitee.com/nntt/md-img/raw/master/img/202204232138825.png)

3. 切换分支

   > git checkout 分支名称

   ![image-20220423214254972](https://gitee.com/nntt/md-img/raw/master/img/202204232142008.png)

3. 合并分支

   要和并到那个分支，首先需要切换到相应的分支

   > git cheakout master
   >
   > git merge dev
   >
   > 先切换到master分支，再把dev合并到master分支
