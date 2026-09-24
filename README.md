# 示例主题 · 占位内容

纸感日记风个人博客（Jekyll Theme），供 GitHub Pages 使用。

## 本地预览

```bash
bundle exec jekyll serve
```

或仅静态查看构建结果（若已装 Jekyll）：

```bash
jekyll build
```

## 结构

- `_layouts/` · default / post
- `_includes/` · header / footer / entry
- `_posts/` · 你的文章（Markdown，目前为空）
- `templates/post-template.md` · 新文章模板，复制到 `_posts/` 后改名即可
- `assets/css/main.css` · 纸质质感与排版

## 说明

首页、归档由 `_posts` 自动生成；文案与个签见 `_config.yml` 的 `motto` / `bio`。
