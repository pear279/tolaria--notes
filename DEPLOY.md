# Tolaria 调研页发布说明

本页面是纯静态站点，无需构建。

## 需要上传的文件

- `index.html`
- `assets/`

## GitHub Pages

1. 新建一个公开仓库，或使用现有仓库。
2. 把 `index.html` 和 `assets/` 放到仓库根目录。
3. 在仓库设置中打开 Pages，Source 选择 `Deploy from a branch`，目录选择根目录。
4. 发布后访问 GitHub Pages 提供的链接。

## Vercel / Netlify

1. 新建静态站点项目。
2. 选择当前目录作为项目根目录。
3. Build command 留空。
4. Output directory 留空或填 `.`。

入口文件是 `index.html`，页面内目录锚点可以直接分享，例如 `#obsidian`、`#tech-stack`。
