 #Step 1
 系统windows7，在网站 http://git-scm.com/，下载最新版本，进行安装。
 
 #step 2
 在本地磁盘上建立一个文件夹"gitlearn", 打开按右键选择git init
 然后选择git bash，打开编译界面
 
 生成SSH
 
 #关联账号
 git remote add book git@github.com:reinhartzzhang/pythoncamp0.git
 
 第一次推送本地master
 git push -u book master
 
 第一次全部下载远端到本地
 git pull -u book master
 
 以后推送
 git push book master
 
 以后下载
 git pull book master
 
 
 从远程克隆
 git clone git@github.com:reinhartzzhang/pythoncamp0.git
 