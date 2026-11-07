# 自在游社 · Freeplay Club — MOD HUB

按自己的节奏，玩喜欢的游戏。**Play your way.**

## ⬇ 下载 / Download

### [直接下载 Windows 绿色版 ZIP](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/download/modhub-stable/GameModHub-Windows.zip)

### [Download the portable Windows ZIP](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/download/modhub-stable/GameModHub-Windows.zip)

**当前文件：MOD HUB 0.6.1 社区预览，含四款游戏完整模块。固定地址，后续更新沿用同一链接。**

**Current package: MOD HUB 0.6.1 community preview, including four complete game modules. This download address stays the same for future approved updates.**

[版本记录 / Release notes](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/tag/v0.6.1) · [SHA-256](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/download/modhub-stable/GameModHub-Windows.zip.sha256)

<!-- dotnet-runtime-help:start -->
## 启动提示 / Startup help

如果 Windows 提示缺少 **.NET Framework 4.8**，请到[微软官方下载页](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)选择 **Runtime（运行时）**，安装并按提示重启电脑，再打开工具。无需 Developer Pack、SDK 或 Python。已安装 4.8.1 或工具已能启动时无需补装；运行库使用系统版本，没有随 ZIP 附带。补装系统组件可能需要管理员权限。

If Windows reports missing **.NET Framework 4.8**, open [Microsoft's official download page](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48), choose **Runtime**, install it and restart Windows if requested, then reopen the tool. No Developer Pack, SDK or Python is needed. An installed 4.8.1 is compatible; no reinstall is needed if the app already starts. The system runtime is not bundled in the ZIP; installing it may require administrator rights.
<!-- dotnet-runtime-help:end -->

## 中文

0.6.1 / 鬼武者1.1.0：新增子弹时间，默认H按一次减速、再按恢复；快捷键可编辑，默认25%速度，可调10–100%。自动触发实验选项默认关闭，监听敌人对主角发出的防御 / 闪避提示窗口，持续时间、冷却和距离可调。最高难度是否仍发出这类窗口及实战覆盖待玩家测试。原12项及设置保留。先正常退出游戏更新插件，再重启核验。

0.6.0新增鬼武者模块1.0.0：五种战斗窗口、伤害 / 防御 / 破防、鬼力 / 变身槽正向积累、鬼眼范围 / 持续时间，共12项独立开关、1–10倍，初次全关。需Steam Build24769601 / EXE1.0.1.0。完整模块包含匹配REFramework与控制插件，游戏关闭后在本游戏插件页安装。标题菜单核验12项全部就绪，实战待玩家测试。原三个游戏模块原包复用。

仁王模块1.3.0新增独立“红光反击窗口”，1–10倍、默认3倍（专用判定对象12→36帧）；仍需手动R。倍率和停用影响下次R，当前对象自然到期。游戏横幅收藏旁更新模块，停用功能并正常退出游戏后点“完成更新”，再重启试用。左侧只更新框架。实战效果待玩家确认。

常用功能在前台，维护进“更多”：收藏/收藏筛选、功能、连接、启动与一键更新直接可用；版本、依赖、诊断及回退保留在更多。

原有精防、精闪和三项战斗控制保留；三项战斗控制默认关闭/1倍，减伤输入3表示承受1/3。完美残心位置已只读核对，原生、跨进程和界面检查通过，实际效果由玩家试用确认。

1. 点击上面的 ZIP 下载链接，完整解压到自己选择的文件夹。
2. 运行根目录的 **GameModHub.exe**，保留 Framework、Modules、Downloads 和 UserData。
3. 在“模块管理”中安装随包提供的本地模块，再选择游戏并开启功能。无需安装 Python、Codex 或登录 GitHub。

| 游戏 | 已支持版本 | 当前功能 |
|---|---|---|
| 海洋盛宴 | Steam Build 26268989 / 26406937 | 贝里、海贼代币、桃心分别1–100倍；26406937另有训练点数、食材、道具1–10倍 |
| 仁王3 | Steam EXE 2.0.2.0 | 精准格挡、精准闪避、完美残心窗口1–10倍；另有攻击、减伤、削精控制 |
| 影之刃零 | Steam Build 26266538 / 26367565 | 五难度完美格挡窗口固定3倍 |
| 鬼武者 | Steam Build24769601 / EXE1.0.1.0 | 12项独立战斗、能量与鬼眼控制，1–10倍，初次全关 |

保留高DPI文字和控件布局修复；保留独立框架/模块设置和安全回退升级。0.5.1已撤回，现有用户可从程序内更新。

下载、设置、收藏、模块和备份默认保存在平台目录，可以整体移动，也可指定其他存储位置。框架和游戏模块独立更新；关闭框架会保留后台修改器。需要停用时使用游戏卡片、“停用全部”或相应托盘菜单。

仁王基础加载器原包不随工具转载。请从[作者页面](https://www.nexusmods.com/nioh3/mods/49?tab=files)取得已支持的v1.0.1并从插件管理导入；已有其他加载器时不要覆盖。首次安装插件后需重启游戏，文件已安装不等于实际加载。

0.3.x首次迁移到模块版需先停用并关闭游戏；已有模块版的框架更新不停止独立修改器。旧版、设置与恢复资料保留。请遵循包内使用说明和实际版本检查。

本包为社区预览：海洋盛宴资源倍率已获维护者本机实测确认；其他游戏按其说明及已验证版本使用，另一台电脑和实际体验仍需玩家反馈。游戏更新后遇到版本不符会拒绝修改。

**请下载上面的完整绿色ZIP。GitHub自动生成的 Source code 压缩包只是这个下载仓库的文档，不是程序。** 工具源码保持私有。官方运行包允许复制传播，保留随包许可和素材来源。

[Discord 中文反馈](https://discord.com/channels/1567700187412045936/1567701582840201256)（已加入成员使用） · [GitHub 问题反馈](https://github.com/Roam2026/freeplay-mod-hub-releases/issues)

## English

0.6.1 / Onimusha1.1.0 adds bullet time: H toggles slow motion at25% by default; speed and shortcut are editable. An optional experimental defensive attack-guide trigger has editable real-time duration, cooldown and range. Both options start OFF. Highest-difficulty coverage and combat behavior require player testing. The existing twelve controls and settings are retained. Exit the game before installing its new plugin, then restart.

0.6.0 adds Onimusha module1.0.0: five manual combat windows, damage/defence/stamina damage, positive Oni Power/Awakening gains, and Oni Vision range/duration. Twelve independent1–10x controls, initially OFF. Requires Steam Build24769601 / EXE1.0.1.0. The complete module includes pinned REFramework and its control plugin; exit the game before installing. All twelve locations are verified at the title menu; actual effects await player testing. Existing game archives are unchanged.

Nioh module 1.3.0 adds an independent Burst Break window (1–10x, default3x; counter collision 12 to 36 frames). Manual R input remains required. Changes/disable affect the next R; existing collisions expire naturally. Update beside Favorite, disable this game’s features and exit normally, then Finish update and restart for testing. The left action updates only the framework. Gameplay trial remains pending.

Common actions stay up front: favorites/filtering, features, connection, launch and one-click updates. More holds versions, dependencies, diagnostics and rollback.

Existing timing controls and three direct-hit controls are retained; direct-hit controls default off/x1. Reduction 3 means one-third incoming damage. Update the framework/module, then close the game before installing the matching plugin. Original hook sites are verified read-only; native/IPC/UI checks passed; gameplay still needs player testing.

Download the ZIP above, extract the complete folder, and run the root **GameModHub.exe**. Install the included cached game module from module management, select the game, then enable its features. No Python, Codex or GitHub sign-in is required. The application interface currently uses Chinese; **README.en.txt** is included.

The package supports ONE PIECE: Grand Gourmet builds 26268989 / 26406937, Nioh 3 EXE 2.0.2.0, and Phantom Blade Zero builds 26266538 / 26367565. Grand Gourmet provides six independent gain controls (the three advanced gains require build26406937), Nioh module 1.3.0 provides precision-guard/dodge, perfect-pulse and Burst Break windows plus outgoing hit damage, incoming hit-damage reduction and outgoing Ki damage, and PBZ uses the verified 3x perfect-deflect profile.

Framework and modules update independently. Closing the framework leaves independent trainers running; disable them through the game card, Disable all, or the tray menu. Settings, caches and recovery files default to the extracted folder and are retained. First migration from 0.3.x requires closing games; subsequent modular framework updates do not.

The original Nioh loader is not redistributed. Obtain supported v1.0.1 from the [author's page](https://www.nexusmods.com/nioh3/mods/49?tab=files), import it from plugin management and restart the game after first installation. Do not overwrite another loader. Unsupported game/plugin versions are refused.

This is a community preview. Grand Gourmet resource gains have maintainer player confirmation; cross-machine operation and other gameplay details still require player testing. The runnable ZIP contains no private source, saves or user settings. GitHub's automatic Source code archives contain download-repository documents, not the application. Preserve third-party notices when redistributing the runtime.

[Discord bug reports](https://discord.com/channels/1567700187412045936/1567709362745512076) (existing members) · [GitHub issues](https://github.com/Roam2026/freeplay-mod-hub-releases/issues)

## Usagi AutoClicker / 乌沙奇连点器

**Portable ZIP / 绿色版：[Download v1.2.5](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/download/autoclicker-stable/Freeplay-AutoClicker-Windows.zip)** · [Release notes / 发行说明](https://github.com/Roam2026/freeplay-mod-hub-releases/releases/tag/autoclicker-v1.2.5)

Extract the complete folder and run the root AutoClicker.exe. English by default; Simplified Chinese available. Windows 10/11 with .NET Framework 4.8. No installer, admin rights, account, Python or GameModHub required.

If startup reports missing .NET Framework 4.8, use [Microsoft's official download page](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48), choose Runtime, install it and restart Windows if requested. No Developer Pack or SDK is needed; 4.8.1 is compatible. The runtime is not bundled in the ZIP.

完整解压后运行根目录 AutoClicker.exe。默认英文，可切换中文。无需安装、管理员权限、账号或 GameModHub。

启动若提示缺少 .NET Framework 4.8，请到上述微软官方页面选择 Runtime（运行时），安装并按提示重启电脑，再打开工具。无需 SDK 或 Python；已安装 4.8.1 或已能启动时无需补装。运行库没有随 ZIP 附带，安装系统组件可能需要管理员权限。

**Updates → Update now** verifies and stages a complete package, preserves data and the previous version, and restarts idle after clicking stops. Previous version supports rollback. Startup checks can be disabled. v1.1.2 users must extract this release to a new folder and copy UserData/ and portable.json once; future upgrades work in the app. Keep the old folder for manual rollback.

**更新 → 一键升级**：校验、暂存完整包，保留设置和上一版，停止连点后以待机状态重启；支持回退。启动检查可关闭。v1.1.2 用户需手动解压本版到新目录，复制旧 UserData/ 与 portable.json 一次，以后在程序内升级。保留旧目录供手动回退。

[GitHub downloads](https://github.com/Roam2026/freeplay-mod-hub-releases) · [Discord member entrance / 成员入口](https://discord.com/channels/1567700187412045936/1567700187940392993) (new members need an invitation / 新成员需要邀请).

Only runtime packages and guides are public; source stays private. Copying and reverse engineering are allowed. 公开运行包与说明，源码保持私有；允许复制传播和逆向分析。

<!-- usagi-autoclicker:end -->
