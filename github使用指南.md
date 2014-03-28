#GitHub使用指南
![image](http://a.36krcnd.com/photo/a462f1f368e67d9ebece977eaabe5b32.png)
##GitHub介绍
是一个面向开源及私有软件项目的托管平台  

GitHub于2008年上线，Github是一个从Ruby社区诞生出来的项目，可以说Git在Ruby社区普及和爆发几乎是必然的事情。Git虽然是Linux内核社区开发出来的，但前几年一直不温不火。真正在开源社区普及和爆发，是从Ruby社区和Github开始的。
  
2011年代码提交量对比图
![image](http://www.worldhello.net/gotgithub/images/survival-of-the-forges.png)

托管的项目超过1000万
![image](http://dl2.iteye.com/upload/attachment/0092/4595/7c78a7bd-b175-368f-b0bf-f25ac8b9073c.png)

##注册
![image](images/homepage.png)
##配置SSH Key  
![image](images/configkey.png)

创建sshkey

     $ ssh-keygen -t rsa -C "your_email@example.com"   
     $ pbcopy < ~/.ssh/id_rsa.pub
     
![image](images/addsshkey.png)

##新建项目
![image](images/new_repository.png)
![image](images/created_repository.png)

##Fork  
![image](images/fork_button.png)

备份该项目的副本作为你自己的项目
![image](images/forked.png)

你可以在该项目中上任意修改，不会对原作者的项目造成任何的影响。
![image](images/fork_commit.png)
![image](images/fork_commit1.png)

##Pull Requests
如果想将你的修改合并到原项目中时，可以pull request，这样原项目的作者就可以将你修改的东西合并到原项目的主分支上去，这样你就为开源项目贡献了代码。
![image](images/click_pull_request.png)
![image](images/create_pull_request.png)
一旦你创建了pull_request给原作者，原作者将会收到通知和邮件
![image](images/pull_request_notification.png)
![image](images/merge_pull_request.png)
merge之后
![image](images/merged_pull_request.png)
这样你的代码就成功的被原作者接受

---------------
**GitHub不仅满足了我们代码仓库的需求，另外对项目管理上需要的一些功能也一应俱全**。

##Milestones
创建一个里程碑
![image](images/create_milestones.png)
里程碑一般而言就是对应于一个项目开发计划或者一个软件版本
![image](images/milestones_list.png)
在这里我们可以查看这个里程碑的进度情况

##Issue
Issue跟我们的开发任务紧密相连，通常一个issue会指派给某位开发人员来解决。开发阶段issue会跟milestone进行关联。
![image](images/create_issue.png)
![image](images/created_issue.png)
这里需要注意issue编号。由于每个issue的解决最终会归结到一个代码的commit，GitHub提供给我们了一个快捷的方式，让commit与issue关联起来，你只需要在commit的注释中出现“#xxx”(issue编号)，并且如果在提交说明中的问题编号前出现特定关键字，还可以自动关闭问题。支持的关键字有：
  
+ fixes #xxx
+ fixed #xxx
+ fix #xxx
+ closes #xxx
+ close #xxx
+ closed #xxx

![image](images/closed_issue.png)

##代码评审
##Gist
##github.io
##git.io
      


