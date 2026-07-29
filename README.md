# Zhijian Yu Academic Homepage

静态个人学术主页。所有公开内容直接写入 HTML，便于搜索引擎抓取。

## 发布

- GitHub Pages：在仓库 Settings → Pages 中选择 **GitHub Actions**，每次推送 `main` 会更新预览。
- 腾讯云 COS：完成域名备案、COS 静态网站和 CDN 配置后，在仓库 Actions 中手动运行 `Deploy production site to Tencent COS`。先在仓库 Secrets 中设置 `TENCENT_SECRET_ID`、`TENCENT_SECRET_KEY`、`TENCENT_COS_BUCKET` 和 `TENCENT_COS_REGION`。

生产域名固定为 `https://www.zhijianyu.top/`。部署前请确认 DNS、HTTPS 和 `sitemap.xml` 中的域名一致。
