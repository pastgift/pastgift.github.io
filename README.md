# pastgift.github.io

Pastgift 的个人 GitHub Pages 静态站点。

## 本地预览

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000/>。

## 搜索与 AI Agent

- `robots.txt`：声明公开页面可抓取，并指向 `sitemap.xml`。
- `sitemap.xml`：提供搜索引擎可发现的 canonical 首页。
- `llms.txt`：为 AI Agent 提供低噪声站点摘要和关键链接。
