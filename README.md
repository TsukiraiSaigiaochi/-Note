# ヰnote

<!-- markdownlint-disable -->

<div align="center">

# ヰnote

A lightweight local sticky note app<br>

Built with Tauri 2 + React

[Report Issues](https://github.com/TsukiraiSaigiaochi/-Note/issues) · [Download Release](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)

[![Version](https://img.shields.io/github/v/release/TsukiraiSaigiaochi/-Note)](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Stars](https://img.shields.io/github/stars/TsukiraiSaigiaochi/-Note?color=ffcb47&labelColor=black)</br>

![React 19](https://img.shields.io/badge/React-19-blue?logo=react)
![Tauri v2](https://img.shields.io/badge/Tauri-v2-%2324C8D8?logo=tauri)
![Rust Edition 2021](https://img.shields.io/badge/Rust-2021-%23000000?logo=rust)<br>

</div>

<!-- markdownlint-restore -->

---

> I will translate it into English and Japanese Tomorrow
> But I wrote the key part  by English
## About

ヰnote 是一个轻量、本地、随叫随到的便签工具。

它不是复杂的知识库，也不是沉重的工作流软件。  
它更接近一个桌面上的草稿本：需要的时候打开，写下几句话，然后继续做自己的事情。

## Motivation

我一直想找一个用着顺手、随叫随到的简单笔记软件。

正好我又是个ヰ组，当然也希望写笔记的时候能看着我推写。

于是，在一个不想复习期末考试的下午，它诞生了。

## Features

- **Markdown Editing and Preview** — 支持 Markdown 语法，用更接近写作的方式记录想法

  ![Main Window](Docs/Images/main-window.png)

- **Quick Notes** — 通过托盘或全局快捷键随时唤出便签窗口

  ![Quick Note](Docs/Images/quick-note.gif)

- **Local Storage** — 笔记内容保存在本地，不依赖云端服务

- **Markdown Import** — 支持 `.md` 文件导入

## How to use
- you can call it by Ctrl+Alt+A
- you can also get a quick note by CTRL+ALT+Q

## Use Cases

- **像使用桌子上的草稿本一样使用它**

- 写代码的时候随手记一下思路

- 打游戏的时候随手记一下注意事项

- 看资料、听课、复习时快速记录片段想法

- 给老师、领导、朋友，甚至 AI 发送消息前，先在这里编辑一遍

- 当作临时剪贴板，暂存需要反复复制的文本

## Download

Download the latest version from [GitHub Releases](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP).

Windows users can download the installer from the Release page.

> This project is still under development.  
> If you encounter any problems, feel free to report them in [Issues](https://github.com/TsukiraiSaigiaochi/-Note/issues).

## Build from Source

### Requirements

- [Node.js](https://nodejs.org/) 18+
- [Rust](https://www.rust-lang.org/tools/install)
- [Tauri CLI 2](https://tauri.app/)

### Steps

```bash
git clone https://github.com/TsukiraiSaigiaochi/-Note.git

cd -Note

pnpm install

# Run in development mode
pnpm tauri dev

# Build release version
pnpm tauri build
```

The build output is usually located at:

```text
src-tauri/target/release/bundle/
```

## Roadmap

- 完善 Markdown 编辑与预览体验
- 优化快捷便签窗口
- 改进导入与本地存储逻辑
- 补充更多截图与使用说明
- 增加多语言 README 文档

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TsukiraiSaigiaochi/-Note&type=Date&legend=top-left)](https://star-history.com/#TsukiraiSaigiaochi/-Note&Date)

## Contributors

[![contrib.rocks](https://contrib.rocks/image?repo=TsukiraiSaigiaochi/-Note&max=1000)](https://contrib.rocks/image?repo=TsukiraiSaigiaochi/-Note&max=1000)

## License

[MIT](LICENSE)

## Language

This README currently uses an English structure with Chinese descriptions.

Japanese and English versions will be added later.  
In the future, the documentation will be separated into multiple language files, such as:

- `README.md`
- `README.zh-CN.md`
- `README.ja.md`
