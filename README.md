# bookmanager
xiyouLinux图书借阅平台

## 整体架构说明

config ----spring 放置spring的配置文件  
       | 
       ----database 放置数据库的配置文件  

 dao ----dbfactory dao接口的生产工厂  
     |
     ----dbimpl   数据库接口的实现类  
     |
     ----dbservice 数据库所提供的调用接口  

model ----存放Java Bean等数据模型  

web  ----存放控制器  

test ----存放测试类  

upload ----存放上传的文件  

view ----存放jsp、html等文件  

---

还有css、js等目录不在这里说明。

大概的目录分配就是这样，每个目录下的子目录，写项目的时候要用到再自行进行扩充，注意命名规范。

还是觉得先快速学习一遍阿里开发手册，对约束与规范有一定的认识。磨刀不误砍柴功～～
