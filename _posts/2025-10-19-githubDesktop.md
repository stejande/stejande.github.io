---
layout:     post
title:      "mac 安装 github desktop 汉化"
subtitle:   " "
date:       2025-10-19 22:07:00
author:     "Stejande"
# header-img: "img/post-in/post-bg-2025.jpg"
catalog: true
tags:
    - mac安装配置
---

1. 安装包链接🔗https://github.com/zetaloop/desktop?tab=readme-ov-file

2. 注意链接文档中提示：
	* macOS 安装后如提示损坏，请运行 `xattr -rd com.apple.quarantine "GitHub Desktop.app"`。

3. 如果输入命令行还是错误：找不到GitHub Desktop.app的位置
【手动指定路径】在命令行里加入路径。比如我自动下载到 downloads 文件夹，
`xattr -rd com.apple.quarantine ~/Downloads/"GitHub Desktop.app"`