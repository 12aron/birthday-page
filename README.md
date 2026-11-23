# birthday-page

GitHub Pages 托管版“Happy Birthday”静态祝福页。

- 站点目录：`site/`（首次运行时由工作流从上游 [ayusharma/birthday](https://github.com/ayusharma/birthday) 自动导入并提交，之后不再覆盖）
- 依赖自托管：`site/vendor/` 存放 jQuery 1.11.2、Bootstrap 3.3.1、less.js 2.1.0，页面不再依赖 Google/CDN 外链
- 发布：`.github/workflows/deploy.yml` 读取 `site/` 并发布到 GitHub Pages
- 线上地址：https://12aron.github.io/birthday-page/
- 修改内容：编辑 `site/index.html`、`site/stylesheet.css`，替换 `site/bd1.jpg` 等，推送到 `main` 即自动重新发布
