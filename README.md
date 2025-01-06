# MobaXterm 许可证生成器

一个简单的 MobaXterm 许可证生成器,支持深色、浅色主题和中文（简体、繁体）、英文及日语界面。

[English](./README_EN.md) | 简体中文

## demo

https://houyuxi012.github.io/MobaXterm_License_Generator/

## 功能特点

- 🎨 现代深浅色主题界面
- 🌏 支持多语言切换(简体中文、繁体中文、英文、日语)
- 🔑 支持生成专业版/教育版/个人版许可证
- 📱 响应式设计,支持移动端访问
- 🛡️ 纯前端实现,无需后端服务

## 环境要求

### 支持的浏览器
- Chrome 80+
- Firefox 75+
- Safari 13.1+
- Edge 80+

### 本地服务器(以下任选其一)
- Python Simple HTTPServer
- Node.js http-server
- PHP 内置服务器
- Apache/Nginx 等

## 快速开始

### 1. 克隆项目到本地目录

```
git clone https://github.com/houyuxi012/MobaXterm_License_Generator.git
```

### 2. 启动本地服务器(以下方式任选其一)

- [Node.js](https://nodejs.org/en/)
- [Python](https://www.python.org/)
- [PHP](https://www.php.net/)

#### 使用 Python (Python 3):
```bash
python -m http.server 8080
```

#### 使用 Node.js:
```bash
# 先安装 http-server
npm install -g http-server
# 启动服务
http-server -p 8080
```

#### 使用 PHP:
```bash
php -S localhost:8080
```


## 功能使用说明

1. 选择许可证类型(专业版/教育版/个人版)
2. 输入用户名(仅支持英文字母)
3. 输入版本号(如 24.00 或 24.1)
4. 输入用户数量(默认为 1)
5. 点击"生成许可证"按钮
6. 下载生成的 Custom.mxtpro 文件
7. 将文件导入 MobaXterm （1、安装版复制 Custom.mxtpro 到 C:\Program Files (x86)\Mobatek\MobaXterm ；2、免安装版复制 Custom.mxtpro 到 MobaXterm 根目录）即可使用

## 注意事项

- 用户名仅支持英文字母
- 版本号格式为 x.x,最多支持一位小数
- 用户数量必须为正整数
- 建议使用最新版本的现代浏览器
- 需要本地 Web 服务器环境

## 作者

- **HouYuXi**
- Email: houyuxi123@gmail.com
- GitHub: https://github.com/houyuxi012

## 许可证

本项目基于 MIT 许可证开源 - 详见 [LICENSE](LICENSE) 文件

Copyright (c) 2023 HouYuXi

## 免责声明

本项目仅供学习和研究使用,请勿用于商业用途。使用本项目所产生的一切后果由使用者自行承担。

## 贡献

欢迎提交 Issue 和 Pull Request 来帮助改进这个项目。

## 更新日志

### v1.0.0 (2023-06-17)
- 初始版本发布
- 支持生成三种类型许可证
- 支持多语言切换切换
- 浅色/深色主题界面


## 项目结构
mobaxterm-keygen/
├── css/
│ ├── pure-min.css # Pure.css 框架
│ └── style.css # 自定义样式
├── js/
│ ├── FileSaver.js # 文件保存工具
│ ├── jszip.js # ZIP 文件处理
│ ├── vue.min-2.6.12.js # Vue.js 框架
│ └── mobaXtermGenerater.js # 许可证生成核心代码
├── index.html # 主页面
├── README.md # 中文说明文档
├── README_EN.md # 英文说明文档
└── LICENSE # 开源许可证

## 技术栈

- Vue.js 2.6.12 - 前端框架
- Pure.css - CSS 框架
- JSZip - ZIP 文件处理
- FileSaver.js - 文件下载
