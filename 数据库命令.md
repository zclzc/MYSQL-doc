
1. 
```linux
 mysql -u root -p
```
   通过使用该命令进入数据库，以检查数据库是否安装成功。
  
2.
```mysql
 show databases; 
```
   该命令可以查看当前有那些数据库（注意其中database**s**是复数形式）。
3.
```mysql
 create database stu;
 ```
   该命令用来创建名字为**stu**的数据库。

4.
```mysql
 use stu；
```
   该命令用来改变当前所在的数据库为**stu**。
  
5.
```mysql
 create table <表名>
 （<属性名1> <数据类型> [not null],
   <属性名2> <数据类型> [not null],
   ...
   [primary key('某属性名'),]
   [foreign key('某属性名') references <表名>('某属性名')]
   ）；
   ```
     该语句块用来创建 **school、information、course、score**（学院信息、学生信息、课程信息、成绩）三个表，其中主码、外码可以根据实际情况来设置。
