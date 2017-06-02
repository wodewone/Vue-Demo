使用 vue + vuex 实现联系人列表

+-----------------------------------+  
| 姓名：甲 电话：12344445555 [删除] |  
+-----------------------------------+  
| 姓名：乙 电话：12366667777 [删除] |  
+-----------------------------------+  
| 姓名：丙 电话：12388889999 [删除] |  
+-----------------------------------+  
           +----+       +-----+
 姓名：|      |  电话 |        |   [添加]
           +----+       +-----+

要求：
  1. 使用 vue + vuex 实现，数据要放到 store 中
  2. 读取列表、删除、添加请求后端实现，可以使用 setTimeout 模拟后端，删除接口可能会失败
  3. 删除时有一个渐隐效果，要求在渐隐过程中条目内容和渐隐前一致

代码提交到 github