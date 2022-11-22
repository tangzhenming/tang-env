# 基于 Docker 的跨平台的开发环境（Windows/macOS/Linux）

## 使用方式

1. VSCode 安装 Remote Container
2. 创建项目文件夹 >>> 创建 Dockerfile >>> `FROM tangzhenming1207/tang-env`
3. 使用 Remote Container 打开项目（From Dockerfile）
4. 直接在目录内开发，比如创建 node-project 、go-project 等子目录

## 环境

- alpine 3
- bash, git, curl
- node
- rbenv, ruby, bundle
- 均配置国内镜像源（node 除外）
