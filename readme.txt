a:工作区
b:暂存区
c:版本库，Head


git diff命令
git diff 		比较a和b
git diff --cached 	比较b和c
git diff HEAD 		比较a和c

git reset和git checkout
git reset HEAD			c覆盖b
git checkout -- <file> 		b覆盖a
git checkout HEAD <file>	c覆盖a,b

git rm
git rm 		删除a和b
git rm --cached 只删除b
rm file		只删除a

版本回退以及切换
git reset --hard HEAD^		返回上一版本
git reset --hard commit_id 	返回指定版本
papapa

