# PvZ2 Gardendless Official Custom Level Repo

![](https://img.shields.io/badge/author-Gaozih-%2366ccff)
![](https://img.shields.io/github/license/Gzh0821/pvzg_level)
![](https://img.shields.io/github/stars/Gzh0821/pvzg_level)

This is the official custom level repository for PvZ2 Gardendless.
You can contribute and download the custom levels here and play them in the game.

## Game Introduction

"PvZ2 Gardendless" is a rewritten "Plants vs Zombies 2" entirely using only Web technologies(including the cocos engine)!

Visit our [website](https://pvzge.com/en/) for download links, game guides and more. You can also report bugs, make comments and suggestions in the feedback module of the website or in the issues and discussions of this project!

“PvZ2 Gardendless”是完全使用 Web 技术（包括 cocos 引擎）重写的“植物大战僵尸 2”！

访问我们的[网站](https://pvzge.com)获取下载链接、游戏指南等。您还可以在网站的反馈模块或本项目的问题和讨论中报告错误、发表评论和建议！

## 如何贡献关卡

请 `fork` 本仓库，然后修改你的配置和上传关卡文件，最后提交 `pull request` 到本仓库。
所有配置和关卡文件均在本仓库的 `docs` 目录下。

### 1.创建个人配置

在 `docs` 的 `custom` 目录下，创建一个以你的昵称命名的文件夹，并在其中新建一个 `links.json` 文件。

注：不要在 `custom` 目录下直接上传或创建文件。

### 2.绑定个人配置

打开 `docs` 目录的 `links.json` 文件，在 `custom` 一栏中，填写你的昵称和个人配置的位置，类似于：

```json
{
  "custom": {
    "YourName": {
      "location": "custom/YourName/links.json"
    }
  }
}
```
