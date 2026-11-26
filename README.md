# 从仿真做科普视频

把一个科普题材做成可操作的网页，录下模型的变化，再配上旁白和字幕。示例用豹纹变色龙捕虫。[打开示例网页](https://creature-sim-cs9.pages.dev/)

## 通用视频制作 Skill

通用视频制作 Skill 已迁到独立仓库。[打开 video-production](https://github.com/songofhawk/video-production)

## 开始使用

1. 下载 [SKILL.md](SKILL.md)。把它交给能操作项目文件和运行命令的 AI 助手。支持导入 Skill 的助手也可以直接导入这份文件。
2. 打开一个空白项目文件夹，准备几张可用的参考图和一段可靠的动作或原理资料。
3. 复制下面的提示词，把方括号里的内容换成自己的题材。

> 请先阅读我提供的 SKILL.md，按里面的路线做一条科普视频。我想让观众看懂［要解释的动作或现象］，参考资料在附件里。先做一个可在浏览器操作的模型，把预览地址和操作方式告诉我。再为全景、特写和关键动作做镜头表，分镜录制并配上我确认的旁白与字幕，最后交付网页项目和 MP4。

愿意从变色龙开始，可以把题材填成「豹纹变色龙怎么用舌头抓住果蝇」，让助手先做拖动转视角、点击放果蝇两个操作。

## 工具

先选一种可以在你的环境里访问项目目录并运行命令的助手。国内可从 [豆包工作](https://www.doubao.com/work) 或 [腾讯 WorkBuddy](https://cloud.tencent.com/act/pro/workbuddy) 了解起。网页示例使用 [Node.js LTS](https://nodejs.org/en/download/)，视频导出使用 [FFmpeg](https://ffmpeg.org/download.html)。需要逐帧拍摄时，再让助手安装 [Playwright](https://playwright.dev/docs/intro) 和它使用的 Chromium。

- [Skill 全文](SKILL.md)
