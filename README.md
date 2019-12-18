# 测试git命令
- 使用情景：本地库.git 被删除，且在本地文件夹写入了新的文件
    1. git remote add origin '库链接'
    2. git fetch origin 先获取远程代码(可能也包含日志文件)
    3. git reset 'commit id'    要是最新的commit id,不然会出现本地库与远程库不一致，需要使用git pull 解决