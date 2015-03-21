# Step 1
 系统windows7，在网站 <h> http://git-scm.com/ </h>下载最新版本，进行安装。
 
# step 2
 在本地磁盘上建立一个文件夹"gitlearn", 打开按右键选择git init
 然后选择git bash，打开编译界面
 
# Step 3
  生成SSH
 
# Step 4 
 关联账号
 git remote add book git@github.com:reinhartzzhang/pythoncamp0.git
 
# Step 5 
 顺序取决于远端是否有文件。
 第一次推送本地master
 git push -u book master
 第一次全部下载远端到本地
 git pull -u book master
 
# Step6 
 以后推送
 git push book master
 
# Step 7
 以后下载
 git pull book master

# Step 8
 从远程克隆
 git clone git@github.com:reinhartzzhang/pythoncamp0.git
 
