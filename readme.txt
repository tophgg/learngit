git log 
查看提交历史

git reflog
查看最近的git命令历史记录 由近到远

git reset --hard [commit id]
回滚到某一commit id的版本，commit id可由git reflog/log查看

git checkout -- xx.txt
取当前分支最新的版本，清除工作区的修改。如果暂存区为空，则可以清空。若暂存区有等待提交的文件则可以执行 git reset HEAD xx.tx将暂存区清空，然后再执行以上命令清除工作区。