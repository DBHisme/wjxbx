# wjxbx

SpringBoot+Vue“问卷星不星”高校满意度调查问卷系统

## 项目介绍

“问卷星不星”高校满意度调查问卷系统是一个基于SpringBoot+Vue的高校满意度调查问卷系统  
前后端分离，前端使用Vue框架，后端使用SpringBoot框架，数据库使用MySQL  
前端页面使用ElementUI组件库，后端使用MyBatis框架进行持久化操作  
项目使用Maven进行构建，使用Junit进行单元测试，使用SonarQube进行代码质量检测  
使用Jmeter进行性能测试，使用JaCoCo进行测试覆盖率检测  

## 项目内容

本次实践的应用系统是《高校满意度调查问卷》系统，本系统的业务背景说明如下：  
常规调查问卷方法在各行各业的统计分析中发挥越来越重要的作用，许多数据的收集都
是通过大量使用到问卷调查与访谈方法。为便于进一步了解被调查对象存在深层次的需求与
情况，深度做好统计分析与调查工作，更加客观准确地反映调查人员的状况，所以需要进行
问卷调查系统的设计与实践。调查问卷系统建立在互联网的基础上，构建一个依托网络的问
卷设计、发布、统计和内容归集的系统。  
传统纸质问卷存在设计与印制问卷成本高，且后期纸质问卷作为档案资料保存较麻烦。
问卷的发放、回收、统计流程复杂，容易产生漏卷废卷统计错误等问题，问卷可控性差。统
计与分析内容难度较大，整体效果不好。  
依托于互联网中的调查问卷系统能够高效地执行大批量的问卷调查并且增强调查结果
的客观性，能够使被调查对象不受影响回答问卷，便于调查工作信息化保存，相比商业网站
上做调查问卷，本系统也可以在内网中进行部署，提高数据保密性。  
本系统的设计是基于 B/S 架构下实现的 Web 项目，用户可以通过 PC 端的主流浏览器
使用本系统。本系统采用主流的开发框架构建系统服务端以及客户端，采用主流数据库实现
数据持久化。  

## 项目要求

1. 要求采用 JDK1.8 以上版本，Tomcat8 以上版本，Mysql5.7 及以上完成开发。
2. 要求使用 Spring Boot 开源应用框架，基于注解的配置方式，完成 B/S 架构应用系
   统框架的搭建及相应功能的开发。
3. 使用 Maven 的构建项目。
4. 使用流行的 Web 框架技术，如 VUE 等 MVC 框架，MyBatis 等数据库持久化框架。
5. 要求采用过滤器完成系统的字符编码功能，使系统正常处理非英文字符。
6. 使用 Junit 完成系统的功能测试。
7. 使用 SonarQube 完成代码制品度量，并为代码生成质量度量报告；
8. 使用 JaCoCo 完成测试用例覆盖率的度量，并为测试用例生成覆盖率报告；
9. 【可选】采用合适的数据库连接池，可以是 Tomcat 自带的连接池功能，也可以是第
   三方连接池工具，如 dbcp 或者 c3p0，注意防止 SQL 注入。
10. 【可选】为了保证用户体验，页面初始加载完成以后，后续页面操作采用 Ajax 技
    术实现异步提交和局部刷新，Ajax 交互的数据格式采用 Json 格式，使用合适的第三方工具
    完成对象和 Json 字符串的互转，如 gson，fastjson，Jackson 等。
11. 【可选】使用 Jmeter 项目性能测试，并迭代优化性能、形成性能测试报告。

## 项目合作人

1. 姓名：贾丰哲 梁朝阳
2. 班级：软件2108
3. 学号： 20216641 20217033
4. 目标：征服星辰大海
