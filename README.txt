终端方式上传项目
1.鼠标右键要打开的项目文件，选择git bash

2.创建本低标记
git init   
//此步骤会生成一个.git文件，该文件默认是隐藏的,如果看不到本地隐藏文件，
可以使用快捷键“command+shift+.”来打开、关闭隐藏文件的显示。

3.将项目中所有文件添加到本地仓库
git add .
如果想添加某个特定的文件，只需把. 换成特定文件名即可

4.添加提交信息备注
git commit -m "此处写备注内容"

5.到git官网新建仓库，并复制git仓库地址

6.将本地仓库与github仓库远程连接起来
git remote add origin git@github.com:Maxlu-xxl/girl-to-orange.git

7.最后一步，上传代码到远程仓库
git push -u origin master

如果失败，将所有文件连同.git一起删除，重新操作一遍

