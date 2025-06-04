机器人模仿者 僵尸模式游戏版本
==========
必须使用 SourceMod 1.9-6084 或者更高版本才能使用

修改部分功能与逻辑，新增配置文件，用于在僵尸模式游戏中实现类似于cs1.6 sypb 的bot守点抵御僵尸玩法

此版本在原先的基础上 新增配置文件 botmimic_paths.cfg 

用于区分每个地图不同的路线路径

填写的路径会在游戏开始 随机选择 CT bot进行复现

请先为自己想要的路线进行录制，配置文件 "enable"  1开启 0关闭 

每个路线路径后可以用 ,隔开 输入 1 

不输入的情况下 默认bot到达位置 禁止移动 给予武器开始守点

输入的情况下 ，bot到达位置后 将可以自由行动。

此版本是为了 控制bot与人类进行更好的配合玩法修改的版本。

Bot Mimic Zombie Mode Version
==========
requires SourceMod 1.9-6084 or higher for the new OnPlayerRunCmdPost forward.

This modified version introduces new features and logic adjustments, including a configuration file (botmimic_paths.cfg) to implement CS1.6 SyPB-like bot defense gameplay in Zombie Mode.

Key Changes:

Added botmimic_paths.cfg to define unique path routes for each map.

At round start, CT bots will randomly select and mimic pre-recorded paths.

Usage:

Set "enable" to 1 (on) or 0 (off).

Path entries can include optional ,1 suffix:

No suffix: Bots hold position (default behavior, receives weapons and defends).

With ,1: Bots may move freely after reaching the waypoint.

Purpose:

Optimized for cooperative gameplay between bots and human players.
