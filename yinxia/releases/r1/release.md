# 发布：r1

- **基于**: B-v002
- **日期**: 2026-10-29

## 包含的版式
- [x] `primary.svg`（必需：主版）——阴阳对印：宣纸色圆角底板上，左白文“印”、右朱文“夏”，拼音“Yìn”“Xià”分写于各自印下；544×377，与 B-v002 相同
- [ ] `icon.svg`——不提供（用户决定“先不配图标”，见 decisions/001、002）
- [ ] `horizontal.svg` / `wordmark-cn.svg` / `wordmark-en.svg` / `wordmark-pinyin.svg`——不提供（主版本身即横版，字标暂无使用场景）
- [ ] `app-icon.svg` / `avatar.svg`——不提供（只导出 svg）

## 决策依据
- `decisions/001-select-direction-b.md`：在 A 方印双字与 B 阴阳对印中选定 B，并决定暂不配方形图标。
- `decisions/002-finalize-b-v002.md`：确认 B-v002 定稿与 r1 只含主版的取舍。
- 系列评审：`_series/xia/series.md` 2026-10-29“系列评审：通过”（对比 xia r1、yinxia B-v002）。

## 说明
印夏的首个发布。B-v002 通过系列评审后，用户要求“定稿发布 r1”。主版直接取自 B-v002，颜色均来自色板（lapis #26619C、paper #FBF3E8）。导出目标为 svg；主要用于 YinXia 系统仓库 README 顶部（可引用 xia-logo 仓库中本发布的 primary.svg）与 GitHub 社交预览图。

## 评审（追加区）
- 2026-10-29 AI 自审：主版彩色/单色/反白完整；宣纸底板在 GitHub 浅色与深色模式下表现一致；32px 以下拼音不可读，指南规定最小尺寸。待用户查看发布预览。
