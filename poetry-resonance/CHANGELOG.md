# CHANGELOG

## v1.4.4 — 2026-09-13

ClawHub 可发现性修复 + 门面精简（正文行为无变化）：

- **v1.4.3（可发现性）**：ClawHub 分类由 `other` 改为 `knowledge, lifestyle`；主题标签补为 `chinese-poetry / daily-quote / libai / dufu / song-ci`（原 `sushi` 有歧义，换掉）。
- **v1.4.4（描述精简）**：frontmatter `description` 由 744 字压缩至 496 字（-33%），保留全部高频触发词；新增英文问题句前置与 `Not for` 边界声明（学术考据 / 格律创作 / 非中文诗词）。
- 正文新增「何时不用」「与谁不同」两节——会渲染到 ClawHub 页面正文，进搜索引擎与 AI 索引。

### 后续待办

- 精读库（references/poems.md）由当前 45 首逐步扩充至 60+ 首。
- 本地 git clone 落后远端多个 commit，联网恢复后 `git pull` 对齐。

## v1.4.2 — 2026-09-03

体检后调整（基于线上 v1.4.1，正文与线上一致，仅门面优化）：

- 精简 frontmatter `description`：由 731 字压缩至 456 字（约 -38%），删除冗余修辞、将模式 A–E 描述改为紧凑短语、合并同类信息；**30 个触发词全部保留**，匹配入口不变。
- 新增 `version` 字段（frontmatter），建立版本号管理习惯。注册表版本以发布时的 semver 为准（本次发布应为 1.4.2）。

### 后续待办

- 精读库（references/poems.md）由当前 45 首逐步扩充至 60+ 首。
- 养成版本迭代记录习惯：每次变更同步更新本 CHANGELOG 与 `version`。
