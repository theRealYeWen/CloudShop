# CloudShop

CloudShop是一个基于Spring Cloud的微服务电商平台。

## 技术栈

- Spring Boot 3.2.3
- Spring Cloud 2023.0.0
- Spring Cloud Alibaba 2022.0.0.0
- MySQL 8.0
- Redis 7.0
- Nacos 2.2.3
- MyBatis Plus 3.5.5

## 项目结构

```
CloudShop/
├── cloud-shop-common/        # 公共模块
├── cloud-shop-gateway/       # 网关服务
├── cloud-shop-user/         # 用户服务
├── docker-compose.yml       # 开发环境配置
└── pom.xml                  # 父POM
```

## 开发环境

1. 安装Docker和Docker Compose
2. 克隆项目
3. 运行开发环境：
   ```bash
   docker-compose up -d
   ```
4. 访问服务：
   - Nacos: http://localhost:8848
   - SonarQube: http://localhost:9000

## 开发规范

- 使用Git Flow工作流
- 遵循Angular提交规范
- 代码提交前需要通过SonarQube检查

## 许可证

MIT License