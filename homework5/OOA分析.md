
## 甲方需求报告 ##
[需求报告](https://github.com/Erutan-pku/oo/blob/master/课程管理系统需求报告.md)
## 乙方需求分析 ##
[需求分析](https://github.com/JosephineSun/OOCOURSE/blob/master/homework4/需求分析.md)<br>
## 乙方涉众分析 ##
[涉众分析](https://github.com/JosephineSun/OOCOURSE/tree/master/homework3)<br>
# 1.类图 #
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/类图.png)
本系统主要涉及到三个类：<br>
1.用户类（User）<br>
用户类的操作有登录和登出。<br>
学生类（Student）、教师类（Teacher）、院长类（Dean）、管理员类（Manager）继承于用户类。<br>
学生类包含属性：学生学号（即编号）和姓名。<br>
教师类：教师编号和教师姓名。<br>
院长类：编号和姓名。<br>
管理员类：编号和姓名。<br>
2.选课类（Lesson）<br>
属性包括课程编号和课程名字。<br>
3.成绩类（Score）<br>
属性包括学生名单和成绩。<br>
# 2.顺序图 #
## 2.1 ##
学生登录系统，进行选课，查询成绩。<br>
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/流程图学生.png)
## 2.2 ##
教师登录系统，发布课程信息，录入学生成绩。<br>
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/流程图老师.png)
# 3.活动图 #
## 3.1 ##
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/学生选课流程图.png)
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/成绩查询流程图.png)
## 3.2 ##
![image](https://github.com/JosephineSun/OOCOURSE/blob/master/homework5/picture/教师流程图.png)
