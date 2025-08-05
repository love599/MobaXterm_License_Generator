# MobaXterm 许可证生成器

一个简单的 MobaXterm 许可证生成器,支持深色、浅色主题和中文（简体、繁体）、英文及日语界面。

[English](./README_EN.md) | 简体中文

## 演示环境（可以正常使用）

https://houyuxi012.github.io/MobaXterm_License_Generator/

https://mobaxterm.agent.houyuxi.com/

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
## Docker 一键部署（最简单）

```bash
#1.启动容器 (容器标签根据运行电脑选择arm或者x86)
docker run -d -p 8080:80 houyuxi/mobakey:x86
#2.访问系统
http://localhost:8080
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

