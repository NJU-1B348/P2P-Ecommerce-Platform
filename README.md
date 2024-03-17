# P2P二手交易平台 项目

## 项目介绍

本项目是一个类似于闲鱼、转转的二手交易平台，用户可以在平台上发布自己的二手商品，也可以购买别人的二手商品。本项目采用的技术栈为Django+SQLite。本项目时南京大学网络应用开发的课程项目。

## 项目功能

- 用户注册、登录、注销
- 商品信息管理
- 订单信息管理
- 用户发布商品
- 用户购买商品
- 用户查看商品详情
- 用户按条件查看商品列表
- 用户搜索商品
- 用户查看订单详情
- 用户投诉

## 开发规范

- 代码规范：PEP8
  - 可使用 Pycharm 的 PEP8 检查工具或 vscode 的 Pylint 插件进行代码规范检查
- Git 规范
  - 从 master 分支签出新分支进行开发 `git checkout -b dev/xxxxx`
  - 分支合并到 master 分支前，需要进行测试和代码审查
  - 分支合并到 master 分支时，需要明确更改的信息
  - 分支合并到 master 分支后，若与 master 分支有冲突，或落后多个版本，可以签出新分支进行开发

## 开发准备

**Step 1**: 安装 Python3.11 或 conda (anaconda/miniconda)。

**Step 2**: 创建虚拟环境，安装依赖。 Django version: 5.0.4

**Step 3**: 熟悉 Django 应用的基本结构，了解 Django 的基本使用方法。

**Step 4**: 熟悉 HTML5、CSS3、JavaScript 等前端技术。