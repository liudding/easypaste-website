# 项目长期记忆：easypaste-website

## 站点结构与内容约定
- 静态站点（Vercel），暗色主题 + CSS 变量。博客文章分两类：
  - **Pillar / 指南页**：单文件 + `translations.js` 驱动 i18n（body 用 `data-i18n` 键，lang 切换靠 JS）。新增多语言文案须往 `translations.js` 的 `zh`/`en` 对象加键。
  - **Hub / Spoke 盘点对比与教程页**：双语各一套独立静态 HTML 文件（如 `blog/x.html` + `en/blog/x.html`），不依赖 translations.js 翻 body；语言切换靠 nav 里的 `class="lang-toggle"` 链接跳转到对应 URL。
- 每篇文章须含：canonical + hreflang（zh-CN/en/x-default 三者互链）、OG/Twitter、3 段 JSON-LD（Article+BreadcrumbList+FAQPage）、`.article table` 与 `.faq-item` 样式（见现有 roundup 页模板）。
- 竞品外链（pasteapp.io / maccy.app / raycast.com 等）统一 `rel="nofollow"`；权威来源（Apple Support、Wikipedia）用 dofollow。
- 内容集群：Pillar（终极指南）↔ Hub（盘点对比）↔ Spoke（教程/单品对比/系统自带）须双向互链，避免孤立页。

## 品牌口径
- 产品名「EasyPaste（macOS 剪贴板管理器）」，需与同名 iOS 键盘「EasyPaste 快易贴」及 GitHub 项目区分。正文统一用全称，避免出现「本品」。

## SEO 工作流（可复用）
- 5 阶段 SOP：keyword-researcher → content-writer → 并行(seo-optimizer/content-editor/link-strategist) → cro-analyst → 主理人整合交付报告。
- 发布阈值：综合分 ≥70 才可标 Ready to Publish。
