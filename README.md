# COMP9315-A2-Multi-attribute-Linear-Hashed-Files
# COMP9315 A2 1v1 远程辅导、讲题和VIP定制服务 保证原创 严厉拒绝一份多售
# 源头导师 科班出身 非中介甩单！
# VX: csprojhelp 备注：github

【重点解析】：

>>Task 1:<<

1. Starter code 里的 tupleHash() 实现只是一个简陋版，要求扩展为可使用所有相关 bits 的综合 hash 方式，有关 bits 由 choice vector 确定

>>Task 2:<<

1. query.h 中的 QueryRep 类型对于完成 selection 查询还不完整，需要自行扩展并增加相应的 helper function

>>Task 3:<<

1. 实现完整的 Linear Hashing 算法（初始代码里只用到了 1 个 attribute）。每当新增一个物理页时，注意重新分配前面 buddy pages 中的 tuples。
2. 与标准的 Linaer Hashing 算法相比，此题放宽了要求：若某个 overflow page 被搬空，不需要删除它，留在原地即可（因为随着数据增长，这个页面在之后仍然可以被用来存储，并不会真正浪费）

【心得小结】：

1. 总体考察的核心能力其实是 C 语言编程，需要对指针、内存、结构体等概念非常熟悉和小心操作
2. 由于主题是模拟数据库内核操作所以数据结构比较复杂， 考验 Debug 技巧
3. 用到的算法如 Linear Hashing 等请仔细参考 lecture notes ，一些细节是和该课程绑定的

========================

4.15 快要due啦～ 欢迎有需要辅导或vip服务的同学dd～

#COMP9315 #UNSW #留学生辅导 #留学生补习 #留学生补课
