# 自定义附魔

此文档为自定义附魔UI操作指南，帮助玩家正确使用该功能界面。

---

## 功能概述

自定义附魔UI是一个允许玩家为物品自定义附魔效果的工具界面。通过输入附魔ID及附魔等级，玩家可以为手持物品添加或删除附魔效果。以下为详细的使用说明。

---

## 打开方式

1. **命令输入**：  
   在游戏聊天栏输入以下命令打开UI：  
   
   ```
   /openui enchant
   ```
2. **权限要求**：  
   玩家必须拥有管理员权限（OP权限）才能打开此界面。

---

## 界面组件说明

### 1. **附魔ID输入框**
   - 用于输入附魔效果的ID。
   - 附魔ID对应的效果可在左侧的附魔列表中查找。例如：`0`表示保护，`1`表示火焰保护。
   - 输入不合法的附魔ID时，物品会仅显示附魔光效，但不产生实际效果。

### 2. **附魔等级输入框**
   - 用于设置附魔效果的等级（如1级、2级等）。
   - 附魔等级最高为32767。

### 3. **按钮功能**
   - **附魔手持物品**：  
     点击此按钮，将根据输入的附魔ID和等级，为当前手持物品添加附魔效果。
   - **删除手持物品第一条附魔**：  
     点击此按钮，移除当前手持物品上的第一条附魔效果。

### 4. **附魔列表**
   - 显示附魔ID对应的名称和效果，便于玩家查询。

### 5. **关闭按钮**
   - 界面右上角的“X”按钮用于关闭当前UI界面。
   - 按下键盘上的`ESC`键也可退出该界面。

---

## 使用步骤

1. **确保权限**：  
   确保玩家拥有管理员权限，否则无法打开UI。

2. **打开UI**：  
   在聊天栏输入命令`/openui enchant`，打开自定义附魔界面。

3. **输入附魔信息**：  
   - 在“附魔ID”输入框中输入目标附魔的ID。参考左侧附魔列表选择合适的ID。
   - 在“附魔等级”输入框中输入所需的附魔等级。

4. **附魔手持物品**：  
   - 选择目标物品，确保其处于手持状态。
   - 点击“附魔手持物品”按钮，完成附魔操作。

5. **删除附魔**：  
   - 若需移除附魔，可点击“删除手持物品第一条附魔”按钮。

6. **关闭界面**：  
   - 点击右上角关闭按钮，或按下`ESC`键退出界面。

---

## 注意事项

1. **附魔ID合法性**：  
   输入不合法的附魔ID会导致物品仅显示附魔光效，但不产生实际效果。

2. **权限变更影响**：  
   - 如果在UI打开后，玩家的管理员权限被撤销，则除右上角的关闭按钮外，其余所有按钮将失效。
   - 玩家需重新获取管理员权限后才能正常操作。

3. **退出方法**：  
   - 使用右上角的关闭按钮。
   - 或按下键盘的`ESC`键。

---

## 附魔ID参考列表

| 附魔ID | 效果名称   | 描述                 |
| ------ | ---------- | -------------------- |
| 0      | 保护       | 提供全面伤害保护     |
| 1      | 火焰保护   | 减少火焰伤害         |
| 2      | 掉落保护   | 减少坠落伤害         |
| 3      | 爆炸保护   | 减少爆炸伤害         |
| 4      | 弹射物保护 | 减少投掷物造成的伤害 |
| 5      | 荆棘       | 反弹部分伤害给攻击者 |
| 6      | 水下呼吸   | 增加水下呼吸时间     |
| 7      | 深海探索者 | 提高水下移动速度     |
| 8      | 水下速掘   | 提高水下挖掘效率     |
| ……     | ……         | ……                   |

