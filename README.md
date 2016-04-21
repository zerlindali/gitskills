# gitskills
##git相关语法##
#####查看工作区状态#####
git status
#####把文件修改添加到暂存区#####
git add readme.txt
#####提交更改,把暂存区的所有内容提交到当前分支#####
git commit -m 'understand how stage works'
#####将本地库的内容推送到远程库#####
git remote add origin git@github.com:ligui989/gitskills.git --第一次推送时,给远程库取一个别名,后面推送就使用这个名字.   
git push origin master
#####将远程库克隆到本地库#####
git clone git@github.com:ligui989/gitskills.git
#####创建分支dev#####
git branch dev
#####切换到分支dev#####
git checkout dev
#####创建分支dev,并切换到新分支#####
git checkout -b dev
#####查看当前分支#####
git branch
#####合并分支#####
git merge dev
#####删除分支#####
git branch -d dev

