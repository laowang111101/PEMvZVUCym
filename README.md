# 前言

随着共享经济的兴起，民宿短租行业在我国得到了迅速发展。本项目是基于微信小程序的民宿短租系统设计与实现，主要采用SSM框架，结合前端技术，为广大用户提供便捷、高效的民宿短租服务。

## 内容介绍

本项目是一个基于微信小程序的民宿短租平台，主要包括以下功能模块：房源展示、房源搜索、预订房间、订单管理、用户管理等。通过使用Java语言和SSM框架，实现了前后端分离，方便开发和维护。前端采用Uniapp框架，实现了一套代码多端适配，提高了开发效率。

## 技术介绍

### 语言：Java

### 使用框架：
- Spring
- Springmvc
- Mybatis
- 微信小程序

### 前端技术：
- JS
- Vue
- CSS3
- Uniapp

### 开发工具：
- IDEA/Eclipse
- Uniapp

### 数据库：
- MySQL 5.7/8.0

### 数据库管理工具：
- phpstudy/Navicat

### JDK版本：
- jdk1.8

### Maven：
- apache-maven 3.8.1-bin

### 前端环境：
- Node.Js 12\14\16

## 核心代码

以下是一段关于房源搜索的核心代码：

```java
//房源搜索接口
@RequestMapping(value = "/searchHouse", method = RequestMethod.GET)
public String searchHouse(@RequestParam String location, @RequestParam String checkInDate, @RequestParam String checkOutDate, Model model) {
    List<House> houseList = houseService.searchHouse(location, checkInDate, checkOutDate);
    model.addAttribute("houseList", houseList);
    return "house_list";
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/326348/37/19600/83155/68c5a85fF954e16fc/0f64069f4251ca1e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/331224/37/12915/78239/68c5a81fFfef7db3a/1aafc278cda000f0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/344023/30/3094/29710/68c5a837F19e00caa/37a4e59c7b8a6076.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/332078/6/12739/16049/68c5a837F28c5a0c1/b2be4deb0b1fb9b8.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/330735/35/12985/31127/68c5a837F29810c52/1055470918008e37.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349781/14/3013/33268/68c5a837Fc0ac6aff/e71d4e1222323cdd.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327484/35/19766/9414/68c5a838F0ffce75d/85c3c25cbf6b74a0.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349819/7/3206/162592/68c5a838F5e33103d/be909bd7788ca16f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350099/15/3089/26640/68c5a839Fe41e4a7d/9b7f0a8b9c463639.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331616/23/12482/33628/68c5a839F745c8c01/b34c20a8c8bb709c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324382/12/19751/34105/68c5a83aF5ebfe862/47675e784ec2a913.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
