# 常用管理仓库git指令
在需要上传的文件右键夹打开Git

查看仓库状态（红色表示有改动）：git status     

提交文件到git暂存区：get add .

再次查看状态（文件非红表示成功提交到暂存区）：git status

给你的本次提交命名：git commit -m "第一次提交"    

将仓库内容拉到git区合并：git pull origin master  

将合并后的新工程堆到github仓库（更新仓库）：git push origin master       

查看历史提交记录（有记录就成功）：git log --oneline
