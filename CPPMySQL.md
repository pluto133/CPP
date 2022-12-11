
- [x] C++ programming
- [ ] MySQL DB
- [ ] FE/BE developping UI Design

[CPP->MySQL](https://blog.csdn.net/m0_67401055/article/details/126031219)
 
 
 (https://blog.csdn.net/m0_67401055/article/details/126031219)
### 参数介绍
==test==
```C++
MYSQL *mysql_real_connect(MYSQL *mysql, const char *host, const char *user,
const char *passwd, const char *db, unsigned int port,
const char *unix_socket, unsigned long client_flag)
```
 


mysql 初始化的句柄指针
host 主机地址
user 用户名 – mysql数据库 root
passwd 用户的密码
db 要连接的数据库
port 端口 一般填0,mysql默认端口 3306
unix_socket 本地套接字 ,一般填NULL
client_flag 连接标志 一般填0
返回值：成功返回 连接句柄,失败返回 NULL
 
