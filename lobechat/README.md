# LobeHub - AI 对话助手平台

LobeHub 是一个开源的 AI 对话助手平台，支持多种 AI 模型，提供优雅的用户界面和强大的功能。集成 Casdoor 身份认证、PostgreSQL 数据库和 RustFS 对象存储，一键部署服务端数据库版本。

## 服务组件

| 组件 | 地址/端口 | 说明 |
|------|----------|------|
| LobeChat 主应用 | http://服务器IP:33210 | 安装时配置 |
| Casdoor 身份认证 | http://服务器IP:38000 | 管理员 admin / 初始密码 123 |
| PostgreSQL 数据库 | 35432 | 用户 postgres / 密码 postgres |
| RustFS 对象存储 | API 39000 / 控制台 39001 | Access Key: rustfsadmin / Secret Key: rustfsadmin |

## 使用说明

- 首次启动最长约 10 分钟，同时下载 4 个镜像
- 首次使用需要注册账号
- 关于反向代理请查阅官方文档

## 维护信息

- 开发者：LobeChat Community
- 发布者：听闻
- 版本：1.0.0
- 平台：x86
