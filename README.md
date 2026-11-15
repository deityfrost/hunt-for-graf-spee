# 围剿施佩伯爵 · Hunt for Graf Spee

1939年，南大西洋。指挥施佩伯爵号袭商与突围，或统率英国巡洋舰搜索、围堵并保护运输船。

这是一款支持**中文与英文**的非对称回合制海战战棋，由 **Deityfrost** 制作。支持 Windows 单人对战 AI 和同一局域网双人对战。当前试玩版 **0.10.17** 使用3D舰船、海面与岛屿，新局规则仍为 **0.4.14**。

![围剿施佩伯爵海战封面](cover.png?v=0.10.17)

## 下载与运行

**[下载 Windows 试玩版 0.10.17](https://github.com/deityfrost/hunt-for-graf-spee/releases/download/v0.10.17/GrafSpee-0.10.17-Windows.zip)** · [最新发布页](https://github.com/deityfrost/hunt-for-graf-spee/releases/latest)

1. 下载 `GrafSpee-0.10.17-Windows.zip`，解压完整文件夹。
2. 运行其中的 `GrafSpee.exe`，保留同目录的 `GrafSpee.pck`、`platform` 和 `LICENSES`。
3. 支持 Windows 10/11 64位及 OpenGL 3.3，无需安装 Godot 或 Blender；单人游玩无需联网或游戏账号。

首次默认为中文，可在载入封面、开局页或设置中选择 **English**，游戏会记住选择。

**English:** A free asymmetric, simultaneous-turn naval tactics game set in 1939. Command Admiral Graf Spee or the British cruisers. Download the Windows ZIP above, extract the entire folder, and run `GrafSpee.exe`. Select **English** on the opening screen. Single-player AI and two-player LAN are supported.

GitHub自动生成的 `Source code` 压缩包只包含发行仓库资料，游戏请下载上述Windows ZIP。

## 这一版更新了什么

- 加入完整中英界面切换，首次进入即可切换语言。
- 更新深海作战室界面、颜色与 Noto 字体，地图选择、随机设置与预览放在同一区域。
- 改善英军共同追击、商船遇袭响应和护航交接；确认商船能够安全离场后可提前折返，失去追击价值时转向护航等实际任务。
- 改善德军绕岛与脱离、满速移动、保留烟幕及安全后维修的判断，减少远处旧接触引发的不必要用烟。
- 修复部分小岛被误画成海面的轮廓问题，统一 Deityfrost 署名。

基础战斗数值和胜负规则不变。以上策略修改经固定局面核验，最终策略尚无新的完整自战胜率结论。

![中英切换与海图选择](screenshot-menu.jpg?v=0.10.17)

下方作战及复盘截图使用专门构造的演示局面，展示界面与功能，不代表完整实战结果。

![德军3D指挥界面](screenshot-german.jpg?v=0.10.17)

![英军3D指挥界面](screenshot-british.jpg?v=0.10.17)

## 怎么玩

- **双方下令，同时行动。** 规划航迹、射击距离和行动姿态，双方锁定命令后统一执行。
- **德国袭商，英国护航。** 德国积累战果并保持施佩存活；英国可击沉施佩，也可护送足够运输船离场。
- **依据有限情报判断。** 岛屿、烟幕、末次接触和损管会影响追击、集火与撤离。
- **选择不同海域。** 四张预设海图和可重复种子的随机海域，支持存读档及战役复盘。
- **从教学开始。** 内含五节德军教学、战役资料和舰船图鉴。

海图右键拖动旋转，左键或中键拖动平移，滚轮缩放。“全图”“定位己舰”“舰船特写”可找回视角。空格执行、暂停或继续；Tab切换己舰；F1战役资料；F5保存；F9读取；M静音；Esc战役菜单。德国可指定目标，英军自动索敌。完整说明随包提供。

![3D战役复盘](screenshot-replay.jpg?v=0.10.17)

## 升级与存档

建议将新版解压到新文件夹，保留旧版。

0.10.17 延续已发布 0.10.16 的3D档案目录 `%LOCALAPPDATA%\GrafSpee-3D-Combat\`。早期2D版和开发版使用各自目录，不会自动迁入，也不会删除玩家记录。新AI不会改写已记录复盘中的历史命令。

## 局域网双人

两台电脑使用同一版本并连接同一局域网。房主从开局界面进入“局域网”创建房间，另一方查找房间或粘贴房主地址加入。详细步骤见ZIP中的《局域网联机说明.md》。

目前没有互联网匹配、观战、云存档或断线续局。不同显卡及两台实体电脑的路由器环境仍欢迎试玩反馈。

## 反馈与说明

问题或建议可在 **[Issues](https://github.com/deityfrost/hunt-for-graf-spee/issues)** 留言，请附版本、地图、战役种子、回合和复现步骤。

本仓库分发Windows试玩包与公开资料，**不包含游戏开发源码，未将游戏项目按开源许可证发布**。素材来源及第三方许可见随包《素材说明.md》和 `LICENSES`；Noto 字体采用 SIL Open Font License 1.1。

本作以历史舰船和拉普拉塔河口海战为背景，海域、运输任务及胜负条件经过游戏化改编。舰模和封面为历史参考下的美术近似，并非历史照片或精确复原。
