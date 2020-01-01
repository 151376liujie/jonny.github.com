## 联系方式

- 手机：185-1180-7059
- Email：jonnyliu0525@qq.com
- 微信号： \_M0525M_

## 个人信息

 - 刘杰/男/1989 年
 - 本科/海南大学三亚学院/软件工程专业 （2008 - 2012）
 - GitHub：[https://github.com/151376liujie](https://github.com/151376liujie)
 - 在线简历：[https://151376liujie.github.io/resume/](https://151376liujie.github.io/resume/)
 - 应聘职位：Java后台开发工程师

## 技能清单

### 硬技能

- 后端
    - 熟悉Java语法及多线程、集合等常用框架
    - 了解JVM垃圾回收原理，熟悉JVM内存模型
    - 熟练掌握Redis常用数据结构，掌握基于Redis分布式锁及对缓存雪崩、穿透、击穿等问题的处理方式
    - 熟练掌握RabbitMQ消息中间件技术，掌握利用消息中间件实现异步解耦削峰及可靠消息常用方式
    - 阅读过Mybatis框架源码，熟练掌握其原理
    - 熟悉分布式系统开发，熟悉高并发系统常用解决方案
    - 熟悉Java常用设计模式（策略、模板方法、代理）
    - 熟练使用Spring Boot / Spring Cloud / Mybatis等开源框架
    - 熟练编写常用sql语句，有一定的MySQL数据库表设计和利用索引进行SQL优化的经验
    - 熟悉微服务思想及部署方式
	
### 软技能
- 良好的阅读英文文档能力，能适应英文环境
- 有一定的代码封装和架构能力，经常对自己的代码进行重构，喜欢干净整洁的代码
- 具有用户思维意识，尽量简化服务方工作量
- 具有架构演化意识，积极思考工作中遇到的问题
- 主动沟通/乐于团队合作，主动抛出问题
- 良好的文档编写能力

## 开源项目

### 项目名称 
[微信消息处理框架](https://github.com/151376liujie/wechat-core)( Star数量：97，Fork数量：65 )

### 项目简介 
基于java实现的轻量级微信消息处理框架，使用**注解**来标识不同消息类型的消息处理器，避免在代码中大量使用if else if来判断消息类型，更解耦！使用者也不需要再去关注消息发送和接收的具体细节，直接关注业务本身即可。

### 主要功能 
- 各类型消息的封装
- 各类型消息处理器的注解化使用
- 各类型消息自定义过滤（消息前、后置处理器）
- 内置各类型消息接收和发送的详细日志
- access_token接口的封装
- 微信用户接口的封装

## 工作经历 
### 凡普金科 ( 2017年10月 ~ 至今 )
##### 项目简介

支付平台是公司支付团队打造的供公司其他业务线无缝对接的一个平台，主要包含快捷支付、划扣、鉴权、绑卡、退款等功能。

##### 主要使用技术
- Spring Boot/Hystrix/RabbitMQ/Redis/Apollo/Nginx

##### 主要工作内容
- 参与支付平台架构设计与开发及架构演进
- 参与支付平台架构及代码重构
- 对接微信、支付宝、快钱、先锋等三方渠道
- 负责收银台设计与实现
- 负责支付平台对接华夏银行存管
- 负责协助业务线对接支付平台

##### 主要贡献
- 抽象渠道侧接口，使各个渠道实现统一的渠道侧接口，简化大量冗余代码，提升平台可维护性
- 使用消息中间件的延迟消息实现回调业务线补偿机制，提升了支付平台的业务容错性
- 统一回调服务入口，只暴露一个借口，减少网络攻击风险；回调服务引入MQ，大幅增加回调服务的吞吐量
- 增加支付失败切换渠道机制，提升了%1的支付成功率
- 增加熔断限流机制，保证了支付平台在峰值流量冲击中的系统可用性
- 优化华夏存管接口，缩小接口响应时间

---
##### 主要工作内容
- 负责爱钱进微信公众号和微信订阅号系统微服务重构
- 负责爱钱进业务系统设计微信接口的拆分

##### 主要贡献
- 重构爱钱进微信公众号系统，引入消息处理器和消息处理器分发机制，将不同类型的微信消息分发到对于的消息处理器中处理
- 引入微信消息代理服务，统一了微信消息推送入口，通过代理服务转发微信消息到下游微信业务系统，实现了消息的统一管理及加解密
- 实现对爱钱进业务系统中微信相关接口的拆分，实现了业务的解耦

### 豆包网 ( 2017年4月 ~ 2017年10月 )
##### 主要使用技术
- Spring Boot/Dubbo/ActiveMQ/Nginx/Redis

##### 主要工作内容
- 负责豆包网官网文章数据来源的爬取和存储
- 负责豆包管家调查问卷活动微服务接口开发及上线部署
- 负责企业edm邮件服务的开发
- 负责公司API网关的设计和开发
- 负责公司内部财务系统的开发和维护

### TCL（ 2016年8月 ~ 2017年4月 ）

#### [手机端portal后台](http://portal.fly2tech.com/#!/) 

一个手机端门户网站，为海外TCL手机用户提供常用地址导航、新闻内容聚合、关键字搜索等服务。

##### 主要使用技术

- Juice/MyBatis/SpringMVC/Zookeeper/Redis/Python/Maven/Mysql/Nginx/Tomcat/AWS/JSP/JQuery

##### 主要工作内容 

- 阅读第三方英文接口文档，根据自身需求进行接口接入前的可用性测试并使用邮件反馈给运营人员。
- 完成代码开发，接入海外第三方新闻API。
- 实现新闻内容的去重、敏感词过滤、新闻内容后台审核、置顶等功能。
- 编写爬虫爬取YouTube、快手、一点资讯等网站视频、图片、新闻等资源，并为爬虫编写测试用例。
- 跟踪第三方新闻API内容更新频率并及时和运营人员反馈。

### 北京海德康健信息技术有限公司 （ 2015年5月 ~ 2016年8月 ）

#### [北京市预约挂号统一平台](http://www.bjguahao.gov.cn) 

北京市预约挂号统一平台是北京市卫计委官方指定的预约挂号渠道，涵盖北京市147家二级、三级以上公立医院的预约挂号服务。同时也开通了电话预约挂号(114语音挂号)服务。

#### 北京114语音挂号系统 

北京114语音挂号系统是北京市卫计委官方指定的24小时提供语音挂号及号源查询的渠道，为不方便上网和不会上网的人群提供方便的语音挂号服务。

##### 主要使用技术

- SpringMVC/Spring JDBC/Redis/Nginx/Maven/MySql/Tomcat/JSP/JQuery

##### 主要工作内容 

- 参与预约挂号统一平台/114语音挂号系统订单模块的开发
- 参与医院号源管理系统主要功能的开发。
- 参与数据库分库设计。
- 封装基础工具代码，使其在整个项目中得以应用。
- 负责华为语音呼叫系统和114语音挂号系统的对接。
- 负责医院每日/月预约量、约成量、约成方式等各类统计报表的定时任务开发。
- 编写爬虫爬取疾病、科室等信息。
- 前台静态页面的动态化、页面数据校验的js代码开发。
- 进行线上的bug重现及修复工作。
- 循序渐进的进行代码重构。

### 广州孚骏信息技术有限公司 （  2012年7月 ~ 2015年5月 ）

#### 医院消毒供应质量追溯系统

该系统主要是针对医院消毒供应室规范化手术器械包的管理的需求而开发。将医院消毒供应室对器械包的生产过程全部纳入系统管理，从器械包的生产到器械包的使用
全程使用条形码来定位器械包，可以很方便的对器械包生产流程进行追踪，同时也可为可能的医疗纠纷提供技术依据。

##### 主要使用技术

- Struts2/Spring/JDBC/Oracle/Tomcat/JSP/ExtJs/JQuery

##### 主要工作内容 

- 负责器械包申请、审核、器械包教学视频上传/下载/在线观看等功能模块的设计开发。
- 根据业务需求开发器械包是永久记录统计、满意度调查等报表报表。
- 使用ExtJs开发前台页面，编写js业务代码。
- 代码重构及bug修复。


