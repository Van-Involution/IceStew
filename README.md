# Ice Stew

> **注意**：Ice Stew 基于 1.16 开发，可能不兼容其他版本，如在移植时出现问题，可自行参照 [Minecraft Wiki](https://minecraft-zh.gamepedia.com/Minecraft_Wiki) 等文档修改

## 简介

这是一款基于数据包和资源包制作的 [**冰煲**](https://github.com/Sinbing) 合成配方包，使用不带 NBT 标签的**迷之炖菜**作为冰煲的等效物，并有对应的进度解锁途径。

![demo](demo.png)
效果展示

> **建议**：将资源包和数据包搭配使用以获得最佳~~迫害~~体验

## ~~食用~~使用说明

1. 安装
    - 在 [Release页面](https://github.com/Van-Nya/IceStew/releases) 下载发布版本并解压，或直接 `git clone` 源码
    - 将资源包 `IceStew-r.zip` 放入 `.minecraft/resourcepacks/` 目录中
    - 将数据包 `IceStew-d.zip` 放入到存档数据包目录中
        - 单机存档请放入 `.minecraft/saves/<save_name>/datapacks/`
        - 服务器请放入位于 `world/datapacks/`

1. 启用
    - 在游戏中启用资源包
    - 在游戏中使用命令 `/reload` 重载数据包
    - 在游戏中使用命令 `/datapack list` 查看已加载的数据包，如果返回消息包含 `[file/IceStew-d]` 则加载成功
        - 使用命令 `/datapack [enable|disable]` 可以**启用/禁用**数据包

## 一份（奇怪的）福利

~~兵煲可爱妈妈爱~~（截取了 [零之时_zero](https://space.bilibili.com/23535347) [发布](https://t.bilibili.com/411789159264153150) 的一张壁纸作为图标）

![vanilla_xinbing](vanilla_xinbing.png)
