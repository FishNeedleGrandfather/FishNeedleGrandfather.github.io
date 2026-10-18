# 余振烨的个人主页

这是一个可直接发布到 GitHub Pages 的静态网站。仓库根目录包含 `index.html`，无需安装依赖或执行构建命令。

## 本地预览

在仓库根目录运行：

```powershell
python -m http.server 8000
```

然后打开 `http://localhost:8000/`。

## 发布到 GitHub Pages

在 GitHub 创建一个空的公开仓库，推荐命名为 `YOUR_USERNAME.github.io`。把下面命令中的 `YOUR_USERNAME` 和 `REPO_NAME` 换成真实值后，在本仓库目录运行：

```powershell
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git push -u origin main
```

在 GitHub 仓库的 **Settings → Pages** 中，将 **Build and deployment** 设为 **Deploy from a branch**，分支选择 `main`，目录选择 `/(root)`，然后保存。个人站点仓库的网址是 `https://YOUR_USERNAME.github.io/`；其他仓库的网址是 `https://YOUR_USERNAME.github.io/REPO_NAME/`。

## 修改网站

- 内容：`index.html`
- 样式：`styles.css`
- 照片：`assets/portrait.jpg`
- 图标：`assets/favicon.svg`

网站展示照片和邮箱，不展示手机号、出生日期、GPA 或排名。
