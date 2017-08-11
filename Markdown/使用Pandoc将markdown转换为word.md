# 使用Pandoc将Markdown转换为Word格式

## 背景
使用Word编写日常文档通常费时费力，主要是因为需要频繁的键鼠切换操作+修正排版(强迫症)
使用Markdown可以较好的解决这个问题，但是在日常办公中往往需要以Word来作为文档交换的最终稿。

## 解决方案-Pandoc
### 简介
Pandoc是一套开源的文稿格式转换程序，支持很多种文稿的格式互转
且可以在Word里保持Markdown文稿的结构(效果实测很不错)

### 使用步骤
1. 安装Pandoc
  [Github](https://github.com/jgm/pandoc/releases)
  下载Windows安装包并安装

2. 启动cmd或powershell
3. 通过cd命令进入文档所在文件夹(建议)
**如果不进入目录文件夹，如果markdown中包含本地图片，且图片地址为相对路径(./images/...)这种，pandoc会无法识别图片(pandoc要么识别绝对路径的图片，要不以当前所在位置认为是根目录)**


3. 按照命令格式转换

```
pandoc 文档.md -o 要输出的名称.docx
```
-o表示代表输出的意思

Tags: Markdown转Word, Markdown输出
