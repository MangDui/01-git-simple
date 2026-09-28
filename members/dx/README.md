# 我的 Git 学习笔记

## 第一次 Git 实验总结

1. `git add` 的作用是：将工作区的修改加入暂存区，标记待提交的文件。
2. `git commit` 的作用是：将暂存区中的改动保存为本地仓库的版本快照，生成commit记录。
3. 本次实验中 `git restore notes.md` 的作用是：把  notes.md  这个文件从暂存区、最近一次提交的状态还原回工作区，丢弃对它做的、尚未提交的修改。
4. `commit` 与 `push` 的区别是：commit仅在本地仓库创建版本；push将本地版本上传到GitHub远程仓库。