---
name: format-factory
description: 批量格式转换工厂，支持图片/文档/音频/视频之间的任意格式互转，一键批量处理，无需手动操作
allowed-tools: Read Write Edit Bash Grep Glob
---

# 🏭 批量格式转换工厂

> 任何格式转任何格式，一键批量处理
> ClawHub 缺什么：他们最多有个别单项转换，无法一站式批量处理全部格式

## 支持转换
| 输入 | → | 输出 |
|:----|:-:|:----|
| JPG/PNG/WebP | → | PDF（合并成册） |
| PDF | → | DOCX/TXT/图片 |
| DOCX | → | PDF/PDF |
| MP4/AVI/MOV | → | MP3（提取音频） |
| MP3/WAV | → | 文字（语音转文字） |
| 网页URL | → | PDF/图片（截图保存） |
| 批量图片 | → | 统一格式/尺寸/命名 |

## 前置安装
```bash
pip install Pillow
```
已安装：ffmpeg（Playwright自带）、yt-dlp、edge-tts

## 使用方式
```
"把这10张图片合并成一个PDF"
"把这个PDF转成Word"
"把这个视频的音频提取出来"
"把这一批图片统一改成PNG格式并压缩"
```
