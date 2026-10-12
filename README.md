# 十六字真言

以终为始 · 目标拆解 · 发散收敛 · 复盘迭代

带有章节导航、目标拆解图、卡片翻转和 Canvas 动画的单页展示。

## 文件

- `public/index.html`：网站首页，由原始文件 `十六字真言v1.html` 原样复制，页面内部版本标识为 V5.0。
- `netlify.toml`：Netlify 配置，发布目录为 `public`，无需构建命令。

## 本地查看

直接使用浏览器打开 `public/index.html`，不需要安装依赖。

## Netlify 部署

在 Netlify 中导入本 GitHub 仓库，选择 `main` 分支；构建命令留空，发布目录使用 `public`。

也可以在已登录的 Netlify CLI 中执行：

```sh
npx netlify-cli deploy --dir public --prod
```
