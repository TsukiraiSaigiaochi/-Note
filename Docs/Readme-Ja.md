# ヰnote

[简体中文](../README.md)<br>[English](Readme-En.md)

<!-- markdownlint-disable -->
<div align="center">

# ヰnote

シンプルなクイックメモツール

[問題を報告](https://github.com/TsukiraiSaigiaochi/-Note/issues)  
· [リリース版をダウンロード](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)

[![Version](https://img.shields.io/github/v/release/TsukiraiSaigiaochi/-Note)](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Stars](https://img.shields.io/github/stars/TsukiraiSaigiaochi/-Note?color=ffcb47&labelColor=black)</br>

![React 19](https://img.shields.io/badge/React-19-blue?logo=react)
![Tauri v2](https://img.shields.io/badge/Tauri-v2-%2324C8D8?logo=tauri)
![Rust Edition 2021](https://img.shields.io/badge/Rust-2021-%23000000?logo=rust)<br>

</div>

<!-- markdownlint-restore -->

---

## 概要

ヰnote は、軽量なローカルメモツールです。<br>
複雑な機能はあまりなく、遊べる機能も多くありません。<br>
どちらかというと、机の上に置いてあるメモ用紙のようなものです。必要なときに開いて、数行書き留めて、また作業に戻るためのツールです。

## 作った理由

私はずっと、使いやすくて、必要なときにすぐ呼び出せるシンプルなメモアプリを探していました。

それに、私はヰ組なので、メモを書くときにも推しの姿を見ていたいと思いました。

こうして、期末試験の勉強をしたくなかったある午後に、このアプリは生まれました。

## 機能

- **Markdown 対応** — Markdown 記法に対応しており、より文章を書く感覚に近い形で考えを記録できます

  ![Main Window](Images/main-window.png)

- **クイックメモ** — トレイまたはグローバルショートカットから、いつでもメモウィンドウを呼び出せます

  ![Quick Note](Images/quick-note.gif)

- **ローカル保存** — メモの内容はローカルに保存され、クラウドサービスには依存しません

- **Markdown インポート** — `.md` ファイルのインポートに対応しています

## 使い方

- アプリを起動した後、`CTRL + ALT + A` でメインウィンドウを呼び出せます
- アプリを起動した後、`CTRL + ALT + Q` でクイックメモウィンドウを呼び出せます

## 利用シーン

- **机の上のメモ用紙のように使う**

- コードを書いているときに、思いついたことをすぐにメモする

- ゲーム中に注意点をさっと書き留める

- 資料を読んでいるとき、授業中、復習中に断片的な考えを記録する

- 先生、上司、友人、あるいは AI にメッセージを送る前に、ここで一度文章を整える

- 一時的なクリップボードとして、何度もコピーする必要があるテキストを置いておく

## ダウンロード

[GitHub Releases](https://github.com/TsukiraiSaigiaochi/-Note/releases/tag/APP) からダウンロードできます。

Windows ユーザーは、リリースページからインストーラーをダウンロードできます。

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

