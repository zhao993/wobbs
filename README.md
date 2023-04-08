# wobbs
## 启动

1. 克隆项目：`https://github.com/zhao993/wobbs.git`。
2. 修改配置文件 `wobbs/wobbs-server/config/config.yaml`，主要修改Mysql、Redis相关配置。
3. 创建数据库 `wobbs`。
4. 启动后端服务，运行 `wobbs/wobbs-server/main.go`，会自动创建表。
5. 浏览器访问 `http://localhost:8080`，可以看到如下页面：

![image-20230408143110651](https://user-images.githubusercontent.com/116085959/230707204-98f7fbc9-1ef5-490b-b488-ce4471cc11a8.png)

表示启动成功。

## 功能介绍

web论坛项目

## 技术栈

- Gin
- Gorm
- MySQL
- Redis
- Vue
- jwt
- 配置文件管理：viper
- 分布式ID：snowflake
- 参数校验：validator
- 日志库：zap
- 热重启：air
