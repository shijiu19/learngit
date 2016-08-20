echo "# learngit" >> README.md
git init
git add README.md
git commit -m "first commit"

Creating a new branch is quick AND simple
no fast forward
#合并分支时，加上--no-ff参数就可以用普通模式合并，合并后的历史有分支，能看出来曾经做过合并，而fast forward合并就看不出来曾经做过合并。
git branch -d dev:
