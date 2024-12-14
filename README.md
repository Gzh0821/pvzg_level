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

## How to contribute to levels

Please `fork` this repository, then modify your configuration and upload the level file, and finally submit a `pull request` to this repository.

All configuration and level files are in the `docs` directory of this repository. You can refer to the format of the files in `official`.

### 1. Create a personal configuration

In the `custom` directory of `docs`, create a folder named after your nickname and create a `links.json` file in it with the content similar to:

```json
{
  "author": "example",
  "authorInfo": "This is a example of custom links.",
  "levelList": [
    {
      "fileName": "SampleLevel_I.json",
      "Information": {
        "uuid": "c58a208a-a5e3-4cfa-9bc3-cc7fbb08c2e3",
        "name": {
          "en": "SampleLevel I",
          "zh-CN": "Sample Level 1"
        },
        "Introduction": {
          "en": "This is a sample level.",
          "zh-CN": "This is a sample level."
        },
        "GameVersion": "0.1.1",
        "Version": "1.0",
        "CreatedAt": "2024-08-08",
        "UpdatedAt": "2024-08-08",
        "Difficulty": "Easy",
        "Category": "Survival"
      }
    },
    {
      "fileName": "MyLevel.json",
      "Information": {
        "uuid": "3e318b10-36f3-49c0-b01c-ad6842521d93",
        "name": {
          "en": "MyLevel",
          "zh-CN": "My Level"
        },
        "Introduction": {
          "en": "This is my level.",
          "zh-CN": "This is my level. "
        },
        "GameVersion": "0.1.1",
        "Version": "1.0",
        "CreatedAt": "2024-08-08",
        "UpdatedAt": "2024-08-08",
        "Difficulty": "Normal",
        "Category": "Survival"
      }
    }
  ]
}
```

Note: Do not upload or create files directly in the `custom` directory.

### 2. Bind personal configuration

Open the `links.json` file in the `docs` directory, and fill in your nickname and the location of your personal configuration in the `custom` column, similar to:

```json
{
  "custom": {
    "YourName": {
      "location": "custom/YourName/links.json"
    }
  }
}
```

### 3. Upload level files

Create a new `levels` in your personal configuration folder directory and upload your level file. The file name can be customized (cannot include spaces or special symbols except `_`),
but it must be in `.json` or `.json5` format.

In your `links.json`, fill in the level information, such as file name, etc.

### 4. Submit changes and initiate a Pull Request

After you have completed the configuration, you can submit your changes and initiate a Pull Request.

We recommend that you use VScode to submit. Just fill in the submission information in Source Control on the left side of VScode, then click Submit, and click Synchronize Changes.

To submit using the terminal:

- Add the modified code to Git:

```bash
git add .
```

- Submit the changes:

```bash
git commit -m "Describe your changes"
```

Push local changes to your own GitHub repository:

```bash
git push origin master
```

Then,go to your GitHub repository page.

- Click the `Compare & pull request` button at the top of the page.
- Fill in the description of the changes and submit a Pull Request.

We will review your Pull Request as soon as possible and provide feedback or merge as needed.