# AI Skills Market

一个开放的 AI 技能数据仓库，收录各种实用 AI 技能/Agent，支持社区浏览、搜索和发现。

## 数据格式

### 技能数据
每个技能存放在 `skills/<skill-id>/` 目录下：
- `skill.json` — 技能元数据（名称、版本、分类等）
- `README.md` — 技能完整文档

### 全局清单
- `manifest.json` — 所有技能的轻量级摘要（列表页数据源）
- `categories.json` — 分类定义

### 模板
- `_templates/skill.json` — skill.json 模板
- `_templates/README.md` — README 模板

## 如何贡献

1. Fork 本仓库
2. 复制 `_templates/skill.json` 到 `skills/<your-skill-id>/skill.json`
3. 编写 `skills/<your-skill-id>/README.md`
4. 在 `manifest.json` 中追加你的技能摘要
5. 提交 PR

## License

MIT
