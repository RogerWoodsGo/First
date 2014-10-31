git pull: 从其他版本库更新代码到本地，git pull origin master

git add: 将当前更改或者新增的文件加入到git中

git commit: 提交修改

git rm: 删除索引

git push: 提交到远端 git push origin

#GitHub使用
1. 创建一个Respo比如Test
2. 得到地址:https://github.com/wcwu/Test.git
3. 在本地某个目录执行下面命令
    1). git init
    2). git add <file/dir>
    3). git commit -m "commit msg" 
    4). git remote add origin  https://github.com/wcwu/Test.git #添加origin作为本地库，网址作为远端库
    5). git push origin master #本地推送到远端

