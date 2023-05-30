
# 第一趴: 简单了解git

# 1. 将git安装到本地
# 2. 配置ssh(公钥和秘钥)
# 3. 创建远程仓库
# 4. 远端仓库克隆到桌面
# 5. 将本地修改的代码上传至远程仓库


# 第二趴  分支管理
### 1. 主分支: 公司中也有叫master分支的
### 2. 公司实际开发过程中的环境介绍
    (1). development (开发环境)
    (2). test    (测试环境)
    (3). stage   (灰度环境,备机环境,半线上环境)
    (4). production (线上环境,全量)
对应的分支
  developemt 分支
  testing  分支
  stageing 分支
  production 分支
  master分支

### 3. 创建分支
    #### 3.1 本地创建分支
       1. 新建分支 git branch <name>(分支名)
       2. 切换分支 git checkout <name>(分支名)
         2.1 组合命令  创建并切换分支  git checkout -b <name>(分支名)
       3.将本地创建的分支,提交到远程仓库 git push origin <name>
    #### 3.2 远端创建分支
    远端创建分支,本地如何更新
        执行git pull
备注: 当我们不知道自己所处哪个分支的时候  vscode有插件提供,帮我们快速的确定自己处在哪个分支上


### 4. 合并分支
 需求: 把wbj_dev分支合并到development分支
 1. 先切换到developpment分支,在执行git merge wbj_dev





# 总结命令
 1. 将远端仓库克隆至本地:
     git clone xxxxx

 2. 将本地代码上传至远程仓库使用的命令
    git add . (将所有新增的文件全部放到暂存区)
    git status // 查看暂存区是否有代码储存
    git commit -m '新增了一个md文档'
    git remote add origin https://github.com/threeSunlight/demo3.git
    git push -u origin main
    git branch name
