# FE 学习刷题（Android）

面向基本情報技術者試験（FE）的离线学习应用：学习、刷题、错题复习、每日推荐。界面与解析使用中文，题干和选项保留日语。

## 下载

从 [v0.1.0 预览版](https://github.com/yukikazejyc123-gif/fe-study-android/releases/tag/v0.1.0)下载 `fe-study-android-debug.apk`。最低 Android 7.0。此 APK 使用调试签名，供个人试用。

## 题库

共 64 道：60 道 [IPA 官方公开题](https://www.ipa.go.jp/shiken/mondai-kaiotu/sg_fe/koukai/index.html)（2023–2026 年科目 A/B）和 4 道明确标注为“原创练习 · 非真题”的题目。官方题的题干、选项和答案按 IPA 题册与答案核查；中文解析为本项目编写，不是 IPA 官方解析。并未声称收录完整 CBT 题库。

## 源码

仓库根目录的 [`fe-study-android-source.zip`](./fe-study-android-source.zip)是完整 Android 项目。下载并解压后可用 Android Studio 打开。GitHub 自动生成的“Source code (zip)”中还套有这一层源码包，请直接取上面的文件。源码包内的 README 包含项目结构、构建方法和题目来源说明。

GitHub Actions 的[构建记录](https://github.com/yukikazejyc123-gif/fe-study-android/actions/runs/37098823220)已完成题库校验、功能烟测、APK 构建，以及包名、签名和内置题库检查。应用不需要账号或网络权限，学习记录保存在本机。
