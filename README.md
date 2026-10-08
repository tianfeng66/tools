# 工具导航

这里汇总田丰的公开工具、技能项目和在线 Agent。此仓库只托管公开导航页；各工具保留在独立 GitHub 仓库，在线 Agent 提供直接体验入口。

| 分类 | 工具 | 适用环境 | 用途 | 入口 |
| --- | --- | --- | --- | --- |
| 素材与设计 | 图片工具箱 | 桌面版 Chrome / Edge | 本地图片评分筛选、查重、黑白边检测和整理 | [项目与说明](https://github.com/tianfeng66/image-toolbox) |
| 素材与设计 | 图片分拣与 LUT 调色 | Mac / Windows，本机网页 | 文字分拣、色彩与构图分析、去边裁剪、生成 LUT 并批量调色 | [安装与说明](https://github.com/tianfeng66/image-sorter-lut) |
| 素材与设计 | 人像精修 ComfyUI 工作流 | ComfyUI / GPU | 使用 Z-Image Turbo 三轮低重绘补足人像细节，尽量保持构图与颜色 | [工作流与说明](https://github.com/tianfeng66/comfyui-workflows/tree/main/portrait-refine) |
| 素材与设计 | 长图切分工具 | 桌面版 Chrome | 自动识别长图切口，支持手动调整并批量导出 | [项目与说明](https://github.com/tianfeng66/long-image-splitter) |
| 素材与设计 | PSD 字体打包 | macOS 13+ | 找出 PSD 使用的字体，并与 PSD 一起打包 | [下载与说明](https://github.com/tianfeng66/psd-font-pack) |
| 素材与设计 | 小语种检查 | macOS 13+ | 检测图片、PDF、Word 等文件中的小语种文字并分类导出 | [下载与说明](https://github.com/tianfeng66/minor-language-checker) |
| 视频与 AI | YouTube 下载 + 抽帧 | macOS | 下载视频并按间隔、帧数、帧率或关键帧提取画面 | [项目与说明](https://github.com/tianfeng66/youtube-downloader-frame-extractor) |
| 视频与 AI | AI 名人介绍视频生成 | Codex 技能环境 | 生成经事实核验的旁白、分段视频提示词和参考图制作方案 | [安装与说明](https://github.com/tianfeng66/ai-mingren-video-generation) |
| 视频与 AI | 动漫人物传记视频工作流 | 扣子工作流 | 生成动漫传记视频的分镜、画面、旁白、字幕与拼接结果；草稿版需导入后调试 | [导入与说明](https://github.com/tianfeng66/coze-anime-biography-workflow) |
| 专业知识库 Agent | 多模态大模型美学知识库 | Dify 在线体验 | 打开网页与专业知识库 Agent 对话 | [打开 Agent](https://udify.app/chat/sAQfRGtYLpmnnPi0) |
| macOS 效率 | 秒搜 | macOS 14+ | 使用 Spotlight 索引快速按文件名搜索 | [下载与说明](https://github.com/tianfeng66/miaosou) |
| macOS 效率 | 轻压 QingYa | macOS 13+ | 压缩、解压、预览压缩包并识别中文文件名编码 | [下载与说明](https://github.com/tianfeng66/qingya-mac-archiver) |

## 使用提示

- 浏览器工具在本机处理文件，按各项目 README 的浏览器要求打开；图片工具箱会请求所选文件夹的读写权限，长图切分工具将结果写入单独目录。
- 图片分拣与 LUT 调色在本机运行，首次使用需安装 Python 与依赖。文字分拣、色彩分析和构图分析的“移出”操作会移动原文件；建议先用副本试。
- 人像精修 ComfyUI 工作流需安装 4 个插件与约 20.7 GB 模型；目前尚未完整跑通验证。导入 `portrait_refine_003.json` 前，请按项目 README 配置环境。
- macOS 应用请从各项目的 Releases 或 README 下载安装。具体系统要求与已知限制以原项目说明为准。
- AI 名人介绍视频生成是技能包，不是可独立打开的应用；安装方式见项目 README。
- 动漫人物传记视频工作流是扣子的草稿导入包，需要下载 ZIP 并在扣子中导入、检查节点与额度；不是直接在网页上运行的工具。
- 多模态大模型美学知识库是 Dify 在线 Agent，点击体验入口即可打开对话页面；具体回答请结合知识库资料核对。
- 小语种检查使用 macOS 本地识别能力；Apple 芯片 Mac 解压即用，Intel Mac 首次启动需要联网下载依赖。
- 这里是目录，不复制各项目源码。仓库项目的更新和问题反馈请到对应项目仓库。

网页版入口：https://tianfeng66.github.io/tools/

