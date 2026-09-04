# CatSeed-Re

Minecraft 1.7.10 Forge + Crucible（CraftBukkit API）服务器的自研插件集合。全部插件面向本服实战开发，可在 Bukkit/Spigot/Crucible 1.7.10 上直接构建部署。

## 项目一览

### 玩家功能

| 项目 | 版本 | 简介 |
|---|---|---|
| [BindSystem](https://github.com/CatSeed-Re/BindSystem) | v1.0.0 | 绑定/解绑插件：Vault 计费 + ILS Soulbound 拦截 + 拾取限制 |
| [ItemRent](https://github.com/CatSeed-Re/ItemRent) | v1.0.0 | 物品租赁：挂牌出租、按天收费、到期自动归还 |
| [ItemEnhance](https://github.com/CatSeed-Re/ItemEnhance) | v1.5.2 | 概率强化（qh）：伤害/生命/闪避/防御/格挡强化 |
| [LuckyDraw](https://github.com/CatSeed-Re/LuckyDraw) | v1.2.1 | 抽奖盒 + 分层奖励 + GUI 配置台 |
| [LuckyMine](https://github.com/CatSeed-Re/LuckyMine) | v1.2.0 | 幸运挖矿：挖指定方块概率掉落自定义奖池 |
| [RPGTrade](https://github.com/CatSeed-Re/RPGTrade) | v1.1.14 | RPGItems 多材料兑换告示牌 |
| [CustomFishing](https://github.com/CatSeed-Re/CustomFishing) | v1.0.0 | 自定义钓鱼：渔获替换为加权随机物品/RPGItems |
| [HealSignMaxHealth](https://github.com/CatSeed-Re/HealSignMaxHealth) | v1.0.0 | `[Heal]` 回血告示牌 |
| [XianyuProjectileDamage](https://github.com/CatSeed-Re/XianyuProjectileDamage) | v1.0.0 | 咸鱼机枪：右键箭矢齐射 + 自定义伤害 |
| [TimedItem](https://github.com/CatSeed-Re/TimedItem) | v1.0.1 | 限时道具：到期自动删除、全服统一到期、离线补发 |

### 基础设施

| 项目 | 版本 | 简介 |
|---|---|---|
| [ItemUUID](https://github.com/CatSeed-Re/ItemUUID) | v1.2.7 | RPG 物品 UUID（NBT 持久化）+ SQLite 审计日志 |
| [PlayerLoginTracker](https://github.com/CatSeed-Re/PlayerLoginTracker) | v1.0.0 | 玩家/IP 双向登录关系记录 |
| [ILSHatRefresh](https://github.com/CatSeed-Re/ILSHatRefresh) | v1.0.0 | `/hat` 换头盔后刷新 ILS 生命值 |
| [RPGMaterialAliases](https://github.com/CatSeed-Re/RPGMaterialAliases) | v1.1.0 | 启动期注册 RPGItems 数字材质 ID 别名 |
| [SpawnPlatformGenerator](https://github.com/CatSeed-Re/SpawnPlatformGenerator) | v1.0.0 | 虚空世界生成器 + 中心出生平台 |

### 修复 / 保护

| 项目 | 版本 | 简介 |
|---|---|---|
| [NullSourceExplosionGuard](https://github.com/CatSeed-Re/NullSourceExplosionGuard) | v1.0.0 | 拦截无来源爆炸事件 |
| [PlotWorldBlockGenGuard](https://github.com/CatSeed-Re/PlotWorldBlockGenGuard) | v1.0.0 | 地皮世界生成区块时清理异常方块 |
| [SpawnFireGuard](https://github.com/CatSeed-Re/SpawnFireGuard) | v1.1.0 | 出生点保护：阻止火焰传播与未授权建筑 |

### 工具 / 扩展

| 项目 | 版本 | 简介 |
|---|---|---|
| [RPGItems-rpgitem-editor](https://github.com/CatSeed-Re/RPGItems-rpgitem-editor) | v1.0.0 | RPGItems `items.yml` 可视化配置台（纯前端） |
| [RPGItems-weapon-powers](https://github.com/CatSeed-Re/RPGItems-weapon-powers) | v3.5.265 | RPGItems 武器技能扩展（8 个新 Power） |
| [tools](https://github.com/CatSeed-Re/tools) | v1.0.0 | 服务器配置审计与编辑工具 |

## 环境

- Minecraft 1.7.10，Forge + Crucible（CraftBukkit API）
- JDK 17 构建，`-source 7 -target 7` 兼容服务端 JRE8（Java 7 字节码）
- 常用依赖：Vault 1.7.3、EssentialsX、ItemLoreStats（ILS）、ItemUUID、RPGItems

## 详细文档

各仓库 README 均包含功能介绍、命令/权限、配置示例与构建方式；完整项目索引见 [docs/CatSeed-Re-项目总览.md](https://github.com/CatSeed-Re/.github/blob/main/profile/README.md)。
