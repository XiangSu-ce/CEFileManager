<div align="center">
  <img src="docs/readme-assets/app-icon.png" alt="CEFileManager Icon" width="120" />
  <h1>CEFileManager</h1>
  <p><strong>Run Codex, Claude-style CLI workflows, file operations, APK editing, and mobile reverse engineering in one Android app.</strong></p>
  <p><strong>在一个 Android App 里直接跑 Codex、Claude 风格 CLI、文件工程、APK 编辑与移动端逆向工作流。</strong></p>
  <p>
    <code>Android</code>
    <code>Kotlin</code>
    <code>Jetpack Compose</code>
    <code>CLI on Phone</code>
    <code>APK / XML / DEX</code>
    <code>Root / Shizuku / SAF</code>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Android-Mobile%20Workstation-101418?style=for-the-badge&logo=android&logoColor=3DDC84" alt="Android Mobile Workstation" />
    <img src="https://img.shields.io/badge/AI%20CLI-Codex%20%7C%20Claude%20%7C%20More-101418?style=for-the-badge&logo=gnubash&logoColor=58D4FF" alt="AI CLI" />
    <img src="https://img.shields.io/badge/APK%20Lab-Edit%20%7C%20Sign%20%7C%20Export-101418?style=for-the-badge&logo=androidstudio&logoColor=8BC2FF" alt="APK Lab" />
  </p>
  <p>
    <img src="https://img.shields.io/badge/Storage-Root%20%7C%20Shizuku%20%7C%20SAF-101418?style=for-the-badge&logo=files&logoColor=19D3A2" alt="Storage Access" />
    <img src="https://img.shields.io/badge/Editors-Text%20%7C%20XML%20%7C%20Hex-101418?style=for-the-badge&logo=visualstudiocode&logoColor=82AAFF" alt="Editors" />
    <img src="https://img.shields.io/badge/Reverse-APK%20%7C%20DEX%20%7C%20SO-101418?style=for-the-badge&logo=hackthebox&logoColor=9FEF00" alt="Reverse Engineering" />
  </p>
  <p>
    <a href="#download">
      <img src="https://img.shields.io/badge/Download-%E4%B8%8B%E8%BD%BD%E4%BD%93%E9%AA%8C-14B88A?style=for-the-badge&logo=android&logoColor=ffffff" alt="Download" />
    </a>
    <a href="https://github.com/XiangSu-ce/CEFileManager">
      <img src="https://img.shields.io/badge/GitHub-%E5%85%AC%E5%BC%80%E4%BB%93%E5%BA%93-111827?style=for-the-badge&logo=github&logoColor=ffffff" alt="GitHub Repository" />
    </a>
    <a href="#screenshots">
      <img src="https://img.shields.io/badge/Screenshots-%E5%AE%9E%E6%9C%BA%E6%88%AA%E5%9B%BE-1D4ED8?style=for-the-badge&logo=googlephotos&logoColor=ffffff" alt="Screenshots" />
    </a>
    <a href="#readme-images">
      <img src="https://img.shields.io/badge/README%20Guide-%E5%9B%BE%E7%89%87%E4%B8%8A%E4%BC%A0%E6%95%99%E7%A8%8B-7C3AED?style=for-the-badge&logo=github&logoColor=ffffff" alt="README Guide" />
    </a>
  </p>
</div>

<p align="center">
  <img src="docs/readme-assets/hero-banner.svg" alt="CEFileManager Hero Banner" width="100%" />
</p>

<p align="center">
  <strong>Phone in hand. Terminal online. APK open. Files under control.</strong><br />
  <strong>手机在手，终端在线，APK 可改，文件可控。</strong>
</p>

> **CEFileManager** is for users who are tired of pretending mobile means lightweight.
>
> **CEFileManager** 面向的是不想再把“手机端”当成“阉割版工作流”的用户。

## Quick Pitch | 一句话卖点

`CEFileManager turns Android into a real mobile engineering workstation.`

`CEFileManager 让 Android 手机直接变成真正能干活的移动工程工作站。`

## Why People Notice It | 为什么它会让人眼前一亮

- You are not switching between five apps just to edit one package or move one file.
- You can show real phone-side CLI capability instead of empty marketing talk.
- Your screenshots already prove the product can run Codex and Claude-style terminal flows on-device.
- The same app covers storage operations, editing, package work, and terminal execution.
- This is exactly the kind of positioning that stands out on GitHub, Telegram, QQ groups, and Android modding communities.

## CN | 这不是普通文件管理器

**CEFileManager** 的目标不是做一个“能看文件”的工具，而是把你在桌面端想做的那套事情，尽可能搬到手机上。

你可以在同一个 App 里完成这些事：

- 跑终端，直接把手机当成移动 CLI 工作站
- 接入 `Codex`、`Claude` 等 AI CLI 工作流
- 浏览、复制、编辑、替换、导出普通文件与受限目录文件
- 处理 `APK`、`XML`、`DEX`、`SO`、`HEX`、压缩包等高频逆向对象
- 做签名、重打包、查看结构、快速改资源、改文本、改配置
- 在 Root、Shizuku、SAF、多存储路径之间切换工作流
- 用文本编辑器、XML 编辑器、终端、预览器在同一套界面里连续作业

它更像一个放进手机里的移动工程台，而不是一个只会复制粘贴的文件浏览器。

## EN | Not just a file manager

**CEFileManager** is built for people who want desktop-grade workflows on Android, not just basic file browsing.

Inside one app, you can:

- run a real terminal workflow on your phone
- connect `Codex`, `Claude`, and other AI-assisted CLI flows
- browse, copy, edit, replace, and export files across normal and restricted paths
- work with `APK`, `XML`, `DEX`, `SO`, `HEX`, and archive-heavy reverse-engineering targets
- sign, rebuild, inspect, patch, and modify app packages without jumping between tools
- switch across Root, Shizuku, SAF, and internal storage workflows
- move between the text editor, XML editor, terminal, viewers, and tooling in one place

This is closer to a mobile engineering workstation than a traditional Android file manager.

## Why It Hits Different | 为什么它更狠

- **Mobile CLI cockpit**: not a toy terminal, but a phone-side workspace for AI CLI usage, command execution, and file operations.
- **Reverse engineering ready**: APK signing, archive editing, XML work, binary viewing, and app package workflows are first-class features.
- **One-device workflow**: inspect, edit, patch, save, test, and export on the same device.
- **Real storage access paths**: designed around internal storage, SAF, Shizuku, Root, and restricted-directory realities.
- **Built for power users**: useful for Android modding, package analysis, scripting, debugging, and field operations.

## Feature Highlights | 核心卖点

| Module | What you can do |
| --- | --- |
| Terminal | Run shell commands, manage sessions, handle long outputs, and use mobile CLI workflows |
| AI CLI | Connect Codex / Claude style workflows inside the app workspace |
| File Manager | Browse, move, copy, replace, compare, preview, and batch process files |
| Editors | Text editing, XML editing, syntax highlight, structured editing, and search |
| APK Lab | Open APK internals, inspect assets, edit contents, repack, and sign |
| Binary Tools | Hex viewing, hash checks, archive handling, and reverse-oriented utilities |
| Access Layers | SAF, app-private, shared storage, Root, and Shizuku-assisted operations |

<a id="screenshots"></a>

## Screenshots | 实机截图

下面这组已经是你的真实截图，不是占位图。

<p align="center">
  <img src="docs/readme-assets/screenshots/quick-connect-mobile.jpg" alt="Quick Connect Mobile" width="32%" />
  <img src="docs/readme-assets/screenshots/claude-terminal-mobile.jpg" alt="Claude Terminal Mobile" width="32%" />
  <img src="docs/readme-assets/screenshots/codex-terminal-mobile.jpg" alt="Codex Terminal Mobile" width="32%" />
</p>

<p align="center">
  <sub>Quick Connect</sub> · <sub>Claude Code on Phone</sub> · <sub>Codex on Phone</sub>
</p>

### What these screenshots already sell | 这三张图本身已经在卖什么

- `Quick Connect`: 直接证明你不是“PPT 接入”，而是真有 AI CLI 接入入口和服务线路结构
- `Claude on Phone`: 直接证明手机端不是摆设，是真终端、真会话、真执行环境
- `Codex on Phone`: 直接证明这是能拿来跑实际工作流的移动 CLI 工作站

## Use Cases | 适合谁

- Android 高级玩家，需要在手机上直接处理文件、包体、签名、配置和终端任务
- 逆向与修改用户，需要快速打开 APK、改 XML、替换资源、导出结果
- AI CLI 重度用户，希望在手机端继续跑 Codex、Claude 类工作流
- Root / Shizuku 用户，希望统一处理受限目录、内部存储和工具链
- 需要外出作业的人，希望只带手机也能继续工作

## Capability Matrix | 能力矩阵

| You need | CEFileManager gives you |
| --- | --- |
| Mobile terminal work | Embedded terminal, session workflow, on-phone command execution |
| AI-assisted CLI usage | Codex / Claude-style CLI integration entry and mobile operation flow |
| File engineering | Copy, move, replace, preview, compare, export, and batch operations |
| Package modification | APK internal browsing, editing, repacking, signing, and output |
| Config editing | Text editor, XML editor, structured search, and save workflow |
| Harder storage paths | Root, Shizuku, SAF, internal storage, and restricted-path handling |

<a id="download"></a>

## Download | 下载

这里已经换成真实入口，可以直接当发布区使用。

- `Direct APK Download`: `https://daw111.asia/CEFileManager.apk`
- `GitHub Repository`: `https://github.com/XiangSu-ce/CEFileManager`
- `GitHub Issues`: `https://github.com/XiangSu-ce/CEFileManager/issues`
- `Git Clone`: `https://github.com/XiangSu-ce/CEFileManager.git`
- `Discussion / Group / Channel`: 如果你后面有 QQ 群、TG 频道、官网介绍页，可以继续补到这里

### Suggested CTA copy | 推荐按钮文案

- `Download Latest APK | 下载最新版 APK`
- `View Screenshots | 查看实机截图`
- `See Mobile Codex Workflow | 看手机端 Codex 工作流`
- `Join Community | 加入交流群`

### Recommended real screenshots | 推荐你补的真实截图

- `Terminal + AI CLI`: 展示手机上直接跑 `Codex` / `Claude` / CLI 的页面
- `Text/XML Editor`: 展示补全、搜索、编辑、保存的界面
- `APK Workspace`: 展示 APK 内目录、资源、签名、替换、导出的流程页
- `File Operations`: 展示复制、移动、受限目录、内部存储之间操作
- `Dark + Dense UI`: 尽量选信息量大的图，不要只放空白页面

<a id="readme-images"></a>

## How To Upload Images To GitHub README | 如何把图片传上去并显示

### Method A: best practice

把图片直接放进仓库，例如：

```text
docs/readme-assets/
  hero-banner.svg
  screenshots/
    terminal-main.png
    editor-xml.png
    apk-workspace.png
```

然后在 `README.md` 里这样写：

```md
![Terminal Screenshot](docs/readme-assets/screenshots/terminal-main.png)
```

如果你要控制尺寸，GitHub README 里可以直接用 HTML：

```html
<p align="center">
  <img src="docs/readme-assets/screenshots/terminal-main.png" width="31%" />
  <img src="docs/readme-assets/screenshots/editor-xml.png" width="31%" />
  <img src="docs/readme-assets/screenshots/apk-workspace.png" width="31%" />
</p>
```

### Method B: drag and drop

你也可以在 GitHub 的 issue、discussion、README 在线编辑器里直接拖图片进去，GitHub 会给一个托管链接。

优点：

- 快
- 不需要先建目录

缺点：

- 图不在仓库里，不方便后续整理
- 换图和版本控制不如仓库内资源清晰

所以首页宣传图建议还是直接提交到仓库。

### Recommended image spec | 推荐图片规格

- 首页横幅：`1600 x 720` 左右
- 截图卡片：`1080 x 2400` 手机长图裁切后使用
- 单张展示宽度：`30%` 到 `32%`
- 文件格式：截图用 `png`，横幅或说明图用 `svg`
- 内容上优先放“终端 + 编辑器 + APK 工具”这三类图

## Copywriting You Can Reuse | 可直接复用的宣传文案

### Short version

`CEFileManager: Turn your Android phone into a real CLI + APK + file engineering workstation.`

`CEFileManager：把你的 Android 手机，直接变成真正可干活的 CLI + APK + 文件工程工作站。`

### Ad version

`Run terminal workflows, AI CLI tools, APK editing, XML patching, and deep file operations on one Android device. CEFileManager is built for users who are done pretending a phone is only for lightweight tasks.`

`在一台 Android 手机上完成终端工作流、AI CLI、APK 编辑、XML 修改和深度文件操作。CEFileManager 面向的不是“随便看看文件”的用户，而是想让手机真正干活的人。`

### Harder ad version

`Your phone is no longer just a viewer. With CEFileManager, it becomes a command-line workstation, APK editing bench, AI CLI cockpit, and file-operation control center that actually ships work.`

`你的手机不该只是查看器。CEFileManager 让它直接变成命令行工作站、APK 编辑台、AI CLI 驾驶舱和真正能交付结果的文件工程控制中心。`

### Community post version

`CEFileManager lets you run terminal workflows, connect Codex / Claude-style CLI flows, edit APK internals, and handle deep file operations on Android. If you want a phone that can actually work, not just consume content, start here.`

`CEFileManager 可以在 Android 上直接跑终端工作流、接入 Codex / Claude 风格 CLI、编辑 APK 内部文件并处理深度文件操作。如果你要的是一台真正能干活的手机，而不是只会消费内容的设备，就从这里开始。`

## Suggested GitHub Top Section Order | GitHub 首页建议排版顺序

1. Icon + title + one-line slogan
2. Hero banner
3. One short CN block + one short EN block
4. Three screenshots in one row
5. Core features
6. Download / release / group / discussion links

## Next Step For You | 你下一步要做什么

1. 先把这个 `README.md` 推上去，首页会立刻成型。
2. 再把你最能打的 3 到 5 张截图丢进 `docs/readme-assets/screenshots/`。
3. 把 README 里的占位图路径换成真实截图。
4. 最后补上下载链接、群链接、频道链接、版本更新入口。

如果你愿意，我下一步可以继续直接帮你补第二版：

- 更像商业项目首页的 GitHub README 排版
- 带徽章、下载按钮、特性卡片
- 带“移动端跑 Codex / Claude”风格的更强广告文案
