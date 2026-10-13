# 范静雯 · 视觉传达设计作品集

这是一个可在本地直接预览、也可部署到 GitHub Pages 的静态作品集。页面使用原生 HTML、CSS 和 JavaScript；图片与视频保存在 `assets/` 目录，并按需加载，减少首页解析和等待时间。

## 本地预览

保留 `index.html` 与 `assets/` 文件夹的相对位置，双击 `index.html` 即可在浏览器打开。视频与图片文件不可单独移出 `assets/`。

## 部署到 GitHub Pages

1. 将整个文件夹中的 `index.html` 和 `assets/` 一起上传到仓库根目录。
2. 打开仓库 **Settings → Pages**。
3. 在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)`，保存。
4. 等待 Pages 发布后，使用页面显示的网址访问。

## 更新作品内容

- 项目名称、分类和简介位于 `index.html` 中的 `projects` 数组。
- 项目缩略图与完整长图地址位于 `MEDIA` 对象；把新图片放入 `assets/`，再更新对应路径。
- 视频文件也放在 `assets/`。项目对象的 `video` 字段需与 `index.html` 里的 `media-...Video` 模板 ID 对应。
- 项目详情会先显示视频，再显示对应长图；所有路径使用相对地址。

当前本地版包含天猫 KV、小野 IP 动态 KV 和瑞雪迎年 KV 三个新增项目，尚未发布到 GitHub。
