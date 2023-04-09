学生选课系统（一个JavaWeb入门级项目）
![image](https://user-images.githubusercontent.com/55183556/230774155-0bc9575b-f433-4a78-b3db-90723f592fbe.png)
![image](https://user-images.githubusercontent.com/55183556/230774159-c78c75a8-b69e-4776-800d-916633259d28.png)
![image](https://user-images.githubusercontent.com/55183556/230774164-65a007a9-94dd-499c-b2d5-775807b80736.png)

要求具备如下知识：
Java基础
前端基础（Html、css、JavaScript、Jquery）
mysql数据库
Web容器（Tomcat）
Jsp/Servlet

通过该项目可以掌握哪些知识：
掌握整个项目的流程
掌握开发中的简单权限控制
掌握前端页面如何与后端整合
宏观把握一个项目
掌握echarts图表技术

技术选型
Web容器：Apache Tomcat8.5
编程语言：Java8
数据库：MySQL5.6
开发IDE：Eclipse
数据库连接池：DBCP
数据库操作：DBUtils
动态网页：JSP/Servlet3.1
静态网页：HTML+CSS+Jquery
数据库设计软件：Power Designer
操作系统：Window/Linux

需求描述
角色：学生、老师、管理员

1）学生：基本信息+课程信息

操作流程

学生登录系统
选择课程并提交确认（确认之后则不能修改了）
考试系统
各种查询（查询各科成绩、查询总成绩、查询排名等
操作功能 

各科成绩查询
总成绩查询
成绩排名、各科成绩排名
 
2） 老师：基本信息+所教课程

登录系统
课程管理
考试成绩录入
各种查询（学生的单科成绩、总成绩、排名）
各种统计（统计及格率、统计>80分以上的同学等）
3） 管理员：维护学生和老师信息、查询统计

登录系统
实现对学生的CURD
实现对老师的CURD
实现各种查询、统计
