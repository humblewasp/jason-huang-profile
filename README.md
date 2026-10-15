# 黄钧峰 Jason｜个人简历

[打开网页版简历](https://humblewasp.github.io/jason-huang-profile/)

中英文简历，包含教育背景、工作经历、实习经历、项目经历与业余生活，支持翻书阅读和 PDF 下载。

此仓库存放网站的静态发布文件，由 GitHub Pages 发布。

首页主要项目可直接打开对应经历章节；履历、成果与简历下载已按 2026 年 10 月提供的简历更新。

## 内容维护

- `assets/profile-data-20261015.js`：可读的中英文个人简介、案例、教育背景与经历数据。
- `assets/profile-20261015-v2.js`：页面与原有翻书交互；`index.html` 指向此入口。
- `assets/profile-refresh-20261015-v2.css`：本次优化的补充样式，沿用既有配色与照片。
- `huang-junfeng-resume.pdf`：下载用简历。更新时同时调整入口中的版本参数与 service worker 缓存版本。

所有页面路径均保留 `/jason-huang-profile/` 前缀，可直接由 GitHub Pages 发布，无需构建。
