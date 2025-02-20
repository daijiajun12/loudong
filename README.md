# loudong
响应云安全漏洞库
by：响应云安全
快手：2830261681
---

# 漏洞数据库应用说明文档

## 概述

本项目是一个基于 Flask 的漏洞数据库应用，允许用户搜索和查看漏洞信息。应用支持以下功能：

- **首页**：提供搜索功能，用户可以输入关键词搜索漏洞。
- **搜索结果**：显示与关键词匹配的漏洞列表。
- **漏洞详情**：显示特定漏洞的详细信息，包括相关的 Markdown 文件。
- **Markdown 查看**：解析并显示 Markdown 文件内容。
- **漏洞测试**：提供一个简单的漏洞测试工具，用户可以输入 URL 和其他参数进行测试。

## 项目结构

```
漏洞库/
├── app.py
|—— app.exe
├── templates/
│   ├── index.html
│   ├── search.html
│   ├── vuln.html
│   └── md_view.html
├── static/
│   ├── (静态文件，如 CSS、JS 等)
│   └── (漏洞文件夹，每个文件夹包含 .md 文件)
├── setup.py
└── vuln.spec
```

## 依赖库

- `Flask`
- `markupsafe`
- `os`
- `markdown`
- `re`
- `requests`

## 安装依赖

在项目根目录下运行以下命令安装所有依赖库：

```sh
pip install -r requirements.txt
```

`requirements.txt` 内容示例：

```
Flask
markupsafe
markdown
requests
```

## 运行应用

直接点击exe文件即可然后浏览器访问 http://127.0.0.1:5000/
        
