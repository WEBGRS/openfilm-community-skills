# OpenFilm 社区技能

官方 10 个以外的 [OpenFilm](https://github.com/openfilm/openfilm) 技能，以及大家常和 OpenFilm 一起用的视频类智能体技能。OpenFilm 自带的「发现」页只列官方的 10 个，这份清单收其余的。[English](README.md)

## 怎么加

在 OpenFilm 的技能页点「添加 skill」，粘贴表里的链接。指向仓库里某个文件夹的链接（`.../tree/main/<文件夹>`）也可以。命令行：`npx openfilm skill add <链接>`。加进 OpenFilm 的技能对每个项目都生效，不想用可以在技能页关掉。

## 为 OpenFilm 写的

都按 OpenFilm 的[技能规范](https://github.com/openfilm/skills/blob/main/SPEC.md)写：一份短需求书，只有智能体没别的办法做到的事才配脚本。

| 技能 | 做什么 | 需要 | 许可证 |
| --- | --- | --- | --- |
| [web-demo](https://github.com/WEBGRS/openfilm-web-demo) | 按步骤录网页产品的演示；产品改版后按原步骤重录，剪辑不变；配音跟着步骤走；同一段录像还能导出图文操作指南 | Chrome 或 Edge、FFmpeg | MIT |
| [app-demo](https://github.com/WEBGRS/openfilm-app-demo) | 一边操作一边录 Windows 软件，指针平滑，每次点击镜头推近 | Windows 10 或 11、FFmpeg 8 | MIT |
| [preview-first](https://github.com/WEBGRS/openfilm-preview-first) | 几分钟内先出整片的占位卡片预览，你确认后再做画面、再做声音；花钱前先报用量 | 无 | MIT |
| [talking-head](https://github.com/WEBGRS/openfilm-talking-head) | 口播精剪：去掉口癖、卡壳和空档，只在停顿处下刀；加重点词、人物名片和封面 | OpenFilm 里连好一个语音转写服务 | MIT |
| [视频规范模板](https://github.com/WEBGRS/openfilm-skill-template) | 不直接出片：一份空白模板，把你自己的规矩（节奏、画面、字幕、声音）写成技能，附一个填好的科普短片样例 | 无 | MIT |

不是技能，但为 OpenFilm 做的：[local-voice](https://github.com/WEBGRS/openfilm-local-voice)，在你自己电脑上配音（Kokoro 音色；要更好的音质或用你自己的声音，走 Qwen3-TTS），带逐字时间的字幕。在 设置 → 服务商 → 自定义服务 里添加。

## 其他视频类智能体技能

这些是通用的智能体技能，不是为 OpenFilm 写的，各自出自己的视频（或者自己的网页和代码）；在 OpenFilm 里，它们做出来的东西就是你片子里的一个片段。收进来是因为 OpenFilm 社区里有人在用。用它们做的东西要发出去之前，先看各自的许可证。

| 技能 | 做什么 | 基于 | 许可证 |
| --- | --- | --- | --- |
| [video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft) | 从网页项目做产品宣传片：真实页面截取、镜头卡片、踩拍剪辑 | Remotion | Apache-2.0；它的 README 提醒公司使用可能要买 Remotion 授权 |
| [xilo-opus-video](https://github.com/Kianzzz/xilo-opus-video/tree/main/skills/xilo-opus-video) | 先给三个方案、各带预览，选定后写成代码页面渲染成 MP4 | Playwright、FFmpeg | MIT |
| [lemo-opuscar](https://github.com/lemomo-ai/lemo-opuscar/tree/main/plugin/skills/lemo-opuscar) | 用代码做短片，可选它库里的画风，也可以自己定；也能用真实素材做解说、用档案影像剪片 | 自己的逐帧渲染器 | 代码 MIT；三条演示配音不在许可范围内 |
| [huashu-art-motion](https://github.com/alchaincyf/huashu-art-motion) | 艺术画面和科普动画，36 种风格；需求书是中文 | Python、Playwright | MIT，人物形象、笔画数据和字体除外 |
| [dashi-animationstyle](https://github.com/chuspeeism/dashi-animationstyle) | 把 15 到 60 秒的中文口播录音做成 1080p 带字幕的视频，7 种手绘风格可选 | Canvas、无头 Chrome | MIT，示例录音除外 |
| [wtt-code-animation-studio](https://github.com/WaterDJiang/Wattter_openSkills/tree/main/wattter_skills/wtt-code-animation-studio) | 从想法、文章或稿子出中文脚本、分镜、可改的源码和带声音的视频 | Canvas 或 p5.js | 没有许可证文件；仓库 README 写的是 CC BY-NC-SA 4.0，不可商用 |

不是技能：[mg-styles-15](https://github.com/Vincentwei1021/mg-styles-15)，15 条 10 秒的动效短片，每条附完整提示词和源码，复制提示词给智能体用。MIT。

许可证和依赖于 2026-10-30 从各仓库读取。

## 推荐一个

开一个 issue 或 pull request，附上链接。收录条件：仓库公开，有智能体能读的 SKILL.md，写明了用什么许可证。
