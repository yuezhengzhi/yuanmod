# YuanMod - Stellaris个人MOD

## 项目简介

YuanMod是一个Stellaris（群星）游戏的个人私用MOD，专注于增强游戏中的领袖系统和添加特色事件链。

## 当前功能

### 领袖自动创建系统
- [x] **基本功能**：根据统治者特质自动生成领袖
- [ ] **领袖图像**：为自动生成的领袖提供合适的图像
- **相关文件**：
  - `common/decisions/yuan_leader_decisions.txt`
  - `common/scripted_effects/yuan_leader_effect.txt`
  - `common/edicts/yuan_leader_edict.txt`

## 计划功能

### 领袖自动创建功能文本润色
计划为不同类型的文明提供特色化的领袖描述文本：
- [ ] **格赫罗斯**：作为格式塔意识的领袖文本风格
- [ ] **奥契丝**：作为机械文明的领袖文本风格
- [ ] **若叶睦**：作为碳基生物类的领袖文本风格

### 格赫罗斯事件链
- [ ] **序幕事件**：已开始设计
- [ ] **主线事件**：完整的格赫罗斯相关事件链

## 文件结构

```
yuanmod/
├── common/                  # 游戏核心机制修改
│   ├── decisions/           # 决策相关
│   ├── edicts/              # 法令相关
│   ├── governments/         # 政府类型相关
│   ├── on_actions/          # 游戏事件触发器
│   ├── scripted_effects/    # 脚本效果
│   └── traits/              # 特质相关
├── events/                  # 事件文件
├── gfx/                     # 图形资源
├── localisation/            # 本地化文本
│   └── simp_chinese/        # 简体中文翻译
└── 废弃代码/                 # 存档的旧版代码
```

## 使用说明

1. 将整个mod文件夹放入Stellaris的mods目录中
2. 在游戏启动器中启用该mod
3. 开始新游戏或加载已有存档

## 开发笔记

- 部分功能仍在开发中，可能存在不稳定性

## 版本兼容性

- Stellaris 4.0.21
- 未覆盖原版文件，键名均已yuan_做为起始

---

*注：此MOD为个人私用，功能会根据个人需求不断调整和完善。*

