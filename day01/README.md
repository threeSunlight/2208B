# 1. 将git安装到本地
# 2. 配置ssh(公钥和秘钥)
# 3. 创建远程仓库
# 4. 远端仓库克隆到桌面
# 5. 将本地修改的代码上传至远程仓库


备注: 当我们不知道自己所处哪个分支的时候  vscode有插件提供,帮我们快速的确定自己处在哪个分支上






# 总结命令
 1. 将远端仓库克隆至本地:
     git clone xxxxx

 2. 将本地代码上传至远程仓库使用的命令
    git add . (将所有新增的文件全部放到暂存区)
    git status // 查看暂存区是否有代码储存
    git commit -m '新增了一个md文档'
    git remote add origin https://github.com/threeSunlight/demo3.git
    git push -u origin main
