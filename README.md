# 🃏 Poker Soundboard

一个用于德州扑克游戏的网页音效面板，点击按钮即可播放对应语音，手机电脑均可使用。

## 🌐 在线体验

👉 [https://edwinzzzw.github.io/Poker-Soundboard/](https://edwinzzzw.github.io/Poker-Soundboard/)

无需安装任何软件，打开链接即用。

## ✨ 功能

- 点击按钮播放对应语音
- 再次点击可停止播放
- 同时只播放一个语音，自动停止上一个
- 播放时显示进度条和状态指示灯
- 支持手机、平板、电脑等所有设备

## 🛠 技术

纯原生前端开发，无任何框架依赖。

- HTML
- CSS
- JavaScript (Vanilla JS)

托管于 GitHub Pages，免费、永久有效。

## 📁 项目结构

```
Poker-Soundboard/
├── index.html     # 主页面
└── Poker/         # 音频文件夹
    ├── sound1.mp3
    ├── sound2.mp3
    └── ...
```

## 🔧 自定义修改

如需添加或修改语音，打开 `index.html`，找到以下代码段进行编辑：

```js
const sounds = [
  { name: "按钮名称", file: "Poker/文件名.mp3" },
  // 继续添加...
];
```

## 📄 License

MIT — 自由使用、修改、分享。
