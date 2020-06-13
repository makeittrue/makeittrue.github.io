---
layout:     post
title:      navicat premium15破解及使用
subtitle:   navicat
date:       2020-6-13
author:     HMY
header-img: img/navicat.png
catalog: 	 true
tags:
    - 数据库
    - Navicat
---

# navicat premium15破解及使用

> 首先声明，使用破解版非商用纯学习使用，如果以后有商用开发使用会购买正版。不提倡使用盗版~

在官网上下载中文版之后用注册机生成注册码，然后通过一种奇异的方式就半破解了。

## 关于MySQL的一些问题

相对来说使用navicat处理MySQL的东西来说方便许多，基于navicat的特性在建表过程中很方便。

### 导入txt文件

这里可以使用navicat的导入功能对于txt文件进行导入，注意分隔符的选择以及起始行的选择。

## 关于MongoDB的一些问题
### 导入json文件数据

如果用navicat导入的话会出现一些问题 所以采用命令行导入的方式进行导入 

代码如下：

```shell
mongoimport --db company --collection project --jsonArray C:\Users\14675\Desktop\project.json
```

-  db 是数据库的名称
- collection是集合的名字 相当于表名
- --jsonArray是有的元素是数组
- --file 如果没有数组则使用file

