#使用github的一些帮助  
## 基本使用  
在github上创建并提交一个项目  
>1.git init -- 在当前目录初始化  
>2.touch README.md  
>3.git add README.md -- 添加文件  
>4.git remote add origin https://github.com/istvzn/Notes.git -- **远程**添加项目origin分支  
>5.git push -u origin master --把本地分支master合并到**远程**分支origin  
>6.git pull 则与git push相反

## 引用
> Quick setup — if you've done this kind of thing before
> Setup in Windows or HTTP SSH
> 	
> We recommend every repository include a README, LICENSE, and .gitignore.
> 
> Create a new repository on the command line
> 
	touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/Orzworker/Notes.git
    git push -u origin master
>
> Push an existing repository from the command line 
> 
	git remote add origin https://github.com/Orzworker/Notes.git
	git push -u origin master
>
> Status API Train