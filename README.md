# Speech Slides

Reveal.js 幻灯片集合，通过 GitHub Pages 在线播放。

## 在线访问

🔗 **https://xwzhangSZU.github.io/speech-slides/**

## 目录结构

```
speech-slides/
├── index.html          ← 首页索引
├── .nojekyll           ← 跳过 Jekyll 构建
├── _template/          ← 新幻灯片模板
│   ├── index.html
│   └── slides.md
├── demo/               ← 演示幻灯片
│   ├── index.html
│   └── slides.md
└── your-talk/          ← 你的演讲（复制 _template 创建）
    ├── index.html
    └── slides.md
```

## 新建一套幻灯片

```bash
# 1. 复制模板
cp -r _template/ my-talk/

# 2. 编辑 slides.md 写内容

# 3. 推送
git add my-talk/
git commit -m "feat: add my-talk slides"
git push
```

然后访问 `https://xwzhangSZU.github.io/speech-slides/my-talk/`

记得在根目录 `index.html` 中添加卡片链接。

## 技术栈

- [Reveal.js 5](https://revealjs.com/) — CDN 加载，无需构建
- GitHub Pages — 免费托管
- Markdown — 用 `slides.md` 写内容，`---` 分页
