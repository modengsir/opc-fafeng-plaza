<div align="center">

# 🤪 OPC 发疯广场 3D · 枪械版

**现实里不能发疯，游戏里优雅发疯。**

[![🎮 在线玩](https://img.shields.io/badge/🎮_在线玩-GitHub_Pages-ff5f9e?style=for-the-badge)](https://modengsir.github.io/opc-fafeng-plaza/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Three.js](https://img.shields.io/badge/Three.js-r157-000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org)
[![纯静态](https://img.shields.io/badge/纯静态-0_依赖-brightgreen?style=for-the-badge)](#)
[![单文件](https://img.shields.io/badge/HTML-单文件_即开即玩-orange?style=for-the-badge)](#)
[![发疯指数](https://img.shields.io/badge/发疯指数-★★★★★-red?style=for-the-badge)](#)

一人公司（OPC）创业者专用 3D 解压射击场<br/>
🔫 突突 Bug · 💥 轰离谱需求 · 🎯 狙焦虑气泡<br/>
90 秒把焦虑打到 0，领取「今日发疯战报」！

</div>

---

## 🎮 在线玩

👉 **https://modengsir.github.io/opc-fafeng-plaza/**

## 📸 游戏截图

<table>
  <tr>
    <td align="center"><img src="screenshots/01-start.png" width="260"/><br/>① 进广场开火</td>
    <td align="center"><img src="screenshots/02-game.png" width="260"/><br/>② 全景开火 · 红闪警告</td>
    <td align="center"><img src="screenshots/03-report.png" width="260"/><br/>③ 今日发疯战报</td>
  </tr>
</table>

## 🕹️ 玩法

| 区域 | 武器 | 规则 |
|------|------|------|
| 🐛 Bug 垃圾场 | 🔫 冲锋枪（长按连发） | Bug 逃跑前红闪警告，跑了 +3 焦虑 |
| 📦 需求回收站 | 💥 霰弹枪 | 只轰离谱需求卡；误伤合理需求 +6 焦虑 |
| 💭 焦虑气泡池 | 🎯 狙击枪（开镜穿透） | 一枪串一串气泡，飘走 +3 焦虑 |

- 🖱️ 点击 / 空格：开火
- ⌨️ `1` / `2` / `3` 或底部按钮：换枪切区
- 🏆 焦虑打到 0 → 领取战报 → 一键复制晒朋友圈

## 🚀 本地运行

```bash
npx serve .
# 或
python3 -m http.server 8080

```

> 需联网加载 Three.js（jsDelivr CDN）。

## 📦 部署 GitHub Pages

1. 打开 https://github.com/modengsir/opc-fafeng-plaza/settings/pages
2. Source 选 **Deploy from a branch**
3. Branch 选 **main** + **/(root)** → Save
4. 约 1 分钟后访问 https://modengsir.github.io/opc-fafeng-plaza/

## 🗂️ 项目结构

```
├── index.html       # 游戏本体（单文件）
├── promo/推特官宣.md # 开源推特文案
├── screenshots/     # README 截图墙
├── README.md
├── LICENSE
└── .gitignore

```

## 🗺️ 路线图

- [x] 三枪三区 + 连击 / 震屏 / 粒子 / 音效
- [x] 靶子逃跑红闪警告 + 狙击开镜
- [ ] 手机触屏优化
- [ ] 本地排行榜
- [ ] 更多发疯主题 & 武器皮肤

## 🤝 贡献

欢迎到 https://github.com/modengsir/opc-fafeng-plaza/issues 提 Issue / PR，一起优雅发疯。

## 📄 License

[MIT](LICENSE)
