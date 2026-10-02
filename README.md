# ShioriPix

> 栞（しおり）— 日语里的「书签」。
> 一个专注于 **Pixiv Novel** 的第三方 Android 阅读器。

ShioriPix 是一个采用 **Jetpack Compose + MVVM + 模块化 Clean Architecture（简洁版）** 构建的
Pixiv 小说阅读器。项目采用 **feature-first + data/domain/ui 分层** 的混合风格，
按功能模块组织代码，追求清晰的依赖边界与可维护性。

> ⚠️ 本项目为个人学习 / 非官方第三方客户端，与 Pixiv 官方无任何关联。

---

## ✨ 特性（规划中）

- 📖 **小说阅读器** —— 沉浸式阅读体验，支持字号、行距、背景等阅读设置
- 🔍 **搜索** —— 按关键词 / 标签 / 作者搜索小说
- 🏆 **排行榜** —— 日榜 / 周榜 / 月榜
- 📚 **书架** —— 收藏、阅读历史、稍后再读
- 🎨 **Material 3** —— 基于 Material You 的现代 UI
- 🌙 **深色模式** —— 跟随系统 / 手动切换

> 当前进度：**UI 骨架搭建阶段（未接入网络 API，使用本地假数据）**

---

## 🏗️ 架构

采用 **feature-first + 分层（data / domain / ui）** 的简洁版 Clean Architecture：
