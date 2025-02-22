# 📘 常用Git仓库管理指令

![Git Logo](https://git-scm.com/images/logo@2x.png) *适用于GitHub仓库的标准化操作流程*

## 🚀 基本操作流程

```bash
# 在项目根目录右键打开Git Bash
# 1. 查看仓库状态（红色表示未跟踪文件）
git status

# 2. 提交所有改动到暂存区
git add .

# 3. 验证提交状态（绿色表示已暂存）
git status

# 4. 创建带描述的提交记录（给你的本次提交命名）
git commit -m "第一次提交"

# 5. 拉取远程最新变更用以避免提交冲突（可能在github网站上修改了一些文件的内容比如readm.md文件.导致和本地文件不同.所以要先拉取合并）
git pull origin master

# 6. 推送本地提交到远程仓库
git push origin master

# 7. 查看精简提交历史（有提交记录则成功）
git log --oneline
