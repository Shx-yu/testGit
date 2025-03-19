# testGit
通过hash--合并（指定某次提交的）分支

# 查看feature分支的提交历史
git checkout feature
git log --oneline

# 假设找到的提交哈希值是abc123
# 切换到main分支
git checkout main

# 合并指定提交
git cherry-pick abc123

# 如果有冲突，解决冲突后继续
# git add <解决冲突的文件>
# git cherry-pick --continue
