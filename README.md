# Java-毕业设计企业财务报销系统

![登陆界面](https://wx-ma1.oss-cn-beijing.aliyuncs.com/settle.jpg "登陆界面.png")

####  **功能设计图** 
![功能设计图](https://skywalking.pro/download/images/settle-platform/WechatIMG236.jpeg "功能设计图.png")

####  **联系作者** 

![联系作者](https://wx-ma1.oss-cn-beijing.aliyuncs.com/main-platform.png "联系作者.png")

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。**  
  

![微信二维码-1](https://wx-ma1.oss-cn-beijing.aliyuncs.com/wx.jpg?x-oss-process=image/resize,p_50 "微信二维码-1.png")

**系统功能持续更新中。。。**
#### 介绍
 **本系统是采用现代信息技术手段，采用JAVA开发语言，VUE语言，HTML语言，实现企业的车票报销系统的系统编码，系统测试，以及系统的各项功能，该系统的主要功能是用户登录，职工报销管理，职工可以提交报销信息，同时系统的财务管理人员可以通过或者拒绝报销，进行流程跟踪，流程记录，同时系统管理人员可以查看系统报销的审批记录，可以方便地溯源，同时系统应该具备多种条件查询，检索的功能，同时实现了财务票据的审核工作流，可以自定义审核步骤。
 SpringBoot2.X VUE2.6 Antd1.7.2  MyBatisPlus Shiro1.5.0 Java1.8 管理系统 JVM 权限设计 可作为毕业设计和快速开发 财务报销系统** 
#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
| ElementUI 2.x |  饿了么出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Shiro1.5.0 | 经典而好用的权限框架  |  |
| uniapp | 移动端开发框架  |  |
| uview | 高颜值的移动端UI框架  |  |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |
#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")
#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。
### 联系作者
#### 微信号: SkyLearningPro
#### 系统演示地址:
```
登录地址: https://www.skywalking.pro/settle-platform
登录账号: admin
登录密码: 123456
```

**若演示程序不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。
#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图](https://www.skywalking.pro/download/images/settle-platform/WX20230104-152045@2x.png "系统技术文档截图.png")

### 项目代码展示

#### 前端VUE代码截图展示

![前端VUE代码截图展示](https://www.skywalking.pro/download/images/settle-platform/WX20230104-152812@2x.png "管理系统VUE代码截图展示.png")

#### 后端Java代码截图展示

![后端Java代码截图展示](https://www.skywalking.pro/download/images/settle-platform/WX20230104-152649@2x.png "后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://www.skywalking.pro/download/images/settle-platform/WX20230104-153215@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://wx-ma1.oss-cn-beijing.aliyuncs.com/settle.jpg "登陆界面.png")

![主页-01](https://www.skywalking.pro/download/images/settle-platform/WX20230104-142502@2x.png "主页-01.png")

#### 系统管理模块
- 系统主页

![主页-02](https://www.skywalking.pro/download/images/settle-platform/WX20230104-142548@2x.png "主页-02.png")

- 菜单管理

![菜单管理](https://www.skywalking.pro/download/images/settle-platform/WX20230104-153358@2x.png "菜单管理.png")

![菜单编辑](https://www.skywalking.pro/download/images/settle-platform/WX20230104-153442@2x.png "菜单编辑.png")

- 角色管理

![角色管理](https://www.skywalking.pro/download/images/settle-platform/WX20230104-153514@2x.png "角色管理.png")

![角色编辑](https://www.skywalking.pro/download/images/settle-platform/WX20230104-153722@2x.png "角色编辑.png")

- 系统用户管理

![系统用户列表](https://www.skywalking.pro/download/images/settle-platform/WX20230104-154256@2x.png "系统用户列表.png")

![系统用户编辑](https://www.skywalking.pro/download/images/settle-platform/WX20230104-154330@2x.png "系统用户编辑.png")

#### 系统监控模块

- 系统日志监控

![系统日志监控](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155137@2x.png "系统日志监控.png")

#### 业务模块

- 员工管理模块

![员工管理模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155226@2x.png "员工管理模块.png")

![员工新增模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155306@2x.png "员工新增模块.png")

- 报销单据列表模块

![申请列表](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155406@2x.png "报销单据列表模块.png")

- 提交单据列表模块

![提交单据列表模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155607@2x.png "提交单据列表模块.png")

- 审核步骤列表模块

![小程序轮播图模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155642@2x.png "审核步骤列表模块.png")

- 审核步骤新增模块

![审核步骤新增模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-155921@2x.png "审核步骤新增模块.png")

- 审核记录模块

![输入图片说明](https://www.skywalking.pro/download/images/settle-platform/WX20230104-160010@2x.png "审核记录模块.png")

- 审核单据模块

![审核单据模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-160102@2x.png "审核单据模块.png")

![审核模块](https://www.skywalking.pro/download/images/settle-platform/WX20230104-160147@2x.png "审核模块.png")

#### 后台系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
  - 系统请求追踪
    * 请求耗时追踪
    + 请求方法追踪
	+ 请求URL追踪
	+ 请响应状态追踪
+ 系统员工管理模块
  - 系统员工管理
    * 系统员工条件查询
    + 系统员工新增
	* 系统员工修改
    + 系统员工批量删除
+ 审核步骤管理
  - 审核步骤列表
    * 审核步骤条件查询
    + 审核步骤新增
	* 审核步骤修改
    + 审核步骤批量删除
+ 报销单据管理
  - 报销单据列表
    * 报销单据条件查询
    + 报销单据提交
	+ 报销单据审核
	* 报销单据修改
    + 报销单据批量删除
+ 审核记录模块
  - 审核记录列表
    * 审核记录条件查询
    + 审核记录新增
	* 审核记录修改
    + 审核记录批量删除

#### 演示地址
```
登录地址: https://www.skywalking.pro/settle-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。**  


![微信二维码-1](https://wx-ma1.oss-cn-beijing.aliyuncs.com/wx.jpg?x-oss-process=image/resize,p_50 "微信二维码-1.png")

#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf health-record-api.tar.gz (解压tar包)
3.  cd health-record-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
