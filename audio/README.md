# EnglishPod audio

EnglishPod EP001–EP365 原始音频归档：365 份对话和 365 份完整播客，共 730 个 MP3，2,683,386,630 字节（约 2.50 GiB）。

每个音频提供独立 MP3 下载，未重新编码、剪辑或变速。不提供全量或分类音频压缩包。Git 仓库仅保存说明和校验清单，MP3 独立保存在 Release 附件中。

## 按类型选择

- [对话音频：365 课逐课独立下载](dialogue/README.md)
- [播客音频：365 课逐课独立下载](podcast/README.md)

两个目录分别提供该类型的文件清单与 SHA-256 校验值。每份 MP3 是独立附件，下载某课音频不会附带其他文件。

## Download / 下载

- 对话文件：`EP001-dialogue.mp3` 至 `EP365-dialogue.mp3`。
- 播客文件：`EP001-podcast.mp3` 至 `EP365-podcast.mp3`。
- [EP001 对话](https://github.com/songmeng20/englishpod/releases/download/audio-v1/EP001-dialogue.mp3)
- [EP001 播客](https://github.com/songmeng20/englishpod/releases/download/audio-v1/EP001-podcast.mp3)

每个文件的课号、原标题、大小、SHA-256、来源和下载地址见 [audio-manifest.json](audio-manifest.json)。可对已下载的单个 MP3 运行 `shasum -a 256 文件名.mp3`，与清单中该文件的 SHA-256 对照。

固定版本下载入口可能重定向至 GitHub 的临时签名 CDN 地址。使用固定版本入口，不保存重定向后的临时地址。不同地区和运营商的可达性可能不同；本归档不承诺中国大陆的网络稳定性或微信小程序域名准入。

## Attribution / 署名与许可

Original work: **EnglishPod (EnglishPod.com)**. Originally published by **Praxis Language**. Original MP3 recordings are provided under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) as identified in the [historical publisher terms](https://web.archive.org/web/20130424034651/http://englishpod.com/terms). See [ATTRIBUTION.md](ATTRIBUTION.md) for source attribution, license scope and modification details.

本仓库为独立整理，与原出版方不存在官方合作或背书关系。
