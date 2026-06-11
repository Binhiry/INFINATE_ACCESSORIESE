# INFINITÉ Accessories 管理系统

## 项目概述

INFINITÉ Accessories 是一个专业的暗黑风格饰品穿搭商城后台管理系统，提供完整的商品管理、订单处理、用户管理等功能。

# 操作

################

解压后需在api文件夹下进入powershell,键入node server.js以启动本地服务器.

使用平台前可提前插入数据库数据,此前运行sql文件夹下的建表语句即可.

################



## 技术架构

### 前端

- HTML5 + CSS3
- Vanilla JavaScript
- 响应式设计
- 暗黑主题UI

### 后端

- PHP 7.4+
- MySQL 8.0+
- RESTful API
- PDO 数据库操作

### 数据库配置

- XML配置文件：`database-config.xml`
- 数据库初始化脚本：`database-setup.sql`



## 故障排除

### 常见问题

1. **数据库连接失败**
   
   - 检查 `database-config.xml` 中的数据库配置
   - 确认MySQL服务正在运行
   - 验证用户名和密码

2. **API请求失败**
   
   - 检查 `api/products.php` 文件权限
   - 确认PHP PDO扩展已安装
   - 查看Web服务器错误日志

3. **页面样式显示异常**
   
   - 检查 `shared.css` 文件是否存在
   - 确认CSS文件路径正确

### 调试模式

在浏览器开发者工具中查看控制台输出，检查JavaScript错误和网络请求状态。


