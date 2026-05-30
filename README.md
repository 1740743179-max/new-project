# GitHub 单文件静态网站

这个项目已经准备好作为 GitHub Pages 站点发布。

## 文件结构

- `index.html`: 单文件静态网站，包含 HTML / CSS / JS

## 本地预览

直接双击 `index.html`，或在当前目录运行任意静态服务器。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库。
2. 把本目录推送到该仓库。
3. 打开仓库页面，进入 `Settings -> Pages`。
4. 在 `Source` 中选择 `Deploy from a branch`。
5. Branch 选择 `master` 或 `main`，Folder 选择 `/(root)`。
6. 保存后等待 GitHub 发布完成。

发布成功后，网站地址通常是：

`https://你的用户名.github.io/仓库名/`

如果仓库名是 `你的用户名.github.io`，则地址通常是：

`https://你的用户名.github.io/`

## 常用 Git 命令

```powershell
git add .
git commit -m "Add single-file static site"
git branch -M main
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```
