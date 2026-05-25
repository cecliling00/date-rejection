# date-rejection Skill — 安装指南

## 你需要做的事情（分享方）

把 `date-rejection.zip` 发给对方。文件在这：
```
/Users/mac/WorkBuddy/2026-05-25-15-33-48/date-rejection.zip
```

通过微信、邮件、AirDrop 等任意方式发送即可。

---

## 对方需要做的事情（安装方）

### 第一步：解压到指定目录

把收到的 `date-rejection.zip` 解压到：

```
~/.workbuddy/skills/
```

解压后目录结构长这样：

```
~/.workbuddy/skills/date-rejection/
├── SKILL.md
└── references/
    └── rejection_patterns.md
```

**macOS 操作方式：** 打开访达 → 菜单栏「前往」→「前往文件夹」→ 输入 `~/.workbuddy/skills` → 把解压出来的 `date-rejection` 文件夹拖进去。

### 第二步：搞定，直接用了

Skill 放入目录后即刻生效，不需要重启任何东西。在 WorkBuddy 里说出触发词就会自动加载。

---

## 验证是否安装成功

让对方在 WorkBuddy 里说：

> 「有人约我看电影，怎么拒绝」

如果能输出一句荒诞拒绝话术，说明安装成功。

---

## 常见问题

**Q: 我没有 `~/.workbuddy/skills/` 这个目录怎么办？**
手动创建即可。打开终端输入：`mkdir -p ~/.workbuddy/skills`

**Q: 解压后 Skill 没生效？**
检查解压后是否是 `date-rejection/SKILL.md` 的路径结构，不要把文件夹多套一层。

**Q: 想卸载？**
删除 `~/.workbuddy/skills/date-rejection/` 整个文件夹即可。

**Q: 想改触发词或添加新模式？**
编辑 `SKILL.md` 开头 description 部分加触发词，或修改 `references/rejection_patterns.md` 加新话术示例。
