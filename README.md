# SpringBoot 项目初始模板 - 轻量

```
基于 Spring Boot 2.7.2 版本
整合 MyBatis-Plus 3.5.2 版本
整合 MyBatis 2.2.2版本
knife4j-接口文档
hutool-5.8.8
easyexcel
```

### 工具类

- Easy Excel 表格处理
- Hutool 工具库
- Apache Commons Lang3 工具类
- Lombok 注解


### 单元测试
- JUnit5 单元测试
- 示例单元测试类



## 快速上手

### MySQL 数据库

1）修改 `application.yml` 的数据库配置

```yml
spring:
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://localhost:3306/my_db
    username: root
    password: 123456
```

2）执行 `sql/create_table.sql` 中的数据库语句，自动创建库表

3）启动项目，访问 `http://localhost:8101/api/doc.html` 即可打开接口文档