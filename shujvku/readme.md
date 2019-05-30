# [计算机网络](https://github.com/scutcyr/jida_teaching/tree/master/shujvku)
- 这是暨南大学计算机网络的课件
- 使用课本：数据库系统概论

<p align="center"><img width="40%" src="https://github.com/scutcyr/jida_teaching/blob/master/shujvku/shujvjku.png" /></p>

- [自学网站](https://www.51zxw.net/list.aspx?cid=492)
- [SQL Sever2008安装教程](https://mp.weixin.qq.com/s/I6tS1hQzOOJYj5Cf2Wfraw)
- SQL Server 2008（32/64位）下载地址：
-- 链接：https://pan.baidu.com/s/1eR5bAme 
-- 密码：f3bh
- SQL Server 2008R2（32/64位）下载地址：
-- 链接: https://pan.baidu.com/s/1o8huYUI 
-- 密码: dqff

## 大作业
<p>1、创建SQL查询命令文件，命名为姓名拼音，例如chenyirong.sql</p>
<p>2、使用CREATE DATABASE创建学生课程数据库：stdtb，主文件命名为stdtb_data，初始大小10MB，最大为100MB，日志文件命名为stdtb_log，初始大小5MB；参考链接：https://www.51zxw.net/show.aspx?id=39019&cid=492</p>
<p>3、使用CREATE LOGIN创建登录名和密码，登录名和密码要求为姓名拼音，例如chenyirong；参考链接：https://www.51zxw.net/show.aspx?id=39127&cid=492</p>
<p>4、使用CREATE USER创建用户usr1，usr2，usr3；参考链接：https://www.51zxw.net/show.aspx?id=39127&cid=492</p>
<p>5、在stdtb数据库当中建立三张基本表：<br>
  	学生表：Student(Sno,Sname,Ssex,Sage,Sdept)<br>
    课程表：Course(Cno,Cname,Cpno,Ccredit)<br>
    学生选课表：SC(Sno,Cno,Grade)<br>
</p>
<p>使用INSERT分别插入以下数据<br></p>
- 学生表：

| 学号Sno | 姓名Sname | 性别Ssex | 年龄Sage | 所在系Sdept |
| ------ | ------ | ------ | ------ | ------ |
| 201215121 | 李勇 | 男 | 20 | CS |
| 201215122 | 刘晨 | 女 | 19 | CS |
| 201215123 | 王敏 | 女 | 18 | MA |
| 201215125 | 张立 | 男 | 20 | IS |
| 201215129 | 李丹 | 女 | 20 | EE |

- 课程表：

| 课程号Cno | 课程名Cname | 先行课Cpno | 学分Ccredit |
| ------ | ------ | ------ | ------ |
| 1 | 数据库 | 5 | 4 |
| 2 | 数学 |   | 2 |
| 3 | 信息系统 | 1 | 4 |
| 4 | 操作系统 | 6 | 2 |
| 5 | 数据结构 | 7 | 4 |
| 6 | 数据处理 |   | 2 |
| 7 | PASCAL语言 | 6 | 4 |

- 学生选课表：

| 学号Sno | 课程号Cno | 成绩Grade |
| ------ | ------ | ------ |
| 201215121 | 1 | 92 |
| 201215121 | 2 | 85 |
| 201215121 | 3 | 88 |
| 201215122 | 2 | 90 |
| 201215122 | 3 | 80 |
| 201215123 | 2 | 82 |
| 201215124 | 2 | 78 |


## 实践资料
- [git for windows](https://desktop.github.com/)

## [第1章](https://raw.githubusercontent.com/scutcyr/jida_teaching/master/shujvku/%E7%AC%AC1%E7%AB%A0%20%E7%BB%AA%E8%AE%BA.ppt)
  [点击下载:第1章 绪论.ppt](https://raw.githubusercontent.com/scutcyr/jida_teaching/master/shujvku/%E7%AC%AC1%E7%AB%A0%20%E7%BB%AA%E8%AE%BA.ppt)
## [第2章](https://raw.githubusercontent.com/scutcyr/jida_teaching/master/shujvku/%E7%AC%AC2%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93.ppt)
  [点击下载:第2章 关系数据库.ppt](https://raw.githubusercontent.com/scutcyr/jida_teaching/master/shujvku/%E7%AC%AC2%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93.ppt)
## [第3章](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC3%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93%E6%A0%87%E5%87%86%E8%AF%AD%E8%A8%80SQL-part2.ppt)
  [点击下载:第3章 关系数据库标准语言SQL-part1.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC3%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93%E6%A0%87%E5%87%86%E8%AF%AD%E8%A8%80SQL-part1.ppt)
  
  [点击下载:第3章 关系数据库标准语言SQL-part2.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC3%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93%E6%A0%87%E5%87%86%E8%AF%AD%E8%A8%80SQL-part2.ppt)
  
  [点击下载:第3章 关系数据库标准语言SQL-part3.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC3%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E5%BA%93%E6%A0%87%E5%87%86%E8%AF%AD%E8%A8%80SQL-part3.ppt)
  
## [第4章](https://github.com/scutcyr/jida_teaching/blob/master/shujvku/%E7%AC%AC4%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AE%89%E5%85%A8%E6%80%A7.ppt)
  [点击下载:第4章 数据库安全性.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC4%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AE%89%E5%85%A8%E6%80%A7.ppt)
  
## [第5章](https://github.com/scutcyr/jida_teaching/blob/master/shujvku/%E7%AC%AC5%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AE%8C%E6%95%B4%E6%80%A7.ppt)
  [点击下载:第5章 数据库完整性.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC5%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AE%8C%E6%95%B4%E6%80%A7.ppt)
  
## [第6章](https://github.com/scutcyr/jida_teaching/blob/master/shujvku/%E7%AC%AC6%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E7%90%86%E8%AE%BA.pptx)
  [点击下载:第6章 关系数据理论.pptx](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC6%E7%AB%A0%20%E5%85%B3%E7%B3%BB%E6%95%B0%E6%8D%AE%E7%90%86%E8%AE%BA.pptx)
  
## [第7章](https://github.com/scutcyr/jida_teaching/blob/master/shujvku/%E7%AC%AC7%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1-part1.ppt)
  [点击下载:第7章 数据库设计-part1.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC7%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1-part1.ppt)
  
  [点击下载:第7章 数据库设计-part2.ppt](https://github.com/scutcyr/jida_teaching/raw/master/shujvku/%E7%AC%AC7%E7%AB%A0%20%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1-part2.ppt)

