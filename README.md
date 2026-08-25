# Precision Metronome

A free, high-precision web metronome featuring sub-millisecond audio timing, arbitrary decimal BPM control (e.g. `96.05 BPM`), and high-contrast visual flash beats.

一款基于 Web Audio 引擎构建的高精度在线节拍器，支持任意小数位浮点细分调速、微秒级硬件时钟调度与全屏视觉闪烁指示。

🔗 **Live Demo / 在线体验**: [https://defei-wang.github.io/precision-metronome/](https://defei-wang.github.io/precision-metronome/)

---

## 🌟 Features / 核心特性

- **Float BPM Resolution (浮点细分调速)**: Supports arbitrary decimal tempo inputs (e.g., `96.05`, `120.37`) for film synchronization and micro-tempo practice. / 支持任意小数位速度微调，满足影视音画对轨与严格练习需求。
- **Hardware-Synced Timing (硬件级音频调度)**: Powered by `AudioContext.currentTime` with a lookahead scheduler for sub-millisecond precision. / 基于浏览器硬件音频时钟与预调度架构，确保微秒级触发精度。
- **Visual Flash Indicator (全屏视觉闪烁)**: High-contrast visual pulse synchronized with display refresh intervals, with first-beat accent color differentiation. / 高对比度全屏视觉闪烁，支持首拍重音变色高亮。
- **Procedural Synthesizer (4 种内置合成音色)**: Woodblock, Bell, Mechanical Click, and Sine Wave generated via real-time code synthesis without external audio files. / 实木打击、金属铃音、机械咔哒、标准正弦，纯代码实时合成，无需加载外部音频文件。
- **Zero Installation & Bilingual (免安装 & 双语支持)**: Runs natively in desktop and mobile browsers with instant EN/ZH UI switching. / 零依赖运行于桌面与移动端浏览器，内置一键中英文切换。

---

## 🚀 Quick Start / 本地运行

Directly visit the [Web App](https://defei-wang.github.io/precision-metronome/) or clone locally:

```bash
git clone [https://github.com/defei-wang/precision-metronome.git](https://github.com/defei-wang/precision-metronome.git)
cd precision-metronome
# Directly open index.html in any modern browser
