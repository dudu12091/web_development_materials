# web_development_materials

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)


## Table of Contents
- [任务](#任务)
- [工具](#工具)
- [后端学习资料](#后端学习资料)
- [前端学习资料](#前端学习资料)
- [会议记录](#会议记录)
	- [1st_meeting](#1st_meeting)
	- [2nd_meeting](#2nd_meeting)
	- [3rd_meeting](#2nd_meeting)
- [受众](#受众)
- [画图](#画图)
- [需求](#需求)
- [功能](#功能)
- [提议](#提议)

## 任务  

>DDL 2020年2月14日

>第二次会议 任务分配：   
两人一组 调换任务 检查补充   
Alen Betty：背景 风险规划 整合文档 受众 调查问卷 分析 文献   
强强 栋栋：画图：各种图 use case ; boundary; data-flow; ER 图   
托比 倍倍：文字描述：用户需求 功能与非功能需求 系统描述 事务需求  

## 工具  

>后端:  
Python & Flask & SQL  

>前端:   
Css & javascript & html  

>手机APP:   
Android studio ?     
纯网站开发/混合开发   





## 后端学习资料
>Sherlock的学习资料:

		flask 快速入门教程 : https://www.youtube.com/watch?v=RWviEK1Si68&list=PLDFBYdF-BxV1G4FBpG1EMyFtbsbZuJOvD

>Bruce的学习资料:

		none


## 前端学习资料

>Toby的学习资料:

		谷歌地图API: https://www.runoob.com/googleapi/google-maps-api-key.html
		JavaScript教程: https://www.w3school.com.cn/js/index.asp
		CSS教程: https://www.w3school.com.cn/css/index.asp
		HTML教程: https://www.w3school.com.cn/html/html_layout.asp

>Park的学习资料:
		
		HTML CSS教程: https://www.bilibili.com/video/av52670599?from=search&seid=13457783868944189566

>Betty的学习资料:
		
		IBM垃圾分类API : https://github.com/IBM/watson-waste-sorter

>Alen的学习资料:
		
		none


## 会议记录



### 1st_meeting

>Documented by Toby  
第一次会议记录在上方的 1st meeting record.docx 文件中  

### 2nd_meeting

>Documented by Betty  
第二次会议记录记录在上方的2nd meeting.docx文件里   
 

>下次开会  
先准备开始requirement 文档 下次开会交 再调换部分    

### 3rd_meeting

>开会准备:  
 第二次会议，我们选出了系统的受众(User). 第三次会议，我们将确定系统的User.
 


## 受众  
>1.上门收垃圾(用户):  
House个人垃圾：一周收一次 临时收垃圾  
公寓(Apartment)负责人：花钱临时收垃圾  
大型垃圾处理站  

>2.垃圾处理公司:  
垃圾运给处理公司 利用         
意义： 盈利 环保  

## 画图 
>用例图：需求描述  
时序图  
活动图  

## 需求   
>先写用户需求  
细化到功能需求  

## 功能   
>路径规划  
简单垃圾分类：拍照 或者输文字 有无API？  
按什么分类  
垃圾桶位置  

>垃圾车时间划分  
1.定时定点（7天）  
2.预约 分段考虑时间点（有记录 没到七天不用去）  
3.优先级 多少户才可以走 收费 实时价格  

## 提议
>情景引入:  
Trash公司是Liverpool的一家垃圾管理公司，主要进行大型的垃圾回收(公寓垃圾回收，学校垃圾回收，个人house垃圾回收等)。Trash公司要求我们建立一个帮助公司处理业务的系统.  
Trash公司希望, 新用户通过 网站(或者手机APP) 提交申请。公司经理看到申请后，撰写初期合同，与用户约定时间商议，签署最终合同。  
合同签署后，公司经理将该用户的公寓加入垃圾管理计划。  
为了方便公司司机回收垃圾，Trash公司希望我们设计一个给司机分配任务，帮助司机规划路线的功能。  
Trash公司发现，很多回收的垃圾没有被正确的分类。导致这一问题的原因之一是，用户对垃圾如何分类没有正确的认识。因此，Trash公司希望提供给用户垃圾分类的功能。  

>Sherlock's  proposal:  
我们设计的系统有两个子系统组成: 用户系统 和 员工系统。用户系统应该与员工系统相互独立。    
1.用户系统  
	




## License

[MIT](LICENSE) © Richard Littauer
