# EnglishPod

EnglishPod 学习资源归档，按资源类型分目录维护。

## 目录

- [`audio/dialogue/`](audio/dialogue/)：365 份对话音频，逐课独立下载。
- [`audio/podcast/`](audio/podcast/)：365 份完整播客音频，逐课独立下载。
- [`audio/`](audio/)：全部音频的总清单、校验值及原作署名。
- `text/`：后续文本资源目录，尚未添加内容。

## 音频下载

[打开 audio-v1 Release](https://github.com/songmeng20/englishpod/releases/tag/audio-v1) 下载 365 份对话和 365 份完整播客，共 730 个原始 MP3，约 2.50 GiB。

MP3 以 Release 附件形式保存，文件名为 `EP001-dialogue.mp3`、`EP001-podcast.mp3`，依次至 EP365。GitHub Releases 不支持子目录，因此实际音频附件为平铺列表；仓库中的 `audio/` 集中维护所有音频说明和清单，后续文本与音频分开管理。

详见 [音频说明](audio/README.md)、[完整清单](audio/audio-manifest.json)和[校验值](audio/SHA256SUMS.txt)。音频保留原始字节，不重新编码、不剪辑、不变速。

## 署名与许可

原作：**EnglishPod (EnglishPod.com)**；原出版方：**Praxis Language**。原 MP3 依据[历史官方条款](https://web.archive.org/web/20130424034651/http://englishpod.com/terms)采用 [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)。完整来源、许可范围和修改说明见 [audio/ATTRIBUTION.md](audio/ATTRIBUTION.md)。本仓库为独立整理，与原出版方不存在官方合作或背书关系。
