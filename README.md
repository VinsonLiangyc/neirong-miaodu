# 内容秒读

**先读一份笔记，再决定深入哪里。**

把 YouTube 和哔哩哔哩长视频的字幕整理成有重点、有逻辑的阅读笔记。支持中文或英文输出，帮助你理解观点背后的理由和例子，也方便保存、导出后慢慢读。

**[在 Chrome 应用商店安装](https://chromewebstore.google.com/detail/hodjcagiecaalcfoehcllcjpiohjdmbp)** · [版本更新](CHANGELOG.md) · [隐私政策](https://vinsonliangyc.github.io/neirong-miaodu/privacy.html) · [问题反馈](https://github.com/VinsonLiangyc/neirong-miaodu/issues)

插件免费，需自行配置模型 API Key；生成笔记、测试连接及人物背景查询可能产生服务商费用。

## 为什么做这个插件

想看的访谈和播客很多，时间和精力却有限。仅看标题和简介，很难判断一两个小时的内容是否值得投入；收藏之后，又常常没有再打开。

我希望先读一份笔记：这期在讨论什么，观点背后的理由和例子是什么，再决定要不要深入。于是，我把自己日常使用的 [Content Digestion Skill](https://github.com/VinsonLiangyc/content-digestion) 整理方法带进浏览器，做成打开视频就能使用的侧栏工具。

## 三个核心体验

### 内容读得完整，重点看得清楚

按主题梳理核心观点、论证和关键例子，用标题、分点、短段落与重点加粗组织内容。开头提供估算字数和预计阅读时间，方便决定现在读，还是导出后慢慢看。

适合访谈、播客、课程等长内容：先理解主要讨论和论证，再回到原视频深入观看。

### 用你习惯的语言，读懂另一种语言里的好内容

中文或英文视频，都可以选择生成中文或英文笔记。默认生成中文；在设置中选好语言后，之后的新笔记和章节说明沿用偏好。字幕保留原文，已有笔记不会自动重写。

### 读懂 ta 的观点，也了解 ta 的专业背景

遇到医学、健康、AI 或其他不熟悉的领域，可以从笔记进入独立的人物背景页，选择主持人或嘉宾，了解 ta 的专业资质、研究成果、与本期议题的关联，以及关键观点的资料依据。

报告附公开来源，方便继续查阅。联网检索与 AI 整理辅助了解人物，不构成官方资质认证，专业资历也不能替代观点证据。

## 阅读、保存与回看

- **字幕与章节**：字幕搜索、播放跟随和时间点跳转，通过章节回到感兴趣的部分。
- **后台生成**：开始任务后可切换标签页或关闭侧栏；关闭整个浏览器可能中断任务。
- **我的笔记**：按标题或作者搜索，本机保存生成结果。
- **多种导出**：单篇支持 Markdown、PDF 和 PNG 长图；笔记库支持多篇 PDF / Markdown 批量导出。
- **长文导航**：阅读到后面也能一键回到顶部，继续复制或导出。

## 开始使用

1. 从 [Chrome 应用商店](https://chromewebstore.google.com/detail/hodjcagiecaalcfoehcllcjpiohjdmbp) 安装，需要 Chrome 116 或更新版本。
2. 打开 YouTube 或哔哩哔哩视频，点击插件图标展开侧栏。
3. 在设置的「模型连接」中选择服务商并填写自己的 API Key。默认提供 DeepSeek，也支持 Kimi、Claude、OpenAI 和兼容接口。
4. 确认字幕已读取，点击生成笔记。在「阅读偏好」中可以选择之后的笔记输出语言。
5. 阅读、复制或导出笔记，也可以进入人物背景页进一步了解分享者。

首次配置可使用插件内的入门指南。聊天产品的会员订阅不等于 API 额度，请以服务商账户中的模型和计费信息为准。

## v0.1.41 更新

- 优化内容取舍与主题归组，保留理解论证所需的理由、例子和适用条件，移除末尾“知识整合”附录。
- 修复引用中的空白框，改善中文与英文、数字之间的排版。
- 增加字数和阅读时间提示，复制与导出同步呈现。
- 将「模型连接」与「阅读偏好」分开，API Key 首屏可填。

内容整理规则适用于新生成的笔记。更多说明见 [更新记录](CHANGELOG.md)。

## 支持范围与隐私

| 项目 | 说明 |
| --- | --- |
| 视频平台 | YouTube、哔哩哔哩；暂不支持 X / Twitter |
| 内容来源 | 可读取的视频字幕，也支持导入对应视频的 SRT、VTT、JSON 字幕 |
| 无字幕视频 | 暂不提供语音转文字或画面文字识别 |
| 笔记语言 | 中文、英文 |
| 保存位置 | 当前浏览器本机，不跨设备自动同步 |
| 人物背景 | 需要可用的联网查询服务与相应站点授权，配置取决于所选服务商 |

笔记与设置保存在本机。生成笔记时，相关字幕和视频信息会发送到你选择的模型服务商；人物背景功能会使用配置的检索服务与公开网页。API Key 用于向对应服务商认证，不通过作者服务器中转。

本机密钥存储不是加密保险箱，请保管好电脑和密钥，并定期导出笔记备份。完整说明见 [隐私政策](https://vinsonliangyc.github.io/neirong-miaodu/privacy.html)。

## 反馈与项目说明

欢迎通过 [Issues](https://github.com/VinsonLiangyc/neirong-miaodu/issues) 提交问题或建议。可以附插件版本、视频链接、错误提示和复现步骤；请勿上传 API Key 或其他私人信息。

作者：Vinson Liang（梁颖琛）

本仓库用于产品介绍、更新记录、问题反馈及隐私政策托管，目前不包含插件源代码。请通过 Chrome 应用商店安装。

---

**English:** 内容秒读 is a Chrome extension that turns YouTube and Bilibili video transcripts into structured reading notes in Chinese or English. It includes chapters, local note storage, exports, and optional speaker-background research with public sources. Bring your own model API key; provider fees may apply. This repository hosts product documentation and the privacy policy, not the extension source code.
