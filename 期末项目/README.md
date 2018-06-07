<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 基于GitHub的实验管理平台的分析与设计

### 成都大学信息科学与工程学院

|学号|班级|姓名|照片|
|:-------:|:-------------: | :----------:|:---:|
|201510414429|软件(本)15-4|周柏龄|![flow1](./a.jpg)|

## 1. 概述
- 基于GitHub的实验管理平台的作用是在线管理实验成绩的Web应用系统。学生和老师的实验内容均存放在GitHUB
页面上。
- 学生的功能主要有：一是设置自己的GitHub用户名，二是查询自己的实验成绩。学生的GitHub用户名是公开的，但成绩不公开。
- 老师的功能主要有：一是批改每个学生的成绩，二是查看每个学生的成绩。
- 老师和学生都能通过本系统的链接方便地跳转到学生的每个GitHUB实验目录，以便批改实验或者查看实验情况。
- 实验成绩按数字分数计算，每项实验的满分为100分，最低为0分。
- 系统自动计算每个学生的所有实验的平均分。
    
## 2. 系统总体结构
![](系统总结构图.jpg)

界面设计参见：https://zhouboling.github.io/is_analysis/test6/ui/index.html
    
## 3. 用例图设计 [源码](src/UseCase.puml)
![](useCase.png)

## 4. 类图设计 [源码](src/class.puml)
![](./class1.png)

## 5. 数据库设计
- ### [参见数据库设计](./数据库设计.md)

## 6. 用例及界面详细设计
- ### [“学生列表”用例](./用例/学生列表.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/index.html)
- ### [“试验成绩评定”用例](./用例/评定成绩.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/实验成绩评定.html)
- ### [“学生成绩查询”用例](./用例/查看成绩.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/学生成绩查询.html)
- ### [“修改密码”用例](./用例/修改密码.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/修改密码.html)
- ### [“修改个人信息”用例](./用例/修改用户信息.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/修改个人信息.html)
- ### [“查看个人信息”用例](./用例/查看用户信息.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/个人信息.html)
- ### [“注销”用例](./用例/登出.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/home.html)
- ### [“登录”用例](./用例/登录.md),[界面](https://zhouboling.github.io/is_analysis/test6/ui/home.html)
    