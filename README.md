# Hello Sophia! 仓库结构

这个 `site` 文件夹已经整理成适合长期维护的静态站点结构，可以直接作为 GitHub 仓库根目录使用，也可以直接上传到 Vercel。

## 目录

```text
site/
├── CNAME
├── README.md
├── .gitignore
├── index.html
└── assets/
    └── images/
        ├── sophia_morning_ai.jpg
        ├── sophia_city_ai.jpg
        └── sophia_creative_ai.jpg
```

## 说明

- `index.html`：站点主页面
- `assets/images/`：高清原图资源
- `CNAME`：自定义域名配置，当前是 `dengzhaotong.com`
- `.gitignore`：忽略本地无关文件

## 推荐维护方式

1. 把这个 `site` 文件夹里的内容作为 GitHub 仓库根目录
2. 日常只改：
   - `index.html`
   - `assets/images/`
3. 再让 Vercel 或 GitHub Pages 从仓库自动部署

## 部署建议

- GitHub Pages：仓库根目录直接发布
- Vercel：导入仓库后直接部署，无需额外构建步骤

## 注意

- 现在这版使用的是独立图片文件，不再把图片内嵌进 HTML
- 以后替换图片时，优先直接替换 `assets/images/` 下的文件
