+++
title = 'qBittorrent 美化'
slug = "qbittorrent-beautify"
date = '2025-08-20T00:00:00+08:00'
image = "post/2025/08/qbittorrent-beautify/img/cover.webp"
license = ""
categories = ["IT"]
tags = ["Beautify"]
+++

> 图片：[Day 18 天依](https://www.pixiv.net/artworks/129644254)  
> 画师：[MORI森](https://www.pixiv.net/users/14292311)

## 前言
不知道大家使用 qBittorrent 的时候有没有反感过它丑陋的 UI，虽然新版本的 UI 勉强看的过去，但还是不够现代化。
因此，我找到了一些好看的主题来让 qBittorrent 更现代化。

## 美化 GUI
### 主题
下载 [qBitTorrent-fluent-theme](https://github.com/witalihirsch/qBitTorrent-fluent-theme) 主题。
如果你的 qBittorrent 版本大于 5.x 版本，可以下载 [defaulticons-fluent.zip](https://github.com/user-attachments/files/17586876/defaulticons-fluent.zip) 或 [Pre-5.0-icons-fluent.zip](https://github.com/user-attachments/files/17588035/Pre-5.0-icons-fluent.zip)。
前者使用 qBittorrent 原版风格图标，后者使用 Fluent 风格图标。

最后添加 `.qbtheme` 文件至 `工具-设置-行为-使用自定义界面主题-界面主题文件`，可按个人喜好自行选择。

###  MicaForEveryone
`qBitTorrent-fluent-theme` 主题需要 MicaForEveryone 才能正常显示，因此需要下载 [MicaForEveryone](https://github.com/MicaForEveryone/MicaForEveryone)。
我下载的是 `v1.3.1.2` 版本，如果遇到什么问题，可以先尝试安装这个版本。

下载完后运行 MicaForEveryone，点击左下角添加规则，点击依据程序名添加规则，输入 `qbittorrent`。
启用将窗口框架扩展到客户区。

## 美化 WebUI
下载 [VueTorrent](https://github.com/VueTorrent/VueTorrent)，选择最新版本。

勾选 `工具-设置-WebUI-使用备用的WebUI`，解压后添加至 `文件位置`。

## 对比
![GUI Before](post/2025/08/qbittorrent-beautify/img/image-00.webp)
![GUI After](post/2025/08/qbittorrent-beautify/img/image-01.webp)
![WebUI Before](post/2025/08/qbittorrent-beautify/img/image-02.webp)
![WebUI After](post/2025/08/qbittorrent-beautify/img/image-03.webp)
