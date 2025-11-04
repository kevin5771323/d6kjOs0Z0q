## 前言

欢迎来到在线视频教育系统项目，基于SSM框架开发，整合了微信小程序、Uniapp等前端技术，为广大学习者提供一个便捷、高效的学习平台。本项目致力于实现优质教育资源共享，助力我国教育事业发展。

## 内容介绍

本项目主要包括以下几个模块：课程展示、视频播放、评论互动、个人中心等。用户可以在平台上自由选择感兴趣的课程进行学习，支持在线观看视频，实时与教师或其他学员互动。同时，个人中心提供了学习进度管理、笔记记录等功能，方便用户跟踪学习情况。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于查询课程列表的核心代码：

```java
@RequestMapping("/courseList")
public String courseList(@RequestParam(value = "page", required = false, defaultValue = "1") int page,
                        @RequestParam(value = "size", required = false, defaultValue = "10") int size,
                        Model model) {
    Page<Course> coursePage = courseService.findCourseByPage(page, size);
    model.addAttribute("coursePage", coursePage);
    return "courseList";
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
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/326002/4/19278/162286/68c572c1F26a08b3c/16c1b4398a4a903d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326619/14/19620/18805/68c57299F2bb46536/974d00c52d335dd4.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332237/12/12871/36211/68c57299Fb330f475/0e6ada3de8cc6ecf.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/343013/13/3041/50991/68c57299Fc89a77da/5ba31891406909ca.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/326695/25/19770/50337/68c57299F183862ef/11c9f5e215846ba4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/344606/16/3084/14360/68c57299F1800fdcd/9033dd838276b23f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/346618/3/3049/28557/68c5729aFdedb1dc2/a2580c129ecddb76.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/323984/19/19715/21783/68c5729aFeb7a26d9/d305221a32ff9944.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/323365/30/19885/25930/68c5729aF212d27a1/70846cd757d8f2e0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/338202/27/5893/114432/68c5729bFb84093cd/7b3a96819fec90d4.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
