# gitskills

#### 删除远程仓库origin的dev分支

~~~~
git push origin --delete dev
~~~~

#### tag操作

~~~~
#查看 tag 标签
git tag
#切换标签
git checkout v1.0
#创建标签
git tag -a v1.0 -m “commit version 1.0
#加上 -f 覆盖原有的tag 
git tag -f v1.0
#push所有tag到远程仓库：
git push origin –-tags
#push单个tag到远程仓库：
git push origin [tagname]
#删除tag标签
git tag -d v1.0
#从远程仓库上删除 tag 
git push origin :v1.0
git push origin :refs/tags/[tagname]
git push origin –delete [tagname]
~~~~

#### 已经 git commit -m ""，但是备注内容写错了，如何修改备注的信息

~~~~
可以重新去编辑：git commit --amend
~~~~
