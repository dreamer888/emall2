# B2C多仓店商城小程序

#### 介绍
B2C多仓店商城小程序，前后端分离 ，
后端java springboot诺依框架 +  前端 vue +  消费者移动端uniapp （支持App ，小程序 ，H5），
骑手移动端uniapp ， 
mysql  ，
微信支付 。

#### 软件部分截图

![输入图片说明](doc/image/admin/%E7%AE%A1%E7%90%86%E7%AB%AF%E6%88%AA%E5%9B%BE-%E5%89%8D%E7%BD%AE%E4%BB%93.png)

![输入图片说明](doc/image/mobile/emall%E9%A6%96%E9%A1%B5.png)

![输入图片说明](doc/image/mobile/emal-%E6%88%91%E7%9A%84.png)

![输入图片说明](doc/image/rider/%E9%AA%91%E6%89%8B.png)

#### 软件架构
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


#### 运行环境 

MySQL	5.7或者8.0
JDK	1.8（推荐）
Redis	4.0.1（其他也可以）
Nginx	1.2 以上 
HbuilderX 3.7以上
maven   3.63 以上
Node    14 到18之间

#### 安装教程

document下面有完整的部署文档


#### 使用说明
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

