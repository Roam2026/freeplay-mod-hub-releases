# 自在游社 · Freeplay Club — MOD HUB

**按自己的节奏，玩喜欢的游戏。Play your way.**

[下载 / Downloads](https://github.com/Roam2026/freeplay-mod-hub-releases/releases) · [v0.2.1 社区预览 / Community Preview](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/tag/v0.2.1)

本仓库只提供程序发行包及说明。工具源码保存在独立私有仓库中。
This repository contains public releases and documentation only. The application source is maintained separately in a private repository.

## 中文

MOD HUB 是 Windows 便携游戏修改工具箱，当前为社区预览版 0.2.1。

| 游戏 | 支持版本 | 功能 |
| --- | --- | --- |
| 海洋盛宴 | Steam Build 26268989 | 贝里、海贼代币、桃心分别 1–100 倍 |
| 仁王3 | Steam EXE 2.0.2.0 | 精准格挡、精准闪避窗口分别 1–10 倍 |
| 影之刃零 | Steam Builds 26266538 / 26367565 | 五难度完美格挡窗口固定 3 倍 |

### 下载与运行

1. 打开发行页，下载 `GameModHub-v0.2.1-Windows.zip`。
2. 完整解压后运行 `GameModHub.exe`；保留 `Modules` 文件夹。
3. 阅读包内 `使用说明.txt`。无需安装 Python 或 Codex。
4. GitHub 自动生成的 `Source code` 压缩包仅包含本下载仓库的文档，不是可运行程序，也不包含工具私有源码。

仁王3需要另外安装作者提供的 [DLL Plugin Loader v1.0.1](https://www.nexusmods.com/nioh3/mods/49?tab=files)。退出游戏后将作者包中的 `dinput8.dll` 放到 `Nioh3.exe` 同目录；已有文件时先核对来源，避免覆盖其他加载器。MOD HUB 会核对支持的文件哈希，不匹配时拒绝安装。加载器不随本包转载，下载可能需要 Nexus Mods 账号。

### 更新与回退

先停用全部功能，关闭工具与游戏，将新版完整解压到新的文件夹后启动。设置和恢复备份保存在 `%LOCALAPPDATA%\GameModHub`，保留此目录。先保留旧版工具文件夹，需要回退时关闭新版并运行旧版。不要只替换 EXE；`Modules` 也需要随版本更新。当前为手动下载更新，没有自动更新服务。

### 预览限制

- 当前工具界面为中文，包内另有英文使用说明。
- 只支持上表版本；游戏更新后可能需要重新适配，不匹配时拒绝修改。
- 影之刃零 26367565 已通过只读定位与属性核对，整合控制和实际战斗效果仍待玩家测试。
- 已做本机离线检查、发行包校验和解压运行检查；尚无另一台电脑的验证，实际游戏体验由玩家反馈。
- 本包不含个人存档、设置、日志、游戏文件或源码。

### 传播、来源与反馈

官方程序包允许下载、使用、复制和传播。第三方组件仍遵循其各自许可，分发时保留包内许可文件。游戏展示素材归相应权利人所有，来源见 `AssetSources.json`。

已有成员可进入 [Discord 中文反馈](https://discord.com/channels/1567700187412045936/1567701582840201256)。频道地址不是新成员邀请链接。也可在本仓库 Issues 提交问题；请写明工具版本、游戏版本和复现步骤，不要上传密码、恢复码、存档或含个人信息的完整日志。

## English

MOD HUB 0.2.1 is a portable Windows game-modding toolbox and a community preview.

| Game | Supported version | Features |
| --- | --- | --- |
| ONE PIECE: Grand Gourmet | Steam Build 26268989 | Berries, Pirate Tokens and Hearts: 1–100x each |
| Nioh 3 | Steam EXE 2.0.2.0 | Precision guard and dodge windows: 1–10x each |
| Phantom Blade Zero | Steam Builds 26266538 / 26367565 | Fixed 3x perfect-deflect windows across five difficulties |

### Download and run

1. Open Releases and download `GameModHub-v0.2.1-Windows.zip`.
2. Extract the complete archive and run `GameModHub.exe`. Keep the `Modules` folder.
3. Read `README.en.txt`; neither Python nor Codex is required. The application UI currently uses Chinese.
4. GitHub's automatic `Source code` archives contain this download repository's documents, not the runnable application or its private source.

Nioh 3 requires the author's [DLL Plugin Loader v1.0.1](https://www.nexusmods.com/nioh3/mods/49?tab=files), downloaded separately. With the game closed, place its `dinput8.dll` beside `Nioh3.exe`. Check any existing loader before replacing it. MOD HUB verifies the supported hash and refuses mismatches. The loader is not redistributed here; Nexus Mods may require an account to download it.

### Updates, rollback and preview limits

Disable all features and close MOD HUB and the games before updating. Extract the complete new package into a new folder. Keep `%LOCALAPPDATA%\GameModHub` for settings and recovery backups, and retain the old application folder for rollback. Update the entire package, including `Modules`, rather than just the EXE. Updates are manual; there is no automatic updater.

Only the listed game versions are supported. Phantom Blade Zero Build 26367565 has read-only location/property validation; its integrated controls and combat behavior still need player testing. Local offline, package-integrity and extracted-package execution checks have been performed; a second computer has not been verified. The package contains no personal saves, settings, logs, game files or application source.

The official binary package may be downloaded, used, copied and redistributed. Preserve the bundled third-party license notices. Game artwork belongs to its respective rights holders; see `AssetSources.json`.

Existing members can use [Discord bug reports](https://discord.com/channels/1567700187412045936/1567709362745512076); this is a channel link, not an invitation. Reports are also welcome in this repository's Issues. Include the tool/game versions and reproduction steps; do not post credentials, recovery codes, saves or unredacted personal logs.

<!-- usagi-autoclicker:start -->
<a id="usagi-autoclicker"></a>

## Usagi AutoClicker / 乌沙奇连点器

**Portable ZIP / 绿色版：[Download v1.2.0](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/download/autoclicker-v1.2.0/Freeplay-AutoClicker-v1.2.0-Windows.zip)** · [Release notes / 发行说明](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/tag/autoclicker-v1.2.0)

Extract the complete folder and run the root AutoClicker.exe. English by default; Simplified Chinese available. Windows 10/11 with .NET Framework 4.8. No installer, admin rights, account, Python or GameModHub required.

完整解压后运行根目录 AutoClicker.exe。默认英文，可切换中文。无需安装、管理员权限、账号或 GameModHub。

**Updates → Update now** verifies and stages a complete package, preserves data and the previous version, and restarts idle after clicking stops. Previous version supports rollback. Startup checks can be disabled. v1.1.2 users must extract this release to a new folder and copy UserData/ and portable.json once; future upgrades work in the app. Keep the old folder for manual rollback.

**更新 → 一键升级**：校验、暂存完整包，保留设置和上一版，停止连点后以待机状态重启；支持回退。启动检查可关闭。v1.1.2 用户需手动解压本版到新目录，复制旧 UserData/ 与 portable.json 一次，以后在程序内升级。保留旧目录供手动回退。

[GitHub downloads](https://github.com/Roam2026/freeplay-mod-hub-releases) · [Discord member entrance / 成员入口](https://discord.com/channels/1567700187412045936/1567700187940392993) (new members need an invitation / 新成员需要邀请).

Only runtime packages and guides are public; source stays private. Copying and reverse engineering are allowed. 公开运行包与说明，源码保持私有；允许复制传播和逆向分析。

<!-- usagi-autoclicker:end -->
