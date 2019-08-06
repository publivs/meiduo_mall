# Django项目

## 1. 项目分析

### 技术实现

- 基于 Python 3 + Django 框架实现
- 数据存储使用 Redis + MySQL  实现
- 第三方扩展：
  - Docker：容器
  - celery:  异步任务
  - FastDFS：自定义文件存储系统
  - Elasticsearch:  全文搜索引擎

### 功能模块

- 用户模块
  - 注册
  - 登陆
  - QQ登陆
  - 密码找回
  - 个人中心
  - 邮件发送
  - 收货地址
- 商品模块
  - 商品详情
  - 热销商品
  - 用户游览历史记录
  - 商品列表页
  - 商品搜索
- 购物车模块
- 订单模块
  - 订单结算
  - 保存订单
  - 下单
- 支付宝接入
- Xadmin
- 用户权限控制

## 2.项目架构

- 项目采用前后端分离的应用模式
- 前端使用Vue.js
- 后端使用Django REST framework

## 第三方库

```shell
pip install Pillow==5.3.0
pip install pymysql==0.9.2
pip install django==2.1.2
pip install django-redis==4.9.0
pip install djangorestframework==3.8.2
```

