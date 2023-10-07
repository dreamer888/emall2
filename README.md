 **# B2C多仓店商城小程序** 

 **#### 介绍** 
B2C多仓店商城小程序，前后端分离 ，
后端java springboot诺依框架 +  前端 vue +  消费者移动端uniapp （支持App ，小程序 ，H5），
骑手移动端uniapp ， 
mysql  ，
微信支付 。

 **#### 软件部分截图** 

![输入图片说明](doc/image/admin/%E7%AE%A1%E7%90%86%E7%AB%AF%E6%88%AA%E5%9B%BE-%E5%89%8D%E7%BD%AE%E4%BB%93.png)

![输入图片说明](doc/image/mobile/emall%E9%A6%96%E9%A1%B5.png)

![输入图片说明](doc/image/mobile/emal-%E6%88%91%E7%9A%84.png)

![输入图片说明](doc/image/rider/%E9%AA%91%E6%89%8B.png)

 **#### 软件架构** 
软件架构说明
- Java 后端服务
    - emall-admin: 启动器（打包打这个就行）
    - emall-admin-api: 提供管理员管理系统的WebApi
    - emall-app-api: 提供APP、小程序、H5用户请求的WebApi
    - emall-rider-api: 提供骑手APP、小程序、H5用户请求的WebApi
    - emall-framework: 提供通用业务代码
    - emall-system: 提供数据模型以及数据访问层封装
    - emall-common: 提供注解、工具类等
    - emall-generator: 代码生成器
    
- Vue 前端页面
    - emall-admin-ui: 基于element-ui的后台管理页面
    - emall-app-ui: 基于uniapp的小程序、H5、APP前端代码
    - emall-rider-ui: 基于uniapp的小程序、H5、APP骑手代码


 **#### 后端技术** 

* 前端开发框架 Vue、Element UI
* 后端开发框架 Spring Boot
* 容器框架 Undertow 基于 XNIO 的高性能容器
* 权限认证框架 Sa-Token、Jwt 支持多终端认证系统
* 关系数据库 MySQL 适配 8.X 最低 5.7
* 缓存数据库 Redis 适配 6.X 最低 4.X
* 数据库框架 Mybatis-Plus 快速 CRUD 增加开发效率
* 数据库框架 p6spy 更强劲的 SQL 分析
* 多数据源框架 dynamic-datasource 支持主从与多种类数据库异构
* 序列化框架 Jackson 统一使用 jackson 高效可靠
* Redis客户端 Redisson 性能强劲、API丰富
* 分布式限流 Redisson 全局、请求IP、集群ID 多种限流
* 分布式锁 Lock4j 注解锁、工具锁 多种多样
* 分布式幂等 Redisson 拦截重复提交
* 分布式链路追踪 SkyWalking 支持链路追踪、网格分析、度量聚合、可视化
* 分布式任务调度 Xxl-Job 高性能 高可靠 易扩展
* 分布式文件存储 Minio 本地存储
* 分布式云存储 七牛、阿里、腾讯 云存储
* 监控框架 SpringBoot-Admin 全方位服务监控
* 校验框架 Validation 增强接口安全性 严谨性
* Excel框架 Alibaba EasyExcel 性能优异 扩展性强
* 文档框架 SpringDoc、javadoc 无注解零入侵基于java注释
* 工具类框架 Hutool、Lombok 减少代码冗余 增加安全性
* 代码生成器 适配MP、SpringDoc规范化代码 一键生成前后端代码
* 部署方式 Docker 容器编排 一键部署业务集群
* 国际化 SpringMessage Spring标准国际化方案


 **#### 运行环境 ** 

MySQL	5.7或者8.0

JDK	1.8（推荐）

Redis	4.0.1（其他也可以）

Nginx	1.2 以上 

HbuilderX 3.7以上

maven   3.63 以上

Node    14 到18之间

#### 安装教程

document下面有完整的部署文档


 **#### 登录说明** 
管理端
账号：admin,  密码：es110212

小程序 登录名:13333333333 ,
点击一下获取验证码先,
然后输入验证码:666666，，


#### 免责声明

本软件已经申请版权，开源源码仅供学习参考，未经授权不能倒卖，否则会引发对原创作者侵权风险。

 **####技术支持** 

QQ 75039960，
18665802636 

