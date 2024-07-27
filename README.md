# SpringBoot 项目初始模板

> Java SpringBoot 项目初始模板，整合了常用框架和示例代码，大家可以在此基础上快速开发自己的项目。


# 使用
修改数据库连接信息，redis连接信息


# 模板功能

- Spring Boot 3.3.2
- Spring MVC
- MyBatis Plus
- Spring Session Redis 分布式登录
- Spring AOP
- Apache Commons Lang3 工具类
- Lombok 注解
- Swagger + Knife4j 接口文档
- Spring Boot 调试工具和项目处理器
- 全局请求响应拦截器（记录日志）
- 全局异常处理器
- 自定义错误码
- 封装通用响应类
- 示例用户注册、登录、搜索功能
- 示例 SQL（用户表）

访问 localhost:7529/api/doc.html 就能在线调试接口了

# 更新
- 将SpringBoot版本更新为3.3.2
- Knife4j更新为4.5.0
- Mysql-Connection-java更新为8.0.33
- Mybatis-plus更新为3.5.7
- JDK版本为21

# 坑
使用OpenAPI3后，生成的接口文档中 host = 地址:端口/ContextPath，host会拼接上BasePath(ContextPath。
前端使用OpenAPI生成接口时需要额外注意