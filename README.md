# langr-audio — obsidian-language-learner 在线音频 CDN 源

给 obsidian-language-learner 插件做**在线流式播放**用的音频仓库，经 jsdelivr CDN 引用，md 里 `langr-audio` 填 jsdelivr URL，**不占用本地/iCloud 存储**、无需常驻进程。

## 目录结构（按系列分目录）

```
langr-audio/
  say-no-to-slow/     # Chris Birch ADV 越野教程 (Say No to Slow)
  <future-series>/    # 后续系列放各自子目录
```

jsdelivr URL 形如：
`https://cdn.jsdelivr.net/gh/<owner>/langr-audio@<branch>/<series>/<file>.mp3`

## 约定

- 命名与 md 统一：`<SERIES>-NN-Slug.mp3`（如 `SNS-00-Introduction.mp3`）。
- 音频为 **mono 64k mp3** 压缩版，仅供插件跟读播放；原始无损/高码率音频不在此仓库。
- 仓库需保持 **Public**（jsdelivr 只服务公开仓库）。
