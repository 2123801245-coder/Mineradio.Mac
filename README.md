# Mineradio · macOS 构建归档

> ⚠️ **这不是本人开发的项目。** 本仓库仅归档 **Mineradio** 的 macOS 构建包，原作者为 **Mineradio**。
> 归档版本：`1.2.0`（压缩包内 `package.json` 标记为 `1.1.0`）

## 关于 Mineradio

Mineradio 是一款**沉浸式音乐播放器**：把天气电台、搜索播放、歌词舞台、粒子视觉与 3D 歌单架组合成一个更接近现场感的私人音乐空间。

核心特性（原项目自述）：

- Open-Meteo **天气电台**：按位置、城市与天气 mood 生成播放队列
- 首页含天气电台、每日推荐、私人电台、继续听、听歌画像与我的歌单入口
- Wallpaper 银河首页背景，未播放时保持干净的星河氛围
- 播放后切换到歌词舞台与粒子舞台同步工作
- **3D 歌单架**（three.js）

## 归档内容

```
Mineradio-1.2.0/
├── desktop/          Electron 主进程（main.js / preload.js / overlay-preload.js）
├── dj-analyzer.js    音频分析
├── public/           前端页面与资源（index.html、three.js、gsap、music-tempo）
├── package.json
├── LICENSE           GNU GPL v3
└── SECURITY.md
```

## 安装

1. 下载本仓库的 [`Mineradio-1.2.0-with-mac-build_1.zip`](./Mineradio-1.2.0-with-mac-build_1.zip)
2. 解压，按包内说明安装

> **安全提示（原项目公告）**：`v1.0.10` 及更早的旧安装包不建议继续安装或传播，请视为不可信历史产物隔离保留。请使用 `v1.1.0` 或更新版本。

## 许可证与署名

原项目以 **GNU General Public License v3.0** 发布，许可证全文见压缩包内 `LICENSE`。

GPL-3.0 允许再分发，但要求：

- 保留版权声明与许可证全文（本归档**原样保留**，未做修改）
- 若对代码做了修改，必须注明修改内容与日期
- 不得附加额外限制

**本归档未对原始代码做任何修改。** 若你发现此处与本说明不符，请提 Issue 更正。

原作者项目主页与其官方 Release 请以 Mineradio 官方渠道为准；本仓库仅为个人备份归档，不代表原作者。

---

个人作品集（本人实际项目）：<https://2123801245-coder.github.io/>
