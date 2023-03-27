工作区
↓
暂存区
↓
本地库

vscode
从master上创建分支 - yunis
修改文件 - 暂存更改 - 输入备注 - 提交
切换master - 点击...  - 分支 - 合并分支 - yunis


git init - 初始化文件夹
vim dir - 创建/打开 文件/夹
:wq - 保存文件
git status - 查看工作区文件状态
ll - 查看文件列表
cat dir - 查看文件最后一屏内容
git add dir - 添加文件到暂存区
git rm --cached dir - 从暂存区删除文件
git commit -m "提交信息" dir - 提交文件到本地库

git reflog - 查看版本信息
git log - 查看版本详情

版本穿梭
git reset --hard (版本)

分支
git branch -v - 查看分支
git branch 分支名 - 创建分支
git checkout 分支名 - 切换分支
git branch -d 分支名 - 删除分支
git merge 分支名 - 合并分支(master和hot-fix)

合并分支冲突 - 需要人为干预 - 进入vim 决定取舍
status为红
重新commit 不需要文件名

创建远程库
远程库名最好和项目名相同
git remote -v - 查看别名
git remote add 别名 https - 创建别名
git branch -d - 查看所有远程分支
git branch -D - 强制删除分支
git push origin --delete (remotes/origin/分支名) - 删除远程分支


推送远程库 - 需要切换到master分支
git push 别名 master

拉取远程库
git pull 别名 master
git status - 是否被覆盖

克隆远程库 - 不需要登陆
git clone https
完成 拉取代码 初始化本地仓库 创建别名（origin）

邀请加入团队 - 需要删除凭证
settings 添加成员，同意加入

