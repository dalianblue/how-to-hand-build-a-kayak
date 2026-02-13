# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

这是一个关于皮划艇建造技术的中文技术文档项目（makeakayak）。主要包含《艺术级皮划艇建造技术》的多种格式文档。

## 文档结构

```
.
├── 艺术级皮划艇建造技术-印刷(1).docx    # Microsoft Word 源文档
├── 艺术级皮划艇建造技术-印刷(1).pdf     # PDF 格式文档
├── 艺术级皮划艇建造技术-印刷(1).html    # HTML 格式导出文档
├── 艺术级皮划艇建造技术-印刷(1).fld/    # 文档资源文件夹（包含图片、样式等）
└── .claude/settings.local.json          # Claude Code 配置文件
```

## 资源文件夹结构

`艺术级皮划艇建造技术-印刷(1).fld/` 文件夹包含从 Word 文档导出的所有资源文件：
- 图片文件（image*.jpg/png）
- HTML 片段（header.html 等）
- XML 配置文件（filelist.xml, themedata.thmx 等）
- 编辑数据（editdata.mso）

## 工作模式

此目录配置了受限的 Bash 权限（通过 `.claude/settings.local.json`）：
- 允许使用 `find` 和 `ls` 命令进行文件浏览

## 文档语言

所有文档内容均为简体中文。处理文档时请使用简体中文进行沟通。

## 常见任务

由于这是一个文档目录而非代码仓库，常见任务可能包括：
- 提取文档中的图片或内容
- 转换文档格式
- 查阅特定的建造技术章节
- 分析文档结构
