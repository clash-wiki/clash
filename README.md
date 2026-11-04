<div align="center">
  <a href="https://github.com/clash-wiki/clash" title="Clash 中文 Wiki 索引">
<img width="150" height="150" alt="Clash" src="https://github.com/user-attachments/assets/0415cf86-7eae-49e7-a9f5-af85116967c0" />

  </a>
  <h1>Clash 中文 Wiki 索引 (2026年11月更新)</h1>
  <p>
    <b>词条、平台笔记与 Releases 读法；不镜像安装包</b>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Update-2026.11-brightgreen.svg" alt="Update">
    <img src="https://img.shields.io/badge/Platform-Win%20%7C%20Mac%20%7C%20iOS%20%7C%20Android%20%7C%20Linux-blue.svg" alt="Platform">
    <img src="https://img.shields.io/badge/Ecosystem-Clash%20%7C%20Mihomo%20%7C%20Sing--box%20%7C%20Xray-orange.svg" alt="Ecosystem">
  </p>
</div>


**目录锚点：** [阅读顺序](#0-阅读顺序) · [词条](#1-词条生态与名词) · [资源目录](#2-资源目录按角色) · [平台笔记](#3-平台速查笔记) · [Releases](#4-如何读-github-releases) · [相关](#5-相关入口) · [FAQ](#6-faq) · [边界](#7-边界与免责)

---

### 0. 阅读顺序

本页是 **Clash 中文 Wiki 索引** 的 Wiki 索引：按「词条 → 目录 → 平台笔记 → Releases 读法」定位官方仓库，**不镜像安装包、不代发订阅、不写逐步安装长教程**。

建议路径：① 扫 [词条](#1-词条生态与名词) → ② 进 [资源目录](#2-资源目录按角色) 点到各项目 **GitHub Releases** → ③ 看 [平台速查笔记](#3-平台速查笔记) → ④ 下包前读 [如何读 GitHub Releases](#4-如何读-github-releases) → ⑤ 热度对照用 [代理雷达](https://github.com/guiforcores/dailileida)。

若本索引有用，欢迎点右上角 **Star** ⭐。

[节点雷达](https://jiedianleida.com/)：Wiki 旁证入口——免费 Clash / V2Ray / SS / Trojan 节点按日测速归档，选订阅前可对照延迟与可用性。

---

### 1. 词条：生态与名词

<details>
<summary><b>Clash</b></summary>

口语里常把「能导入 Clash 风格配置」的客户端统称为 Clash。历史上有多个近名项目；选型以**具体 GitHub 组织 / 仓库**与近期 Releases 为准，不要只看口号标题。
</details>

<details>
<summary><b>Mihomo（常被称作 Clash Meta 系内核）</b></summary>

原 Clash 核心停更后，许多仍在维护的 GUI 改用 Mihomo 等兼容内核。字段大体相近，细节以所选客户端文档为准；本目录里多数活跃项目走这一路线。
</details>

<details>
<summary><b>Sing-box / Xray</b></summary>

同属代理生态的其他内核栈，配置模型与 Clash YAML **并不总是一一对应**。跨栈热度可对照 [代理雷达](https://github.com/guiforcores/dailileida)（开源看 GitHub Star，商店应用看美区 App Store / Google Play 评分数）。
</details>

<details>
<summary><b>订阅 / Profile / 规则</b></summary>

由你自行准备；本 Wiki **不托管、不生成**节点。导入与分流见对应客户端 README / Issues。GUI 负责订阅与系统代理 / TUN；本页主要索引带界面的客户端 Releases。
</details>

---

### 2. 资源目录（按角色）

链接一律指向官方 **GitHub Releases**（或归档备份仓）。按「角色」分栏便于 Wiki 查阅，**不是**「某平台唯一推荐」榜单。

#### 2.1 桌面 GUI（Windows / macOS / Linux）

| 词条 | Releases | 备注（索引级） |
|:-----|:---------|:---------------|
| Clash Verge Rev | [releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) | 常见桌面维护分支之一 |
| Clash Party | [releases](https://github.com/mihomo-party-org/clash-party/releases) | Mihomo Party 系桌面客户端 |
| ClashX Meta | [releases](https://github.com/MetaCubeX/ClashX.Meta/releases) | macOS 向 Meta 系客户端 |
| FlClash | [releases](https://github.com/chen08209/FlClash/releases) | 桌面 + Android 等多端 |
| Clash Nyanpasu | [releases](https://github.com/LibNyanpasu/clash-nyanpasu/releases) | 桌面 GUI |
| Sparkle | [releases](https://github.com/xishang0128/sparkle/releases) | 桌面补充项 |
| Bettbox | [releases](https://github.com/appshubcc/Bettbox/releases) | 桌面补充项 |

#### 2.2 移动端（Android / iOS）

| 词条 | Releases | 备注（索引级） |
|:-----|:---------|:---------------|
| Clash Meta for Android | [releases](https://github.com/MetaCubeX/ClashMetaForAndroid/releases) | Android 常见维护项；原 Clash for Android 已停更 |
| ClashBox | [releases](https://github.com/xiaobaigroup/ClashBox/releases) | Android 补充项 |
| Clash Mi | [releases](https://github.com/KaringX/clashmi/releases) | 含移动端；iOS 渠道以官方说明为准 |
| FlClash | [releases](https://github.com/chen08209/FlClash/releases) | 含 Android |
| Hiddify | [releases](https://github.com/hiddify/hiddify-app/releases) | 跨栈多端；配置模型可能与纯 Clash YAML 不同 |

> **多端对照：** 同一订阅少换工具时，可并行查阅 [Clash Mi](https://github.com/KaringX/clashmi/releases)、[Hiddify](https://github.com/hiddify/hiddify-app/releases)、[FlClash](https://github.com/chen08209/FlClash/releases)（后两者配置模型可能与纯 Clash YAML 不同）。

#### 2.3 归档与停更对照（仅历史查阅，不建议日常主用）

| 词条 | 备份 / 原仓库 | 说明 |
|:-----|:--------------|:-----|
| Clash for Windows | [clash-latest/Clash-for-Windows](https://github.com/clash-latest/Clash-for-Windows) | 经典 Windows GUI，已停更 |
| ClashX | [clash-latest/ClashX](https://github.com/clash-latest/ClashX) | 经典 macOS GUI，已停更 |
| Clash for Android | [clash-latest/Clash-for-Android](https://github.com/clash-latest/Clash-for-Android) | 经典 Android 客户端，已停更 |
| Clash Verge（原版） | [zzzgydi/clash-verge releases](https://github.com/zzzgydi/clash-verge/releases) | 原 Verge；日常请改看 Verge Rev |
| ClashN | [2dust/clashN releases](https://github.com/2dust/clashN/releases) | 归档对照 |

> OpenWRT / 软路由不单列二进制；请查固件插件源或 mihomo 相关文档，并与桌面配置分开管理。

---

### 3. 平台速查笔记

只回答「去目录哪一栏查」，**不替代**各仓库安装说明。

- **Windows**：查 [2.1](#21-桌面-guiwindows--macos--linux)；核对 x64/arm64 与安装包后缀。SmartScreen 提示时回 Release 页校验。  
- **macOS**：对照 [ClashX Meta](https://github.com/MetaCubeX/ClashX.Meta/releases) 与跨平台桌面项；被拦截时走「隐私与安全性」；按 Apple Silicon / Intel 选构建。  
- **Linux**：按 Release 内 AppImage/deb/rpm 说明；TUN/权限问题搜对应 Issues。  
- **Android**：维护向见 [Clash Meta for Android](https://github.com/MetaCubeX/ClashMetaForAndroid/releases)；勿与已停更备份仓混淆。  
- **iOS**：以 [Clash Mi](https://github.com/KaringX/clashmi/releases)、[Hiddify](https://github.com/hiddify/hiddify-app/releases) 官方说明/商店为准；不索引不明 IPA。  
- **OpenWRT**：见 2.3；与手机/电脑配置分开备份。

---

### 4. 如何读 GitHub Releases

1. 打开上表 `…/releases`，确认 **组织名与仓库名** 与本 Wiki 一致。  
2. 优先 **Latest** 正式版；除非清楚风险，否则慎用 pre-release。  
3. 在 Assets 中按操作系统与 CPU 架构挑选，勿下错平台包。  
4. 若正文提供校验和（SHA 等），下载后自行核对再安装。  
5. 本仓库 **不提供** 安装包附件镜像——版本迭代快，附件易过期。

---

### 5. 相关入口

| 入口 | 用途 |
|:-----|:-----|
| [本仓库 clash-wiki/clash](https://github.com/clash-wiki/clash) | 本 Wiki 索引与月份维护标记 |
| [代理雷达 guiforcores/dailileida](https://github.com/guiforcores/dailileida) | 按 GitHub Star / 美区 App Store / Google Play 评分追踪 mihomo、sing-box、Xray、V2Ray、Clash 及自研内核相关客户端热度 |
| [clash-latest/ClashNode](https://github.com/clash-latest/ClashNode) | 节点相关整理的兄弟索引（本 Wiki 不托管订阅） |

日期徽章（`YYYY年M月更新` / `Update-YYYY.MM`）表示**本页维护月份**，不等于某一客户端发版日。

---

### 6. FAQ

<details>
<summary><b>Q：本页和「下载站长文」有什么区别？</b></summary>

A：Wiki **索引**：按词条与角色导航官方 Releases，并补充读包方法与平台笔记；不做安装长文或机场矩阵。
</details>

<details>
<summary><b>Q：为什么同一客户端会出现在多个小节？</b></summary>

A：如 FlClash、Clash Mi 同时具备桌面与移动属性。目录按「你怎么查」重复挂链，避免只进一栏就漏掉。
</details>

<details>
<summary><b>Q：Clash、Mihomo、Clash Meta 是不是同一个东西？</b></summary>

A：不是同一产品。社区习惯把兼容原 Clash 配置、改用 Mihomo 等内核的客户端仍叫「Clash」。以具体仓库 README 的内核说明为准。
</details>

<details>
<summary><b>Q：可不可以只下停更备份仓？</b></summary>

A：可查阅，但**不建议**日常主用；请改用 2.1 / 2.2 中仍有更新的项目。
</details>

<details>
<summary><b>Q：标题里的月份和绿色 Update 徽章谁维护？</b></summary>

A：由例行任务自动改写 `YYYY年M月更新` 与 `Update-YYYY.MM`。人工改文案时请保留这两种格式，以免自动化失效。
</details>

<details>
<summary><b>Q：找不到适合 OpenWRT 的包怎么办？</b></summary>

A：本索引以桌面 / 移动 GUI 为主。软路由请查对应固件插件源或 mihomo 相关项目文档，并单独管理配置。
</details>

---

### 7. 边界与免责

1. **只做索引与名词整理**：不提供绕过审查、侵犯版权或从事违法活动的服务或操作指南。  
2. **不替代官方文档**：安装失败、TUN、规则、订阅等问题请到对应 GitHub 的 Issues / README。  
3. **合法使用**：请遵守当地法律法规与服务条款；使用第三方客户端、订阅或节点的风险由使用者自行承担。  
4. **链接时效**：若 Releases 404，以 GitHub 上该组织当前页面为准。标题/徽章月份仅表示本 Wiki 维护周期。

---

<sub>Clash 中文 Wiki 索引 · Wiki 索引 · 2026年11月更新 · 不镜像安装包</sub>
