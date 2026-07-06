# 项目清理清单 - 仅中文版本

**日期:** 2026-07-06  
**版本:** 6.6.0  
**目的:** 简化项目，仅保留中文资源和操作手册

---

## 📋 删除的文件/目录

### 文档翻译（Docs）
- ✂️ `docs/README.ja.md` — 日文 README
- ✂️ `docs/README.ko.md` — 韩文 README

### 多语言 Skill 包
- ✂️ `skills/seedance-vocab-ja/` — 日文词汇表 Skill
- ✂️ `skills/seedance-vocab-ko/` — 韩文词汇表 Skill
- ✂️ `skills/seedance-vocab-ru/` — 俄文词汇表 Skill
- ✂️ `skills/seedance-vocab-es/` — 西班牙文词汇表 Skill
- ✂️ `skills/seedance-examples-ja/` — 日文例子 Skill
- ✂️ `skills/seedance-examples-ko/` — 韩文例子 Skill

### 多语言参考资料（References）
- ✂️ `references/vocab/ja.md` — 日文词汇参考
- ✂️ `references/vocab/ko.md` — 韩文词汇参考
- ✂️ `references/vocab/es.md` — 西班牙文词汇参考
- ✂️ `references/vocab/ru.md` — 俄文词汇参考

---

## ✅ 保留的文件

### 核心英文文档
- ✓ `README.md` — 完整英文文档（作为技术参考）
- ✓ `SKILL.md` — Skill 系统定义
- ✓ `CHANGELOG.md` — 更新日志

### 中文入门文档
- ✓ `zh-QUICKSTART.md` — **新增** 详细中文快速入门指南 ⭐
- ✓ `docs/README.zh.md` — 中文 README

### 中文 Skill 和参考
- ✓ `skills/seedance-vocab-zh/` — 中文词汇表 Skill
- ✓ `skills/seedance-examples-zh/` — 中文例子 Skill
- ✓ `references/vocab/zh.md` — 中文词汇参考
- ✓ `references/vocab/en.md` — 英文词汇参考（保留用于对标）

### 所有通用 Skills（保留）
- ✓ `skills/seedance-interview/`
- ✓ `skills/seedance-prompt/`
- ✓ `skills/seedance-sequence/`
- ✓ `skills/seedance-continuation/`
- ✓ `skills/seedance-camera/`
- ✓ `skills/seedance-lighting/`
- ✓ `skills/seedance-audio/`
- ✓ `skills/seedance-motion/`
- ✓ `skills/seedance-characters/`
- ✓ `skills/seedance-style/`
- ✓ `skills/seedance-vfx/`
- ✓ `skills/seedance-troubleshoot/`
- ✓ `skills/seedance-prompt-short/`
- ✓ `skills/seedance-copyright/`
- ✓ `skills/seedance-filter/`
- ✓ `skills/seedance-antislop/`
- ✓ `skills/seedance-recipes/`
- ✓ `skills/seedance-pipeline/`
- ✓ `skills/seedance-vocab-en/`

### 所有参考资料（保留）
- ✓ `references/` — 100+ 技术参考文件

---

## 📊 清理前后对比

| 项目 | 清理前 | 清理后 | 减少 |
|------|-------|-------|------|
| **多语言 Skill** | 28 | 21 | -7 |
| **多语言词汇文件** | 6 | 2 | -4 |
| **多语言文档** | 3 | 2 | -1 |
| **总文件数** | ~450+ | ~430+ | -20+ |

---

## 🎯 新用户体验

### 中文用户的启动流程

```
1. 查看 zh-QUICKSTART.md（新增 ⭐）
   ↓ 5 分钟快速了解
   
2. 安装到 Codex / VSCode
   ↓ 2 分钟完成
   
3. 开始使用 seedance-20 Skill
   ↓ 立即生成视频提示词
```

### 英文用户或开发者

```
1. 查看 README.md（技术参考）
2. 查看 SKILL.md（系统定义）
3. 浏览 references/（深度学习）
```

---

## 🔍 关键变化说明

### 为什么删除其他语言？

1. **维护成本高** — 每个翻译都需要同步更新
2. **中文用户优先** — 项目主要面向中文用户
3. **项目精简** — 保持仓库轻量级，克隆更快
4. **清晰的入口** — 不会有语言选择的混乱

### 为什么保留英文？

1. **技术参考标准** — 如需跨语言同步，有英文作为源头
2. **国际用户** — 英文 README 和参考资料可供英文使用者
3. **代码和 API 文档** — 技术细节用英文维护

---

## 📝 安装后建议

### 中文用户新手入门

1. 首先读 `zh-QUICKSTART.md`（10 分钟）
2. 在 Codex 中输入：`@seedance-20 我想要一个视频...`
3. 系统会引导你一步步完成

### 进阶用户

1. 读英文 `README.md` 了解全貌
2. 浏览 `references/` 深度学习各个主题
3. 使用 `seedance-vocab-zh` Skill 优化中文提示词

---

## 🚀 版本信息

- **清理版本:** 6.6.0-zh-only
- **上游版本:** 6.6.0
- **清理日期:** 2026-07-06
- **维护者:** YT-GG

---

## 💡 下一步

如果需要再次添加其他语言：
1. 从 `Emily2040/seedance-2.0` 原仓库 cherry-pick 对应文件
2. 创建新的语言分支（例如 `feature/spanish-support`）
3. 提交 PR

---

**项目已精简完成！** ✨  
中文用户现在有最清晰的入门路径。
