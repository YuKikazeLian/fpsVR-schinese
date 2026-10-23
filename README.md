# fpsVR Simplified Chinese Translation / fpsVR 简体中文译文

Simplified Chinese translation for [fpsVR](https://store.steampowered.com/app/908520/fpsVR/) (by SBSoftLab), prepared for inclusion as an official language.

## Contents

| File | Description |
| --- | --- |
| `fpsVR_strings_schinese.csv` | UI string table: `key`, `field` (text / tooltip), `english`, `schinese` — 477 entries + 7 tooltips, keyed by the in-app string dictionary keys (v2.6) |
| `fpsVR_strings_schinese.json` | Same table as `key → Chinese` JSON (tooltips use `key|tooltip`) |
| `help/overlay_*_help_c.json` | Chinese versions of the 5 `defaults/interface/overlay_*_help_e.json` files (same structure, same keys) |
| `fpsVR_schinese_translation.zip` | All of the above in one archive |

Notes:
- HTML tags, `$` placeholders, units (ms / GB / Hz / mm), file names and internal identifiers are kept unchanged.
- Entries where Chinese is identical to English (abbreviations like `L `, `RC `, `H: `) were intentionally left as-is.
- Tested on fpsVR v2.6 (Windows 11, Chinese locale): CJK text renders correctly with the default `Microsoft Sans Serif` font via Windows font fallback.

This repository contains only translated text, no fpsVR binaries. fpsVR is © SBSoftLab.

---

## 中文说明

这是 fpsVR 的简体中文译文，用于提交给开发者争取加入官方中文。包含界面字典全部 477 条文字、7 条提示文字，以及 5 个悬浮窗帮助文件，已在 fpsVR 2.6 上实测显示正常。

本仓库只包含译文，不包含 fpsVR 程序文件。欢迎提 Issue 指出翻译问题。
