# FE 学习刷题（Android）

面向基本情報技術者試験（FE）的离线学习应用。科目 A、B 分别提供知识点学习、刷题、错题复习和每日推荐。题干、选项保留日语原文；界面和详细解析使用中文。

## 下载 v0.2.0

- [Android 安装包](https://github.com/yukikazejyc123-gif/fe-study-android/releases/download/v0.2.0/fe-study-android-v0.2.0-debug.apk)
- [完整项目源码包](https://github.com/yukikazejyc123-gif/fe-study-android/releases/download/v0.2.0/fe-study-android-v0.2.0-source.zip)
- [版本说明](https://github.com/yukikazejyc123-gif/fe-study-android/releases/tag/v0.2.0)

最低 Android 7.0。此版使用调试签名，供个人预览试用。**v0.2.0 与旧版签名不同，无法直接覆盖安装；卸载旧版会清除本机学习记录。**尚未进行 Android 实机安装测试。

## 题库与学习

| 内容 | 科目 A | 科目 B | 合计 |
| --- | ---: | ---: | ---: |
| 题目 | 464 | 50 | 514 |
| 学习单元 | 23 | 6 | 29 |
| 知识点 | 144 | 38 | 182 |

题库含 424 道官方过去问、86 道官方样题，以及 4 道明确标注为“原创练习 · 非真题”的练习。旧制午前题单独标注。官方题的题干、选项和答案按 IPA 原卷及答案核验，并附来源链接及可放大的原卷图片。中文解析由本项目编写，不是 IPA 官方解析。

知识点包含日语术语或原文、中文详细讲解、推导步骤、自编教学例子及易错点，适合零基础逐步学习。182 个知识点尚未覆盖完整考试大纲；公开过去问与样题也不代表完整 CBT 题库，题目主题可能重复。

主要来源：[IPA 现行科目 A/B 公开题](https://www.ipa.go.jp/shiken/mondai-kaiotu/sg_fe/koukai/index.html)。每道题及课程的具体资料出处记录在应用及源码内。

应用不需要账号或网络权限，学习记录保存在本机。

## 源码与构建

上面的完整项目源码包，或仓库根目录的 [fe-study-android-v0.2.0-source.zip](./fe-study-android-v0.2.0-source.zip)，解压后可用 Android Studio 打开。GitHub 自动生成的“Source code (zip)”仍包含这一层项目源码包，请直接下载明确命名的完整项目源码包。

构建环境为 JDK 17、Gradle 8.13、Android SDK 35。[GitHub Actions 构建记录](https://github.com/yukikazejyc123-gif/fe-study-android/actions/runs/37170721428)已通过源码文件清单、题库再生成一致性、A/B 学习流程、APK 构建及身份/资源/签名检查。发布 APK 采用本地已核验的文件；CI 产物使用独立的临时调试证书。

## 文件校验（SHA-256）

- APK：`440b0f857df16d9cf1b25040992d5e276625ec4527d5ffaa6220c714e887cecb`
- 完整源码包：`4ff84143297b929876fe178a38c654e4c80ed8b67309b1662b3de4076c5988a9`
