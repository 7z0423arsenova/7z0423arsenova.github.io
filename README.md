# 7z0423arsenova.github.io

Arsenova 的个人网站。纯静态 HTML + CSS，无构建步骤，推送到 `main` 即由 GitHub Pages 发布。

| 文件 | 作用 |
|---|---|
| `index.html` | 首页内容（搜索 `TODO` 找到需要改的地方） |
| `style.css` | 全部样式，颜色变量在文件顶部 |
| `404.html` | 找不到页面时显示 |
| `CNAME` | 自定义域名（配置好 DNS 后再添加） |

本地预览：

```sh
python3 -m http.server 8000
```
