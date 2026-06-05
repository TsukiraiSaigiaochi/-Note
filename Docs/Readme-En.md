# ヰnote

[简体中文](../README.md)<br>[日本語](Readme-Ja.md)

<!-- markdownlint-disable -->
<div align="center">

# ヰnote

A simple quick note-taking tool

[Report an Issue](https://github.com/TsukiraiSaigiaochi/-Note/issues)  
· [Download Release](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)

[![Version](https://img.shields.io/github/v/release/TsukiraiSaigiaochi/-Note)](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Stars](https://img.shields.io/github/stars/TsukiraiSaigiaochi/-Note?color=ffcb47&labelColor=black)</br>

![React 19](https://img.shields.io/badge/React-19-blue?logo=react)
![Tauri v2](https://img.shields.io/badge/Tauri-v2-%2324C8D8?logo=tauri)
![Rust Edition 2021](https://img.shields.io/badge/Rust-2021-%23000000?logo=rust)<br>

</div>

<!-- markdownlint-restore -->

---

## About

ヰnote is a lightweight local sticky note tool.<br>
It does not have many complex features, nor does it offer much in terms of playful functionality.<br>
It is more like a draft paper on your desktop: open it when needed, write down a few lines, and then get back to what you were doing.

## Motivation

I had always wanted a simple note-taking app that felt smooth to use and could be brought up instantly.

Also, as a member of ヰ組, I naturally wanted to look at my oshi while writing notes.

So, on an afternoon when I did not feel like reviewing for my final exams, this project was born.

## Features

- **Markdown Support** — Supports Markdown syntax, allowing you to record your thoughts in a way that feels closer to writing

  ![Main Window](Images/main-window.png)

- **Quick Note** — Bring up the note window at any time through the system tray or global shortcuts

  ![Quick Note](Images/quick-note.gif)

- **Local Storage** — Notes are stored locally and do not rely on any cloud service

- **Markdown Import** — Supports importing `.md` files

## Usage

- After launching the app, press `CTRL + ALT + A` to bring up the main window
- After launching the app, press `CTRL + ALT + Q` to bring up the quick note window

## Use Cases

- **Use it like a piece of draft paper on your desk**

- Quickly jot down ideas while coding

- Take quick notes while playing games

- Record fragmented thoughts while reading, attending classes, or reviewing

- Edit a message here before sending it to a teacher, a boss, a friend, or even an AI

- Use it as a temporary clipboard for text that needs to be copied repeatedly

## Download

Download from [GitHub Releases](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP).

Windows users can download the installer from the release page.

> This project is still under development.  
> If you encounter any problems, feel free to report them in [Issues](https://github.com/TsukiraiSaigiaochi/-Note/issues).

## Build
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


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TsukiraiSaigiaochi/-Note&type=Date&legend=top-left)](https://star-history.com/#TsukiraiSaigiaochi/-Note&Date)

## Contributors

[![contrib.rocks](https://contrib.rocks/image?repo=TsukiraiSaigiaochi/-Note&max=1000)](https://contrib.rocks/image?repo=TsukiraiSaigiaochi/-Note&max=1000)

## License

[MIT](LICENSE)

