##progit

#### status
```
untracked
tracked 
	unstaged
	committed
	modified
	staged
```
####alias

```
git config global --alias.co checkout

co — checkout
ci — commit
st — status
br — branch
last — log -1 HEAD

```


#### error
```
-  error: src refspec master does not match any.
目录中没有tracked files ，不能提交空目录
git add <file>... 把文件加入跟踪状态
```