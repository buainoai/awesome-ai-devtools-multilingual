# 贡献指南 / Contributing Guidelines

感谢您对本项目的关注！本文档提供了贡献的指南和说明。

Thank you for your interest in contributing! This document provides guidelines and instructions.

---

## 目录

- [添加新工具](#添加新工具)
- [改进翻译](#改进翻译)
- [添加新语言](#添加新语言)
- [报告问题](#报告问题)
- [Pull Request 流程](#pull-request-流程)

## 添加新工具

1. **Fork** 本仓库并创建一个新分支
2. 在 `i18n/README.en.md`（英文版）的适当分类中添加工具
3. 请遵循以下格式：
   ```markdown
   - [工具名称](https://tool-url.com/) — 工具的简要描述及其主要功能。
   ```
4. 请确保该工具满足以下条件：
   - 是 AI 驱动或 AI 增强的工具
   - 与软件开发相关
   - 有可用的网站或代码仓库
   - 尚未被收录
5. 提交 Pull Request

## 改进翻译

1. 进入 `i18n/` 目录
2. 打开您想改进的语言文件（例如 `README.zh.md` 为中文）
3. 进行修改时请遵循以下规则：
   - 保留工具名称、URL 和技术术语为英文
   - 保持所有 Markdown 格式不变
   - 确保语言导航栏保持完整
4. 提交 Pull Request，并清楚描述改进了什么

## 添加新语言

1. 复制 `i18n/README.en.md` 作为模板
2. 将文件命名为 `README.{语言代码}.md`（例如 `README.ar.md` 为阿拉伯语）
3. 在文件顶部添加语言导航栏
4. 翻译所有章节标题和描述
5. 保留工具名称、URL 和技术术语为英文
6. 更新主 `README.md` 以包含新语言
7. 更新所有现有文件中的语言导航栏
8. 提交 Pull Request

## 报告问题

- 使用 GitHub Issues 报告错误或建议改进
- 请提供尽可能多的详细信息
- 对于翻译问题，请指明语言和需要修正的具体文本

## Pull Request 流程

1. 确保您的更改遵循现有的格式规范
2. 如有必要，更新主 `README.md`
3. 您的 PR 将由维护者审查
4. 一旦批准，将合并到主分支

## 行为准则

- 在所有交流中保持尊重和建设性
- 欢迎新人并帮助他们入门
- 关注对社区最有利的事情

感谢您帮助全球开发者更好地获取 AI 开发者工具！
