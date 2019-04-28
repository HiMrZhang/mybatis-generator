# mybatis代码生成工具

作者：掌少

## 1. 概述

自动生成dao层接口、pojo以及mapper xml

## 2. 使用方法

## 2.1 配置

	#数据库的url
    db.url=jdbc:mysql://127.0.0.1:3306/demo
    #用户名
    db.username=root
    #密码
    db.password=app!@#$4321)P:?0p;/
    #表名
    db.tablename=user

### 2.2 使用方法

    mvn mybatis-generator:generate
