# 香港一日游（2026-10-25）

可直接使用 GitHub Pages 托管的静态网页。使用 HTML + JavaScript，**不需要 Node、npm、Docker 或服务器**。

## 网页部署

1. 在 GitHub 创建 `hongkong-trip-2026` Public 仓库。
2. 把本目录的 `index.html` 和 `.nojekyll` 放到仓库根目录。
3. Settings → Pages → Source: Deploy from a branch → Branch: `main` → Folder: `/(root)` → Save。
4. 打开 `https://YOUR_USERNAME.github.io/hongkong-trip-2026/`。

## 说明

- 默认地点及行程基于 2026-10-25 香港一日游计划。
- 交互编辑内容保存在当前浏览器的 localStorage 中，不会自动同步到另一台设备。
- 地图使用 Leaflet 和 OpenStreetMap 瓦片；实时底图、外部导航需要网络。
- 页面中店铺开放时间不是实时数据，营业日仍需确认。
- Github Pages 是公开网址，请确保接受公布行程信息。
- 页面设计受到开源项目 [TREK](https://github.com/liketrek/TREK) 启发，但不是它的官方发行版或源代码派生。
