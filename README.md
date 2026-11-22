# Tick Lock PvP

冻结世界，在快捷栏上方的时间轴逐 tick 编排移动、视角、攻击和物品使用；全员确认后，服务器同步执行本回合。适合多人 PvP 录像，也可以单人练习。

## 下载与安装

**[下载 Tick Lock PvP 0.9.0（JAR）](https://github.com/haihuangz/tick-lock-pvp/releases/download/v0.9.0/tick-lock-pvp-0.9.0.jar)** · [版本说明](https://github.com/haihuangz/tick-lock-pvp/releases/tag/v0.9.0)

需要 Minecraft Java 版 **26.2**、**Fabric Loader 0.19.3 或以上**、**Java 25 或以上**，以及适配 26.2 的 **[Fabric API](https://modrinth.com/mod/fabric-api)**。把模组 JAR 和 Fabric API 放进 `mods` 文件夹。联机时，服务端和所有参战客户端都要装同一版本的模组。ReplayMod 是可选的客户端录制工具，不装也能玩。

请下载 `.jar`，不要下载 GitHub 自动生成的 `Source code` 压缩包；压缩包只包含下载说明和许可证。

## 怎么玩

- 单人进存档按 **F7** 开始；多人由房主或管理员运行 `/ticklock start`。
- 按 **F8** 切换到输入模式，用原版键鼠编辑当前格；**左右方向键**选格，按住 **Shift** 一次跳五格。
- 按 **Enter** 提交本轮计划，全员提交后再按一次确认。空白格没有输入，提前排好的后续动作会保留。
- 默认每回合执行 5 tick，`/ticklock ticks 20` 可改为 20 tick，范围 1–100。
- 回合限时默认关闭。`/ticklock timer on` 开启每轮 60 秒限时，`/ticklock timer off` 关闭。到点后，未提交的玩家会采用服务器收到的最新草案，全员自动确认。

更多操作可在创造模式的 **Tick Lock PvP** 分类里打开指南书查看。

## English

Freeze the world, plan your movement, aim, attacks and item use tick by tick, then execute the round together after everyone confirms. Supports solo practice and multiplayer PvP recording.

**[Download v0.9.0 (JAR)](https://github.com/haihuangz/tick-lock-pvp/releases/download/v0.9.0/tick-lock-pvp-0.9.0.jar)** · [Release notes](https://github.com/haihuangz/tick-lock-pvp/releases/tag/v0.9.0)

Requires **Minecraft Java Edition 26.2**, **Fabric Loader 0.19.3+**, **Java 25+**, and **[Fabric API](https://modrinth.com/mod/fabric-api)** for 26.2. Place both JARs in `mods`. On multiplayer, install the same mod version on the server and all participating clients. ReplayMod is optional and client-side. Use the `.jar` asset, not GitHub's automatically generated `Source code` archives.

Press **F7** in a solo world or run `/ticklock start` as the host or operator in multiplayer. Press **F8** to toggle input mode, use the **arrow keys** to select a cell, and press **Enter** to submit, then again once everyone is ready to confirm. `/ticklock ticks 20` changes the round length (1–100, default 5); `/ticklock timer on` enables the optional 60-second timer. See the guide book in the mod's creative tab for more.

## 许可 / License

本仓库仅用于提供官方下载，不公开模组源码。欢迎分享此页面或 Release 链接，请勿擅自重新上传或分发模组文件。完整条款见 [LICENSE](LICENSE)。

This is an official download repository, not a source-code repository. You may share the official page or release link. Do not re-upload or redistribute the mod files without permission. See [LICENSE](LICENSE) for terms.
