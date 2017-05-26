# JeeSite 云恬定制版

1. 创建数据库

`Create database {databaseName} DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;`

2. 修改 jeesite.properties 数据库 jdbc 连接配置

`jdbc.url=jdbc:mysql://127.0.0.1:3306/{databaseName}?useUnicode=true&characterEncoding=utf-8`

3. 初始化数据库

`mvn antrun:run -Pinit-db`
