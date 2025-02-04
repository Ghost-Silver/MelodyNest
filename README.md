# MelodyNest 🎵

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

一个开源的跨平台音乐播放器，灵感来自QQ音乐，致力于提供简洁优雅的听歌体验。

![界面预览](docs/screenshot-preview.png)  
*(注：截图需后续补充)*

## 特性

### 已实现功能
- 🎧 基础音频播放（MP3/WAV/FLAC）
- 📂 本地音乐文件拖拽导入
- ⏯️ 播放/暂停/进度控制
- 🎚️ 音量调节

### 开发中功能
- 🎨 QQ音乐风格UI复刻
- 📜 歌词同步显示
- 🌓 暗黑/明亮主题切换

## 技术栈
- **前端框架**: Electron + React
- **音频引擎**: Howler.js
- **UI组件库**: Ant Design
- **构建工具**: Webpack
- **包管理**: npm

## 快速开始

### 环境要求
- Node.js ≥ 18.x
- npm ≥ 9.x

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/你的用户名/MelodyNest.git

# 安装依赖
cd MelodyNest
npm install

# 启动开发模式
npm run start

构建可执行文件
npm run build

# 输出至 /dist 目录

项目结构
MelodyNest/
├── src/                # 源码
│   ├── main/           # Electron主进程代码
│   ├── renderer/       # 前端界面代码
│   └── preload/        # 进程通信脚本
├── public/             # 静态资源
├── docs/               # 文档与截图
└── package.json

如何贡献
欢迎通过以下方式参与：

提交 Issue 报告问题或建议
Fork 仓库并提交 Pull Request
完善文档或翻译
代码规范
分支命名: feat/xxx / fix/xxx
提交信息遵循 Conventional Commits
使用 ESLint + Prettier 保持代码风格统一
开源协议
MIT License

让音乐自由流动！ 🎶
开发者交流邮箱：cyf31415@yeah.net
