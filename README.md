
### jun_boot_admin springboot权限管理项目开发脚手架



### 项目说明
-------------
1. jun_boot_admin是以Springboot+Shiro+MybatisPlus为核心，以shiro-redis、redis为辅开发的精简后台基础系统。
2. 包含用户管理,角色管理,菜单管理,定时任务,文件管理,图标工具等常用业务模块。
3. 使用AdminLTE作为前端UI框架，添加菜单Tab页签完成内嵌iframe多页面功能, 前端项目地址：https://gitee.com/liyucc/adminlte-tab
4. 使用Mybatis集成通用Mapper作为ORM框架。
5. 使用redis、Ehcache实现权限缓存。
6. 使用thymeleaf模板,实现页面拆分,封装公共部分。
7. 使用Druid数据源,数据库监控。
8. 添加文件管理，整合阿里云、腾讯云、七牛云实现文件oss存储。

### 技术选型
-------------
AdminLTE、Springboot、Shiro、Mybatis-plus、shiro-redis、Ehcache、Redis、Mysql、Maven and so on

### 快速开始
-------------
1. 根据application-dev.yml内配置,设置mysql相关配置（sql文件在resource/sql目录下）
2. 根据application-dev.yml内配置,设置redis相关配置 (安装好redis并启动redis服务)
3. 项目导入eclipse或idea
4. 运行Application.java启动类
5. 浏览器输入http://qixing.nb666.net,账号/密码:admin/123456

### 重点功能
-------------
文件管理
http://qixing.nb666.net/sysfile
任务管理
http://qixing.nb666.net/sysJob
静态页面跳转
http://qixing.nb666.net/icons

### 参考项目
-------------
1. https://github.com/almasaeed2010/AdminLTE
2. https://github.com/baomidou/mybatis-plus
3. https://github.com/alexxiyang/shiro-redis
4. https://gitee.com/y_project/RuoYi
5. https://gitee.com/renrenio/renren-security

### 实例截图
-------------
