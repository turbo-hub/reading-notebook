
注：如遇文件打不开 重新刷新一下网址  
一般等一会就可以看到了 或者换个浏览器  
如果依然无法打开，一般都是dns解析问题，可以修改本地host来完成解析  
方法如下  

windows：C:\Windows\System32\drivers\etc\hosts  
mac: sudo vim /etc/hosts  
然后添加如下映射  

#GitHub start  
192.30.253.112    github.com  
192.30.253.119    gist.github.com  
151.101.184.133    assets-cdn.github.com  
151.101.184.133    raw.githubusercontent.com  
151.101.184.133    gist.githubusercontent.com  
151.101.184.133    cloud.githubusercontent.com  
151.101.184.133    camo.githubusercontent.com  
151.101.184.133    avatars0.githubusercontent.com  
151.101.184.133    avatars1.githubusercontent.com  
151.101.184.133    avatars2.githubusercontent.com  
151.101.184.133    avatars3.githubusercontent.com  
151.101.184.133    avatars4.githubusercontent.com  
151.101.184.133    avatars5.githubusercontent.com  
151.101.184.133    avatars6.githubusercontent.com  
151.101.184.133    avatars7.githubusercontent.com  
151.101.184.133    avatars8.githubusercontent.com  
#GitHub End  



================================================我是分割线====================================================================  
# reading-notebook
读书笔记   

书名：stream processing with apache flink  
作者：Fabian Hueske and Vasiliki Kalavri 著   

Chapter 1：Introduction to Stateful Stream Processing  
第一章：介绍有状态的流处理  
1.传统数据架构 Traditional Data Infrastructures 

2.有状态的流处理 Stateful Stream Processing 

3.开源流处理的发展 The Evolution of Open Source Stream Processing 

4.快速了解flink A Quick Look at Flink 

--------------------------------------------------------------------
Chapter 2. Stream Processing Fundamentals  
第二章：流处理的基本原理  
1.介绍dataflow编程模型 Introduction to Dataflow Programming 

2.并行化流处理 Processing Streams in Parallel 

3.时间语义 Time Semantics 

4.状态和一致性模型 State and Consistency Models 
总结 Summary 

--------------------------------------------------------------------
Chapter 3. The Architecture of Apache Flink  
第三章：apache flink的结构  
1.系统层面架构 System Architecture  

2.flink组件 Components of a Flink Setup  

3.程序的部署模式 Application Deployment  

4.任务执行 Task Execution  

5.高可用设置 Highly Available Setup  

6.flink中的数据传输 Data Transfer in Flink  

7.事件时间处理 Event-Time Processing  

8.状态管理State Management   

9.检查点、保存点、和状态恢复 Checkpoints, Savepoints, and State Recovery 
总结 Summary 

--------------------------------------------------------------------
Chapter 4.Setting Up a Development Environment for Apache Flink  
第四章：配置flink开发环境  
1.需要的软件 Required Software  

2.在ide中调试和运行flink程序 Run and Debug Flink Applications in an IDE  

3.引导flink maven项目 Bootstrap a Flink Maven Project  
总结 Summary  

--------------------------------------------------------------------  
Chapter 5. The DataStream API (v1.7)  
第五章：DataStream API（1.7版本）  
1.Hello, Flink!  

2.转换 Transformations  

3.设置并行度 Setting the Parallelism  

4.类型 Types  

5.定义key和引用字段 Defining Keys and Referencing Fields  

6.实现函数  Implementing Functions  

7.链接外部和flink的依赖 Including External and Flink Dependencies  
总结 Summary  

--------------------------------------------------------------------  
Chapter 6. Time-Based and Window Operators    
第五章：时间语义和窗口算子  
1.配置时间语义 Configuring Time Characteristics    

2.处理函数 Process Functions    

3.窗口算子 Window Operators  

4.按时间join流 Joining Streams on Time  

5.处理延迟数据 Handling Late Data  
总结 Summary  

--------------------------------------------------------------------  



 


