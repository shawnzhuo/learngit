Git 分布式版本管理系统


git理解原理

通过 “ 中间区” 和 “主保存仓库” 进行版本管理，
修改的文件，需先添加到中间区stage， 然后再提交到主仓库

可以进行修改，回退，删除，提交等版本管理


使用：


#注册
 全局用户名，全局邮件联系人

$ git config --global user.name "Your Name"$ git config --global user.email "email@example.com"


#创建新库, 因为叫repository
(就是管理目录和文件的版本)
init
初始化：
选择一个目录作为新库
使用git init
$ git init





Add
拷贝文件到库目录
然后注册添加到git的中间区
$ git add readme.txt


Commit
使用commit的把所有中间区文件提交到主库
$ git commit
$ git commit -m "wrote a readme file"




Checkout
就是回退（或者取出）到当前最新的一个版本
1、回退和主库一致
2、另外是回退和 中间区 一致，条件是已提交到中间区


标签tag
就是主库某个时刻的版本号
与commit的区别是，标签是名称，commit是数字不容易记忆

分枝
另起一个主库版本


工作区，未提交的文件
暂存区，中间缓存文件，add提交后的
Master正式区， 正式提交保存文件，commit提交后
为什么Git添加文件需要add，commit一共两步呢？因为commit可以一次提交很多文件，所以你可以多次add不同的文件

用户住目录：
/c/Users/shawnzhuo/.ssh/


Github
互联网远程 主库；

别人远程主库----克隆----自己远程主库-----get---本地主库




要关联一个远程库，使用命令
git remote add origin git@server-name:path/repo-name.git；
git remote add origin git@github.com:shawnzhuo/learngit.git


关联后，使用命令第一次推送master分支的所有内容；
git push -u origin master

此后，每次本地提交后，只要有必要，就可以使用命令推送最新修改；
git push origin master


github克隆到本地库
git clone git@github.com:shawnzhuo/gitskills.git


