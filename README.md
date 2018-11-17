### 美妆多人博客系统的设计与实现

### 技术选型：

* JDK8
* MySQL
* Spring-boot
* Spring-data-jpa
* Shiro
* Hibernate-search
* Ehcache
* Freemarker
* Bootstrap
* SeaJs

### 启动：
 - main方法运行
 ```xml
 配置：web/src/main/resources/application.yml (数据库账号密码)、向数据库导入初始数据 sql/db_mblog.sql
 运行：web/src/main/java/mblog/BootApplication
 访问：http://localhost:8080/
 后台：http://localhost:8080/admin
 账号：默认管理员账号为 admin/12345
