# 城池设计与证据实验室

三个无需登录、可直接交互的静态网页，由 GitHub Pages 托管。

- [合集首页](https://j72456051-collab.github.io/ancient-city-labs/)
- [城池设计实验室](https://j72456051-collab.github.io/ancient-city-labs/city-builder.html)
- [平面图与三维图生成效率对比](https://j72456051-collab.github.io/ancient-city-labs/layout-vs-3d.html#experiment)
- [政治型与经济型生成效率对比](https://j72456051-collab.github.io/ancient-city-labs/political-vs-economic.html#type-race)

访客可以选择参数、生成模型、运行计时和使用页面原有的导入导出功能，无需 GitHub 或 ChatGPT 账号。设计实验室保存到访客自身浏览器的 localStorage，不提供多人同步；请导出 JSON 备份。

## 来源与版本

1. `city-builder.html` 原样复制自用户提供的“营城-离线版.html”。
2. `layout-vs-3d.html` 原样复制自用户提供的“城池证据实验室-离线版.html”。
3. `political-vs-economic.html` 由原 Sites 项目第 5 版源码生成自包含 HTML；源码提交 `65f437349e8d85ae505e0bd146e754f750ccd6f0`，与已发布版本记录一致。

第二和第三项目前内容一致，各自保留独立文件，并分别定位到图形对比、城市类型对比实验。

所有脚本、样式与模型数据均内嵌，无 API Key 或服务端依赖。外部史料链接需要联网。计时结果是该实现的现场测量，不能据此推论所有平面图都比三维图快，或某类历史城市固有地更易复原。史料与模型边界保留在原页面中。

## 本地使用

双击三个实验 HTML 文件即可使用。也可在本目录运行 `python3 -m http.server 8000`，打开 http://localhost:8000 。

## GitHub Pages

仓库 Settings → Pages → Deploy from a branch → `main` / `(root)`。
