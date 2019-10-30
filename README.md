## 社区项目 学习
## 资料
[Spring 文档](https://spring.io/guides)
[Bootstrap组件](https://v3.bootcss.com/components/)
[OkHttp](https://square.github.io/okhttp/)

# 脚本
```sql
create table USER
(
    ID           INT AUTO_INCREMENT PRIMARY KEY NOT NULL,
    ACCOUNT_ID   VARCHAR(100),
    NAME         VARCHAR(50),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT,
    constraint USER_PK
        primary key (ID)
);
```
