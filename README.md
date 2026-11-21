# ACME 浏览器证书客户端

> 单文件 H5 版 ACME 客户端，可在线免费申请签发 Let's Encrypt / ZeroSSL 等 CA 的 SSL/TLS（含泛域名）证书。

在线体验：https://wangchenyu.com/ssl/

## 功能特性

- 浏览器内完成 ACME 协议签发流程
- 支持 Let's Encrypt、ZeroSSL 等公共目录
- 申请私钥与 CSR 在本地生成
- 单文件，无需安装依赖

## 使用方法

1. 用浏览器直接打开 `index.html`，无需安装任何软件、无需构建、无需后端服务。
2. 所有计算与处理均在浏览器本地完成，数据不会上传到服务器。
3. 处理完成后使用页面上的复制 / 导出按钮即可保存结果。

## 技术栈

原生 JavaScript 单文件应用

## 目录结构

```
├── index.html        # 主页面
├── assets/ 或本地资源 # 样式、脚本与静态资源（按需）
```

## 致谢

基于 xiangyuecn/ACME 能力思路实现。

## 说明

本项目由 [wangchenyu.com](https://wangchenyu.com/) 整理并开源，仅供学习与个人使用。
