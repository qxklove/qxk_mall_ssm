# 购物网站

## 项目介绍
模仿教程实现的购物网站

### 功能介绍

1. 用户注册登录功能
2. 商品分类显示功能
3. 商品查询显示功能
4. 购物车功能
5. 用户下单购买功能
6. 用户评价功能
7. 添加删除服装功能
8. 商品信息修改功能
9. 订单管理功能
10. 多卖家支持

### 运用知识

* SSM框架
* MySQL
* Tomcat
* 数据库基本查询
* 数据库连接池c3p0
* jstl标签库
* jsp,servlet
* javascript,jquery
* Maven
* git

### 搭建环境

JDK8.0 + MySQL + Tomcat

#### 使用方法

1. git clone `https://github.com/qxklove/qxk_mall_ssm.git`
2. 使用IDEA导入打开
3. 导入sql文件tmall.sql
4. 部署Tomcat并启动

---
### 更新历史

2019-06-06  
第一次较大更新:加入卖家的概念  
现在后台就可以面向卖家啦啦啦，支持多个卖家，每个卖家只会管理自己家卖的东西和订单，同时前台用户订单会根据卖家来进行分类。  
后面应该还会再调整页面，仔细测试。现在等不及先上一版了。

2019-06-06  
业务调整，卖家的id应该是商品的外键，去点之前在分类对象里加的卖家id外键。然后分类是只有admin可以编辑的。
