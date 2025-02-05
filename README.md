# 11_18_vmanagent

## 项目简介

11_18_vmanagent 是一个基于 Go 和 Gin 框架的后端项目，旨在提供虚拟机管理的相关功能。该项目包含了基本的路由配置和跨域资源共享（CORS）设置。

## 功能特性

- 基于 Gin 框架的高性能 HTTP 服务器
- 配置了 CORS 以支持跨域请求
- 提供虚拟机管理的相关 API

## 文件结构

```
11_18_vmanagent/
├── vmbackend/
│   ├── main.go
│   ├── router/
│   │   └── router.go
│   └── ...其他文件
└── README.md
```

## 安装与运行

### 环境依赖

- Go 1.16 及以上版本
- Gin 框架

### 安装步骤

1. 克隆项目到本地：

   ```sh
   git clone https://github.com/yourusername/11_18_vmanagent.git
   ```

2. 进入项目目录：

   ```sh
   cd 11_18_vmanagent/vmbackend
   ```

3. 下载依赖包：
   ```sh
   go mod tidy
   ```

### 运行项目

在项目根目录下执行以下命令启动服务器：

```sh
go run main.go
```

服务器启动后，默认监听在 `http://localhost:8000`。

## 贡献

欢迎提交 issue 和 pull request 来帮助我们改进项目。

## 许可证

该项目使用 MIT 许可证，详情请参阅 LICENSE 文件。
