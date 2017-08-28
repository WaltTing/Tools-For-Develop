# 用Git来上传操作本地的文章

## 1.创建本地仓库
在任意文件夹下：

	git clone "仓库路径"

比如：我的github仓库Tools-For-Develop的url是 [https://github.com/WaltTing/Tools-For-Develop](https://github.com/WaltTing/Tools-For-Develop)。
那么我可以这样：

	git clone https://github.com/WaltTing/Tools-For-Develop

这样就会在本地上检出那个仓库的文件。

## 2.将文件添加到这个仓库
将文件添加到和README.md同级的目录下：   
第一步：将当前更改或者新增的文件加入到Git的索引中  
 
	git add .

"."表示所有的更改。如果只提交一个文件，比如提交“me.txt”，则可以：

	git add "me.txt"
第二步：提交当前工作空间的修改内容

	git commit -m "备注"   

注：“ ”表示你对你操作的备注，将会出现在github仓库文件的后面。

第三步：将本地commit的代码更新到远程版本库

	git push -u origin master

## *3.其他的操作

删除一个文件：

 	git rm '文件名' -r


