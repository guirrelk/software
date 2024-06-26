# software
软工实验
# 实验环境
jdk + Tomcat + Mysql + Webstorm（前端框架） + Intellij IDEA（ide） 
# 开发进度
2024/3/25  
进行后端数据库搭建，建立关系并完成E-R图.  
初步进行前端环境搭建.  
  
2024/4/1  
完成登录页面；  
完善后台数据库

第七周：项目启动与规划
任务完成： 
确定项目目标和范围，明确要开发的人才招聘系统网站的主要功能。
设定项目的时间表和里程碑，制定详细的开发计划。
搭建开发环境，包括安装必要的开发工具、配置代码版本控制系统。
遇到的问题： 
在选择开发框架和工具时花费了一些时间。
对项目整体规模和时间预估不够准确。
解决方案： 
通过查阅资料，最终选择了适合的开发框架和工具。
调整项目计划，确保后续开发能够按照计划进行。

第八周：需求分析与设计
任务完成： 
完成详细的需求分析，包括用户角色、用例图、业务流程等。
设计数据库结构，绘制ER图，并编写数据字典。
设计系统整体架构，明确前端、后端、数据库的交互方式。
遇到的问题： 
在设计数据库结构时遇到了一些数据冗余和一致性问题。
解决方案： 
通过查阅数据库设计相关书籍和资料，解决了数据冗余和一致性问题。

第九周：系统实现（用户模块）
任务完成： 
实现用户注册功能，包括表单验证、数据存储等。
实现用户登录功能，包括密码加密、登录状态管理等。
编写用户模块的单元测试，确保功能稳定。
遇到的问题： 
密码加密算法的选择和实现上花费了一些时间。
解决方案： 
查阅相关资料，选择了合适的密码加密算法，并成功实现。


第十周：系统实现（职位模块）
任务完成： 
实现职位发布功能，包括职位信息的录入和存储。
实现职位列表展示功能，包括分页、排序等。
设计并实现职位详情页面，展示职位的详细信息。
遇到的问题： 
在实现职位列表分页时遇到了性能问题。
解决方案： 
优化数据库查询语句，使用索引提高查询效率


第十一周：系统实现（其他模块）
任务完成： 
完成搜索功能的开发，允许用户根据关键词搜索职位。
实现用户个人信息管理功能，如修改密码、更新个人信息等。
对已完成的功能进行集成测试，确保各模块能够协同工作。
遇到的问题： 
在搜索功能实现时，对搜索算法的选择和优化上花费了一些时间。
解决方案： 
尝试不同的搜索算法，最终选择了适合项目需求的算法，并进行优化。


第十二周：系统实现（简历模块）
任务完成： 
实现简历上传功能，包括文件验证、存储和展示。
设计并实现简历管理页面，允许用户查看、编辑和删除自己的简历。
遇到的问题： 
在处理大文件上传时遇到了性能和安全性问题。
解决方案： 
使用分片上传技术处理大文件，提高上传效率。

十三周：系统实现（消息模块）
任务完成： 
实现消息通知功能，如发送面试邀请、简历更新通知等。
对系统进行优化，提高性能和响应速度。
遇到的问题： 
在实现消息通知功能时，对通知的发送方式进行了调整。
解决方案： 
根据测试结果，最终确定了合适的通知发送方式。

十四周：系统实现（管理员模块）
任务完成： 
实现管理员登录与权限验证功能，确保管理员身份的安全性和合法性。
设计并实现管理员控制面板，包括用户管理、职位管理、简历管理等功能模块。
遇到的问题： 
在设计管理员控制面板时，对界面布局和功能模块的组织进行了多次调整。
在实现用户、职位、简历的批量操作时，需要考虑性能和效率问题。
解决方案： 
参考其他管理后台设计，最终确定了合适的界面布局和功能模块组织方式。
对于批量操作，使用了异步处理来提高性能和效率。

第十五周：测试与修复
任务完成： 
编写测试用例，对系统进行全面的功能测试。
修复测试中发现的问题和BUG。
遇到的问题： 
在测试过程中发现了一些之前没有考虑到的问题和BUG。
解决方案： 
仔细分析问题的原因，并编写相应的修复代码。
对修复后的代码进行回归测试，确保问题已解决。

