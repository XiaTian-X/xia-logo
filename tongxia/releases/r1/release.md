# 发布：r1

- **基于**: B-v007
- **日期**: 2026-10-29

## 包含的版式
- [x] `primary.svg`（必需：主版）——契合印：宣纸色圆角底板上，左为墨色圆角方印（“同”镂空，阴印），右侧让出圆弧咬口容下墨色圆印（“夏”实心，阳印），拼音“Tóng”“Xià”逐字对齐在下方；488×389，与 B-v007 相同
- [ ] `icon.svg`——不提供（用途只有 GitHub 仓库，暂无方形需求）
- [ ] `horizontal.svg` / `wordmark-cn.svg` / `wordmark-en.svg` / `wordmark-pinyin.svg`——不提供（主版本身即横版，字标暂无使用场景）
- [ ] `app-icon.svg` / `avatar.svg`——不提供（只导出 svg）

## 决策依据
- `decisions/001-select-direction-b.md`：在 A/B/C/D 四个方向中选定 B，并经多轮调整定为方圆契合、墨色加宣纸底板（B-v007）。
- `decisions/002-finalize-b-v007.md`：确认 B-v007 定稿与 r1 只含主版的取舍。
- 系列评审：`_series/xia/series.md` 2026-10-29“系列评审：通过”（对比 xia r2、tongxia B-v007、yinxia r1）。

## 说明
同夏的首个发布。B-v007 通过系列评审后，用户要求“定稿发布 r1”。主版直接取自 B-v007，颜色均来自色板（sumi #2E2A28、paper #FBF3E8）。导出目标为 svg；同时生成 latest/ 固定地址副本，并更新仓库 README。

## 评审（追加区）
- 2026-10-29 AI 自审：主版彩色/单色/反白完整；宣纸底板在 GitHub 浅色与深色模式下表现一致；32px 以下拼音不可读、16px 时契合缝消失，指南规定最小尺寸。待用户查看发布预览。
