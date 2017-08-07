
1.创建一个文件夹作为本地仓库，比如新建一个Blog文件夹。  
2.初始化文件夹，输入
> git init

3.将远程仓库的文件夹clone到这个文件夹中
> git clone https://github.com/WaltTing/Tools-For-Develop  
 
4.将要上传到远程仓库的文件加入到该文件夹下   
如果需要修改  
编辑完成之后，再往README.md中插入超链接：

> https://github.com/WaltTing/Tools-For-Develop/用README.md为仓库创建目录.md

5.依次执行以下操作

> git add 文件名.md

将文件提交到本地的版本库中，引号里面的add可以自定义，是要提交的说明。

> git commit -m "add"

最后将本地仓库的内容提交到github远程仓库。

> git push -u origin master


