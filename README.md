## 前言

大家好，这是一个基于Java和MySQL开发的远程教育网站项目，是本人的毕业设计。在这个项目中，我采用了当前较为流行的技术，如Spring Boot、Vue等，并实现了用户在线学习、课程管理等功能。以下是关于该项目的详细介绍，希望能对大家有所帮助。

## 内容介绍

本项目是一个远程教育网站，主要分为前台展示和后台管理两个部分。前台部分包括课程展示、在线学习、个人中心等功能，用户可以在网站上找到适合自己的课程进行学习。后台管理部分则包括课程管理、用户管理、订单管理等功能，方便管理员对网站进行维护和运营。整个项目采用了前后端分离的开发模式，前端负责展示，后端负责数据处理，提高了开发效率和项目的可维护性。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一个简单的后端接口示例，使用了Spring Boot框架：

```java
@RestController
@RequestMapping("/api/course")
public class CourseController {

    @Autowired
    private CourseService courseService;

    @GetMapping("/list")
    public ResponseEntity<List<Course>> list() {
        List<Course> courseList = courseService.list();
        return ResponseEntity.ok(courseList);
    }
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

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/309389/35/26634/78650/689f0d8bFb528130d/61d7d0fef106a7e1.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327280/7/4964/16944/689f0d66F53404e98/3294d4e73e4d2160.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/295120/8/26007/20670/689f0d66F28308e9c/c48fe4614ef2da7b.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/304726/23/26816/64521/689f0d67F1288b647/9ac3e6d6fd9afcd7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326994/38/4952/44298/689f0d67Ff428c232/e838d609f1407e70.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/310935/6/26740/22103/689f0d68F180d148b/ce5787539f075605.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/312916/36/22462/14392/689f0d68F343061ab/6890fd85f59488b5.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/302115/25/18865/20057/689f0d69Fab5541a5/f4e8a0f5fc89a3b7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311119/22/26907/59805/689f0d6aFd44eab70/9a75ac59355cf1a3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/296020/39/7640/128613/689f0d6aFb72fd49e/3396553d6ae59f9a.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
