---
title: Git Command
date: 2018-01-18 10:26:18
tags:
---
## 分支有关命令
  
   - 查看分支：git branch
   
   - 创建分支：git branch <name>
   
   - 切换分支：git checkout <name>
   
   - 创建+切换分支：git checkout -b <name>
   
   - 合并某分支到当前分支：git merge <name>
   
   - 删除分支：git branch -d <name>
   * 【git 删除本地分支】
   git branch -D br
   * 【git 删除远程分支】
   git push origin :br  (origin 后面有空格)
