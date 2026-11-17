# gerenzhuye

ThornI1538 的个人主页 —— 一个零依赖的单页网站，只有 HTML + CSS + 一点点 JS。

## 本地预览

直接用浏览器打开 `index.html`，或者：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 修改内容

- 名字、简介、技能、项目都在 `index.html` 里，可以直接改文字。
- 头像使用 GitHub 头像：`https://github.com/<用户名>.png`。
- 配色在文件顶部的 CSS 变量里，支持浅色 / 深色模式（跟随系统）。

## 部署到 GitHub Pages

1. 打开仓库的 **Settings → Pages**。
2. Source 选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`。
3. 保存后等待一分钟，站点地址为：
   <https://thorni1538.github.io/gerenzhuye/>

## License

MIT
