# VoteSystem
用C编写
## 问题：
某个班级有３个候选人，有６个同学参与投票，而且只能投一个人，要求编写统计选票的程序。先输入候选人名字，再输入同学所投的候选人名字，最后根据每位候选人的得票数排序

## 思路
先定义一个学生结构体 stduent，结构体中包含姓名，票数。
同时声明结构数组stu[N - 1],里面存放候选人信息
输入候选人的姓名，开始投票。如果输入的字符串和候选人的姓名一样，就累加。
之后，用插入排序。最后输出排完序票数。

个人感觉我做的这个，很简陋。只是完成了基本的功能

