# 余振烨的个人主页

一个无需构建工具的静态个人主页，可部署到 GitHub Pages。页面内容根据现有简历整理；项目配图是概念示意图。

## 本地查看

直接打开 `index.html` 即可。若要用本地服务器预览，在本目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000/`。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个**公开仓库**。GitHub Free 的 Pages 可用于公开仓库。
2. **仅上传本目录中的文件**到新仓库根目录：`index.html`、`styles.css`、`script.js`、`assets/`、`.nojekyll`。不要上传上级目录的原始简历、成绩表等资料。
3. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，选择 `main` 和 `/(root)`，保存。
4. 等待 GitHub 完成发布，页面地址会显示在 Pages 设置页。

本站所有资源均使用相对路径，因此也适用于 `用户名.github.io/仓库名/` 形式的项目站点。

## 修改内容

- 个人资料、项目和获奖经历：编辑 `index.html`。
- 颜色和排版：编辑 `styles.css`。
- 照片：替换 `assets/portrait.jpg`，保持文件名即可。
- 邮箱：搜索 `3410351502@qq.com` 后统一替换。

本版未公开手机号、出生日期、课程成绩、GPA 或排名。发布前请再次检查页面内容是否符合你的公开意愿。
