# 11_18_vmanagent

## 项目简介

11_18_vmanagent 是一个基于 Go 和 Gin 框架的后端项目，旨在提供虚拟机管理的相关功能。该项目包含了基本的路由配置和跨域资源共享（CORS）设置。

## 功能

- 基于 Gin 框架的高性能 HTTP 服务器
- 支持跨域请求（CORS）
- 提供 RESTful API 接口
- 支持 GET, POST, PUT, DELETE, OPTIONS 请求方法

## 目录结构

```
/d:/golang/goproject/src/11_18_vmanagent/
├── vmbackend/
│   ├── main.go        # 主程序入口
│   ├── router/
│   │   └── router.go  # 路由配置
│   ├── controller/    # 控制器
│   ├── service/       # 服务层
│   ├── model/         # 数据模型
│   ├── middleware/    # 中间件
│   └── config/        # 配置文件
├── frontend/          # 前端代码
│   ├── public/        # 静态资源
│   ├── src/
│   │   ├── assets/    # 资源文件
│   │   ├── components/# 组件
│   │   ├── views/     # 视图
│   │   ├── router/    # 前端路由
│   │   └── store/     # 状态管理
└── README.md          # 项目说明文件
```

## 安装

1. 确保已安装 Go 语言环境（版本 1.16 及以上）。
2. 获取项目代码：
   ```sh
   git clone https://github.com/yourusername/vmbackend.git
   ```
3. 进入项目目录：
   ```sh
   cd /d:/golang/goproject/src/11_18_vmanagent/vmbackend
   ```
4. 安装依赖：
   ```sh
   go mod tidy
   ```

## 运行

1. 在项目根目录下运行以下命令启动服务：
   ```sh
   go run main.go
   ```
2. 服务启动后，默认监听在 `http://localhost:8000`。

## 使用

可以使用 Postman 或 curl 等工具测试 API 接口。例如：

```sh
curl -X GET http://localhost:8000/your-endpoint
```

## 贡献

欢迎提交 issue 和 pull request 来帮助改进项目。

## 许可证

此项目使用 MIT 许可证。详情请参阅 LICENSE 文件。
