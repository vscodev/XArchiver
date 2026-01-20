# XArchiver

[![GitHub Release](https://img.shields.io/github/v/release/vscodev/XArchiver)](https://github.com/vscodev/XArchiver/releases)

网上下载的压缩包资源找不到解压密码？欢迎使用XArchiver碰碰运气~

![screenshot](https://cdn.jsdelivr.net/gh/vscodev/XArchiver@main/screenshot.png)

## 概述

一般来说，压缩包密码是不可能被破解的。以 [Unicode® 13.0.0](https://www.unicode.org/versions/Unicode13.0.0/) 为例，官方公布的字符数有143859个，假设解压密码最多3个字符，可能性就超过 $143859^{3} > 2.97 \times 10^{15}$ 种，每秒处理1亿个密码也需要近1年的时间。因此，如果你的电脑没有比肩超级计算机的算力，任何所谓的破解都是徒劳的！

然而在很多情况下，某个网站分享资源使用的解压密码是既定的，比如 `www.example.com`  通常以 `example` 或者 `example.com` 作为默认的解压密码。实践表明，发掘和收集这些资源分享站常用的解压密码，通过高质量的密码字典来破解那些你找不到出处的加密压缩包资源是可能的，XArchiver因此诞生。

XArchiver是一款基于大数据的压缩包密码破解软件，它并不穷举所有可能性，而仅遍历那些在网上被经常使用的解压密码，在大幅提升破解效率的同时成功率也远高于传统的暴力破解方式。

## 下载安装

XArchiver支持在Windows 10及以上版本的64位系统上运行，你可以前往 [Releases](https://github.com/vscodev/XArchiver/releases) 页面下载软件的最新版本。

## 注意事项

XArchiver帐号仅限本人使用，不得分享、外借或转让。如果你滥用本站提供的服务，包括但不限于伪造压缩包测试软件的功能、模拟客户端的网络请求试图攻击服务器，系统有权在不通知的情况下封设备、封IP、封帐号！
