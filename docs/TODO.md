# Wiki 更新进度和计划

## 已完成 ✅

### 第一阶段：基础结构和完整道具数据库
- [x] 完整道具列表 (all-items.md) - 165个道具完整数据
- [x] 基础文件结构
- [x] 许可证文件
- [x] 术语翻译对照表

## 进行中 🚧

### 第二阶段：基于英文Wiki的内容完善
需要基于 `docs/data/` 中的英文Wiki文件进行完整更新：

#### 高优先级
1. **食物系统** (food.md) - 基于 Food.wiki (794行)
   - 自然食物：浆果、蘑菇、根茎等
   - 包装食品：飞机餐、饮料、饼干等
   - 烹饪系统
   - 营养数据表格

2. **装备系统** (equipment.md) - 基于 Equipment.wiki (380行)
   - 医疗类：绷带、急救包、解毒剂等
   - 可放置类：岩钉、绳索、蘑菇平台等
   - 可使用类：望远镜、信号弹等
   - 详细使用说明

3. **成就系统** (achievements/README.md) - 基于 Badges.wiki (490行)
   - 所有徽章详细信息
   - 解锁条件
   - 获取技巧

#### 中优先级
4. **生物群系** (biomes/README.md) - 基于 Locations.wiki (112行)
   - 5个生物群系详细描述
   - 危险和资源
   - 通关建议

5. **游戏机制** (mechanics/README.md) - 基于 How to play.wiki (159行)
   - 攀登系统
   - 状态效果
   - 游戏循环

6. **难度系统** - 基于 Ascents.wiki (80行)
   - 所有攀登难度
   - 负面效果说明

#### 低优先级
7. **护照系统** - 基于 Passport.wiki (214行)
8. **主页面优化** - 基于 Main Page.wiki

## 数据文件说明

所有英文Wiki源文件位于 `docs/data/`：
- `items.json` - 165个道具完整数据（已使用）
- `Translates.csv` - 官方本地化文本（已部分使用）
- `Food.wiki` - 食物系统英文Wiki
- `Equipment.wiki` - 装备系统英文Wiki  
- `Badges.wiki` - 成就系统英文Wiki
- `Locations.wiki` - 地点/生物群系英文Wiki
- `How to play.wiki` - 游戏玩法英文Wiki
- `Ascents.wiki` - 难度系统英文Wiki
- `Passport.wiki` - 护照系统英文Wiki

## 更新策略

1. 分批次更新，每次聚焦一个主要章节
2. 保持中文翻译准确性，使用官方本地化术语
3. 保留英文Wiki的结构和组织方式
4. 补充游戏数据和详细说明
5. 确保内容实用性和可读性

---

*最后更新：2025-11-11*
*当前进度：第一阶段完成，第二阶段进行中*
