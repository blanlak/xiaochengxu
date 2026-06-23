# 撤销更改（Undo）

> 自动触发命令：`@undo`

## 撤销方式

1. **快捷键**（最快）：`Ctrl+Z`(Win) / `Cmd+Z`(Mac)，连续按撤销多步
2. **CodeBuddy 面板**：点击修改消息旁的撤销/User Cancelled 按钮
3. **Git 回退**：
   ```bash
   git checkout -- .          # 撤销所有
   git checkout -- app.json   # 撤销指定文件
   ```
4. **口头指令**：说"恢复 xxx 文件到修改前"
