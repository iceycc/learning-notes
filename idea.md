## 新的想法 ##
---
## 学会github的基本操作 ##  
1. 注册
2. 简单的命令行操作
3. 下载图形界面客户端
4. 新建一个项目
5. 添加一个版本,备注
6. revert一个版本.回滚,抵消上次的版本操作
7. undo most recent commit 撤销最近提交到changes
8. new branch name 新建一个新的分支
9. default 系统默认的
10. 分支合并有思路有点乱 新版本github要找到update from,分支是为了测试其他代码,测试成功时,合并到主分支,删除即可  	
	  
	分支合并   
	两种方式  merge  rebase  
	1.点击同步操作可以更新远端代码到本地  
	2.发生冲突时会出现冲突标识符，上面head 是本地冲突，下面是远端冲突。修改代码后提交版本即可解决冲突。  

	冲突合并：1、解决冲突，2、制作版本（commit），3、重新同步（sync）  
	冲突标识：  
         head 本地分支  
         origin/master 远端分支  
	同步(sync)含义：share your local commits on the server and retrieve changes from others.
11. 团队工作协作流程团队工作协作流  
	guides.gethub.com//GitHub指南    	
	getbeijing.com/flow/ 翻译的中文版；   
 	1.创建一个新分支；  
  	2.创建一个新版本；  
  	3.开启一个Pull Request；拉取请求； （核心：拉取请求，激发讨论！！！）前提：有分支！！  
	4.代码讨论与审核；  
	5.合并分支，然后部署；	  

	团队内部	  
	首先添加一个写权限，Settings->Collaborators->添加队友；	  
      		
	
12. 团队协作 拉请求  
	pull request:意思是请求项目的维护者拉我这个分支上的代码到master分支上  
	compare & pull request:意思是请求项目的维护者和协作者对我的代码进行比较讨论,是否合适拉我这个分支上的代码到master分支上.  
	在进行pull request之前一定要保证所有的任务都同步到了Github之上。

13.开源项目的贡献流程
	

- 1.将项目fork过来，
- 2.clone到本地仓库，修改信息，
- 3.sysc与远端仓库进行同步，
- 4.在github页面进行pull request提交到开发者哪里，进行协商等待开发者合并。完成后可以将项目删除	
	
	一些细小的修改：Quick Pull Requests
	
	① 普通用户：
	在原文件的网页页面点击编辑，然后系统会自动为你创建一个fork,然后进入Propose file change，直接在页面进行pull request 
	
	② 拥有写权限的用户:
	进行修改,直接把自该写到master分支，第二种，创建分支，然后pull request 
	
	没收到pull request之前查看用户fork修改的方法：，点击Grapha，找到network查看那些用户fork了项目进行了修改  

14.issues		
	
- githhub三大套件
	- issues:创建事务卡片（new issue)  
			
		Issues:创建事务卡片（new issue)
		添加标题和内容，在Assignee中部署谁完成任务
		讨论时，可以@好友进行讨论
		selecting thethem上传图片
	- wiki手册
	- GitPages项目网站  

15.github 搜索 		
 	
	Github Secret
	1,快捷键T，打开检索文件功能。
	2，根据项目来找牛人 
	

16.github学习书籍
	GitHub客户端只能满足一些常见的需求，要更高级必须要学着用Git命令行。 
	《Pro Git》
	github虽不开源，无法部署到自己服务器。
	但，gitLab开源

	
	


