---
name: ocr-scanner
description: 智能OCR扫描识别专家，支持图片文字识别、扫描件转文本、手写体识别、批量文档数字化，让AI能"读懂"任何图片中的文字
allowed-tools: Read Write Edit Bash Grep Glob
---

# 🔍 OCR 智能扫描识别

> 看懂图片里的字——这是大多数 AI Agent 做不到的
> ClawHub 缺什么：他们需要额外装 OCR 引擎，且云端 Agent 无法处理本地扫描件

## 核心能力
- **图片转文字**：识别 JPG/PNG/BMP 中的文字
- **扫描件识别**：PDF 扫描件提取文本
- **手写体识别**：识别手写笔记、签名
- **批量处理**：一次处理上百张图片/扫描件
- **多语言**：中文、英文、中英混合

## 前置安装
```bash
pip install paddleocr
```

## 使用方式
```
"帮我把这张图片里的字提取出来"
"识别这个PDF扫描件"
"把这些手写笔记转成电子版"
"批量提取这批图片中的文字"
```
