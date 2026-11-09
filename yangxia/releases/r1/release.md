# 发布：r1

- **基于**: H-v014
- **日期**: 2026-11-09

## 包含的版式
- [x] `primary.svg`（必需：主版）——印边芽苞：宣纸色底板上，左为新叶绿芽苞形白文印（圆身半径 98，右上 45° 生出两侧内凹的芽尖，在离圆心 140 处收尖），沿全轮廓刻一圈细线（印边 12、线宽 4），芽尖处细线收成一道干净的细缝，“养”镂空并落在芽苞视觉重心；右为新叶绿朱文圆印（半径 104、线宽 12，“夏”实心）；两字同字号同中线，拼音“Yǎng”“Xià”逐字对齐在下方；516×373，与 H-v014 相同
- [ ] `icon.svg`——不提供（用途只有 GitHub 仓库，做成工具时再补方形图标）
- [ ] `horizontal.svg` / `wordmark-cn.svg` / `wordmark-en.svg` / `wordmark-pinyin.svg`——不提供（主版本身即横版，字标暂无使用场景）
- [ ] `app-icon.svg` / `avatar.svg`——不提供（只导出 svg）

## 决策依据
- `decisions/001-shortlist-concepts.md`：第一轮概念筛选（A–D）。
- `decisions/002-reconcept.md`：用户要求全部重新设计后的第二轮概念（E–H）。
- `decisions/003-select-direction-h.md`：选定方向 H 向阳印，并记录 v002 → v003 → v007 → v014 的选定变化。
- `decisions/004-finalize-h-v014.md`：确认 H-v014 定稿、r1 只含主版与色板整理的取舍。
- 系列评审：`_series/xia/series.md` 2026-11-09“系列评审：通过”（对比 xia r2、mengxia r1、tongxia r1、yangxia H-v014、yinxia r1、yunxia r1）。

## 说明
养夏的首个发布。H-v014 通过系列评审后，用户要求“定稿发布 r1”。主版直接取自 H-v014，颜色均来自色板（leaf #65945A、paper #FBF3E8）。导出目标为 svg；同时生成 latest/ 固定地址副本，并更新仓库 README。

## 评审（追加区）
- 2026-11-09 AI 自审：主版彩色/单色/反白完整，印边细线与芽尖细缝在各配色下均可分辨；宣纸底板在 GitHub 浅色与深色模式下表现一致；32px 宽以下细线与细缝变淡、拼音不可读，指南规定最小尺寸。待用户查看发布预览。
