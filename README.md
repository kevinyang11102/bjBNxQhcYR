# 项目简介 java686

本项目是一款基于 Spring Cloud 的博客管理系统后台，集成了多种微服务架构，旨在为用户提供一个稳定、高效、易于扩展的博客管理平台。

## 技术栈

- **服务注册与发现**：Eureka
- **配置管理**：Spring Cloud Config
- **负载均衡**：Ribbon
- **断路器**：Hystrix
- **网关**：Zuul
- **数据库**：MySQL
- **缓存**：Redis

## 功能模块

- **用户管理**：用户注册、登录、权限管理等功能
- **文章管理**：文章发布、编辑、删除、分类和标签管理
- **评论管理**：评论发表、审核、删除等
- **系统管理**：系统配置、日志管理等

## 系统角色

- **系统管理员**：负责系统配置和用户权限管理
- **普通用户**：发表文章、评论、修改个人资料等

## 运行环境

- **操作系统**：Linux或Windows
- **JDK版本**：1.8以上
- **数据库**：MySQL 5.7+
- **缓存**：Redis 3.2+

## 部署步骤

1. 搭建开发环境，包括JDK、MySQL、Redis等
2. 克隆本项目代码到本地
3. 根据配置文件进行环境配置
4. 启动各个微服务
5. 访问前端页面，进行功能测试

## 目录结构

```
blog-system
|-- blog-api         // API接口模块
|-- blog-auth        // 认证模块
|-- blog-common      // 通用模块
|-- blog-config      // 配置中心
|-- blog-eureka      // 服务注册与发现
|-- blog-gateway     // 网关模块
|-- blog-modules     // 业务模块
```

## 核心亮点

- **微服务架构**：各模块之间松耦合，便于扩展和维护
- **断路器机制**：保障系统稳定运行，防止雪崩效应
- **动态配置**：支持配置热更新，无需重启服务
- **负载均衡**：确保请求分发到各个服务实例，提高系统性能
- **权限控制**：细粒度的用户权限管理，保障系统安全
- **日志管理**：记录系统运行状态，便于问题追踪和分析

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img12.360buyimg.com/ddimg/jfs/t1/331695/26/17225/21166/68d532ffFe7b4dbdc/6cb8d0198550d237.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/337995/3/14766/98495/68d532ffFa3b217aa/abc0b0d3b529e706.jpg)

![](https://img14.360buyimg.com/ddimg/jfs/t1/340605/13/10197/65291/68d53300F940ffb77/d5dcd1ac1d9090d2.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/334898/29/17062/44058/68d53300Fcb623c64/742dd363052f6be6.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/343101/11/7423/34486/68d53300Fca735534/9c515fc371ac1397.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/336177/36/14354/44837/68d53301F51dc29dd/39c2056047cc082b.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/240957/1/30369/43708/68d53301F6deb0bc6/7c68b71e78c046c9.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/107800/20/45671/103739/68d53302Fadafcc8c/e5100cc810869081.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/327299/26/23980/66540/68d53302F5ac735fc/5379f6a656b69073.jpg)

