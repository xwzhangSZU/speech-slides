<!-- .slide: data-background-color="#1a1a2e" -->

# Speech Slides Demo

**演示幻灯片**
GitHub Pages + Reveal.js

---

## 为什么用 GitHub Pages？

- 无需优盘，浏览器输入网址即可播放
- 免费托管，无限次修改
- 易于分享，发链接即可
- 版本管理，每次修改都有记录

---

## 工作流

```text
写 Markdown → push 到 GitHub → 自动部署
```

1. 在 `slides.md` 中用 Markdown 写内容
2. `git push` 推送到仓库
3. GitHub Pages 自动更新
4. 浏览器打开链接即可演示

---

## Markdown 语法示例

**加粗**、*斜体*、`行内代码`

> 引用文字效果

- 列表项 A
- 列表项 B
- 列表项 C

---

## 代码高亮

```python
def greet(name: str) -> str:
    """Say hello."""
    return f"Hello, {name}!"
```

---

## 垂直幻灯片

按 **↓** 向下翻页

--

### 子页面 1

垂直幻灯片适合补充细节

--

### 子页面 2

主线用 `---` 分隔，子页用 `--` 分隔

---

<!-- .slide: data-background-color="#16213e" -->

## 谢谢！

Questions?
