# 📘 常用Git仓库指令

![Git Logo](https://git-scm.com/images/logo@2x.png)
*适用于GitHub仓库的标准化操作流程*

---

## 1. 推拉仓库基本操作流程

```bash
在项目根目录右键打开Git Bash

1. 查看仓库状态（红色表示未跟踪文件）
git status
2. 提交所有改动到暂存区
git add .
3. 验证提交状态（绿色表示已暂存）
git status
4. 创建带描述的提交记录（给你的本次提交命名）
git commit -m "第一次提交"
5. 拉取远程最新变更用以避免提交冲突（可能在github网站上修改了一些文件的内容比如readm.md文件.导致和本地文件不同.所以要先拉取合并）
git pull origin master
6. 推送本地提交到远程仓库
git push origin master
7. 查看精简提交历史（有提交记录则成功）
git log --oneline
8.强制推送，覆盖仓库旧内容（慎用）
git push origin master --force
```
## 2. 克隆仓库
```bash
git clone 仓库路径

git clone https://github.com/username/repository.git
```
## 3. 新建仓库
0.github创建新仓库

（以下是Git指令）
1. 删除旧的.git文件夹（保留你的代码文件）
rm -rf .git
2. 初始化全新的Git仓库
git init
3. 添加所有文件到暂存区
git add .
4. 提交初始版本
git commit -m "1.0"
5. 关联新仓库的远程地址
git remote add origin https://github.com/你的用户名/XingYun-Clean.git
6. 强制推送到新仓库（因为是全新仓库，不需要--force）
git push -u origin master



## 序号. 名称（模板）
```bash

示例

```



