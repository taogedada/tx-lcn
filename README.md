第一种配置方式：eureka+test+testa+tx-lcn-maste(使用官方的tm项目)
第二种配置方式：eureka+test+testa+tm(自己搭建tm项目，引入tm依赖)
目前存在的问题：当打断点后，会报错加入一个无效的group，配置事务时间没生效
txlcn源码地址：https://github.com/codingapi/tx-lcn.git
参考：https://blog.csdn.net/JavaTeachers/article/details/106520996
https://blog.csdn.net/yhmliunan/article/details/102694611

