# 未明子录播 · 公开下载

这里存放未明子录播的转码版本，通过 GitHub Releases 提供**直链下载**，不需要登录、不需要网盘、不需要提取码。

## 直链（点开即下载）

https://github.com/cunnak/lwmz-recordings/releases/download/v261126/lwmz-20261127-1080p.mp4

支持断点续传（HTTP Range），可直接丢给 IDM / aria2 / 迅雷 / 浏览器。

```bash
curl -L -O https://github.com/cunnak/lwmz-recordings/releases/download/v261126/lwmz-20261127-1080p.mp4
aria2c -x 8 -s 8 https://github.com/cunnak/lwmz-recordings/releases/download/v261126/lwmz-20261127-1080p.mp4
```

## 已发布

| 日期 | 文件 | 规格 | 大小 |
|---|---|---|---|
| 2026-11-27 | lwmz-20261127-1080p.mp4 | 1920x1080 H.264 / AAC，2h00m10s | 1.62 GiB |

> 单个 Release 附件上限 2 GiB，因此源片（3.65 GB）已重新编码压缩。画质为 VBR 约 1.9 Mbps，桌面与讲课画面清晰。

## 说明

- 下载走 GitHub 的 `objects.githubusercontent.com` / `release-assets.githubusercontent.com`，国内直连通常不稳，需要代理；对国内观众更友好的方案是对象存储（阿里云 OSS / 七牛 / Cloudflare R2），成本约 0.5 元/GB 流量或免费额度内。
- 仓库和 Release 必须保持 public，否则直链失效。
