# EasyPaste 盘点对比文 SEO 技术审计报告
> 审计人：欧化成（SEO 优化师）｜日期：2026-07-24
> 审计对象：`drafts/mac-clipboard-manager-recommend-zh-2026-07-24.md`（中文）、`drafts/best-clipboard-manager-mac-en-2026-07-24.md`（英文）
> 文章类型：商业调研型「选工具」Hub 文，与信息型 Pillar《终极指南》互补
> 主关键词：中文 `Mac 剪贴板管理器推荐`｜英文 `best clipboard manager mac`

---

## 总览结论（先说重点）

| 篇目 | 总评分 | 核心结论 | 发布状态 |
|------|------|---------|---------|
| 中文 | **73 / 100** | 关键词密度健康、内容扎实；缺主词入 H2、JSON-LD 未加、slug 缺 `.html` | Needs Minor Fixes |
| 英文 | **70 / 100** | **主词精确密度严重偏低（~0.04%）**、H2 无主词、slug 与中文不一致 | Needs Revision（关键词项必修） |

**两篇共同必修项（发布前）**：① 主词写入 2 个 H2 标题；② 补 `Article`+`BreadcrumbList`+`FAQPage` 三套 JSON-LD；③ 中文 slug 统一加 `.html`；④ 互设 hreflang；⑤ 统一本品称谓为「EasyPaste（macOS 剪贴板管理器）」并链官网；⑥ 入 sitemap。
**英文额外必修**：主词精确密度从 ~0.04% 提升到 1%+（加 4–6 处精确短语）。

---

# 模块一：中文文章审计

## 1.1 SEO 评分（0–100）及维度分

| 维度 | 权重 | 得分 | 扣分原因 |
|------|------|------|---------|
| 关键词布局 | 15 | **12** | H1✓、前 100 词✓、密度 1.49%✓；但 **0/8 个 H2 标题含主词**，结论段无精确主词 |
| 内容深度/覆盖 | 15 | **14** | 10 工具 + 7 维度 + 对比表 + 场景匹配 + 8 FAQ + ~4025 字；仅可补「用户评价/更新频率」 |
| 结构（H1/H2/H3） | 15 | **14** | 单 H1、层级清晰无跳级、TL;DR 表好；H2 主词缺失略拖 |
| 元标签 | 15 | **11** | 标题 31 字（≈510px）达标但偏长；描述 ~98 字达标但 CTA 弱；**slug 缺 `.html`，与全站约定不一致** |
| 内链 | 10 | **9** | 5 条上下文内链（指南/教程/内置历史/maccy-vs-paste/官网），锚文本自然；可再补 1 条集群 |
| 外链权威 | 10 | **8** | 3 条权威外链（pasteapp.io、maccy.app、raycast.com）；**缺 Alfred（alfredapp.com）、Yoink** |
| 结构化数据 | 10 | **0** | 草稿未含任何 JSON-LD，需补 Article+Breadcrumb+FAQ |
| 移动/技术基线 | 10 | **5** | 草稿不可验证；需 og-image 引用、alt、lazyload、canonical、hreflang 落地 |
| **合计** | **100** | **73** | |

## 1.2 关键词分布热图（主词 `Mac 剪贴板管理器推荐`）

```
H1                          ✓  行 1
前 100 词                    ✓  行 5（加粗）
H2 标题(共 8 个)             ✗  0/8（但「我们的评选维度」段正文行 38、「按场景选哪款」段正文行 153 含主词）
正文密度                     ✓  5 次 / ~4025 字 ≈ 1.49%（落在 1–2% 健康区，无堆砌）
结论(行 205–212)            ✗  精确主词未出现（行 209 用「EasyPaste（macOS 剪贴板管理器）」代述）
Meta Title / Description     ✓  均含主词
```

**次关键词覆盖**：`剪贴板管理器`（高频✓）、`Mac 剪贴板`（变体✓）、`iCloud 同步`（高频✓）、`免费剪贴板工具`（正文以「免费又轻量的 EasyPaste」表述，精确短语偏弱，建议补 1–2 处「免费剪贴板工具」）。

## 1.3 Meta 标题备选（中文：按 CJK 宽度计，目标 ~20–32 字≈≤600px；关键词前置、含年份/差异化）

> 注：团队要求「50–60 字符」是 Latin 规则；中文每字≈16px，31 字已≈510px，再长会被 Google 截断。现标题 31 字不截断，但建议精简到 24–28 字更稳。

| # | 备选 | 字数 | 说明 |
|---|------|------|------|
| 现有 | Mac 剪贴板管理器推荐（2026）：10 款主流工具横向对比 | 31 | 达标但偏长 |
| 1 | Mac 剪贴板管理器推荐 2026：10 款横评与选购指南 | 28 | 主词前置、含年、「横评+选购指南」差异化 |
| 2 | Mac 剪贴板管理器推荐：2026 年 10 款工具实测对比 | 27 | 主词前置、含年、「实测」增强信任 |
| 3 | 10 款 Mac 剪贴板管理器推荐（2026）横向评测 | 25 | 主词前置、含年 |
| 4 | Mac 剪贴板管理器推荐 2026：哪款最适合你？ | 24 | 主词前置、疑问句式提 CTR |
| 5 | 2026 Mac 剪贴板管理器推荐：免费/付费 10 款对比 | 27 | 年前置、主词紧随 |

**推荐 #1 或 #2**：主词最前置、含 2026、且「横评/实测/选购指南」给出差异化钩子。

## 1.4 Meta 描述备选（中文：目标 90–110 字；前 60 字含核心词 + 全文含 CTA）

| # | 备选 | 字数 | 说明 |
|---|------|------|------|
| 现有 | 2026 年最实用的 Mac 剪贴板管理器推荐清单，横向对比 Paste、Maccy、Raycast、Alfred、EasyPaste 等 10 款工具，按场景帮你选对那一款，免费又轻量的 EasyPaste 值得一试。 | ~98 | 达标，CTA 偏弱 |
| 1 | 想告别「复制就丢」？这份 2026 Mac 剪贴板管理器推荐横评覆盖 10 款工具，教你按预算和场景选对。免费、轻量、带 iCloud 同步的 EasyPaste 值得一试，马上免费下载。 | ~96 | 前 18 字含主词，结尾强 CTA「马上免费下载」 |
| 2 | Mac 剪贴板管理器推荐 2026：我们实测 10 款主流工具（Paste/Maccy/Raycast/Alfred/EasyPaste），从免费开源到付费订阅，按你的场景选对那一款。免费轻量的 EasyPaste 点此下载。 | ~100 | 主词前置、列工具名、CTA 明确 |
| 3 | 2026 年最全 Mac 剪贴板管理器推荐：横向对比 10 款工具的历史深度、搜索、iCloud 同步与价格，帮你按场景一步选对。免费又轻量的 EasyPaste 支持 iCloud 同步，点此免费下载。 | ~102 | 突出对比维度、CTA |
| 4 | 还在为「复制就丢」头疼？2026 Mac 剪贴板管理器推荐清单来了：横评 Paste、Maccy、Raycast 等 10 款，按场景教你选对。免费又轻量的 EasyPaste 立即下载。 | ~94 | 痛点开头、CTA 强 |

**推荐 #1**：前 60 字内出现主词 + 痛点钩子，结尾「马上免费下载」CTA 明确，长度合规。

## 1.5 结构化数据 / Schema 建议 → 见模块四（中英文各一套）

## 1.6 精选摘要（Featured Snippet）捕获建议

优先抢「People Also Ask」与精选摘要的区块：

1. **TL;DR 总表（行 52–64）**：已是表格，适合「table」型精选摘要。建议在表前加一句直接定义句：「下面是我们对 10 款 Mac 剪贴板管理器的横向评分总览」。
2. **一句话结论（行 65）**：「预算足要好看选 Paste，要免费要隐私选 Maccy，要免费又要同步选 EasyPaste」→ 改写为**有序清单**更易被抽取：
   `1. 综合最佳：Paste（精致界面 + iCloud 同步）｜2. 最佳免费：Maccy（开源、本地隐私）｜3. 最佳免费+同步：EasyPaste（iCloud 同步）`
3. **7 个评选维度（行 40–46）**：天然「list」型片段，回答「如何选剪贴板管理器」。建议在列表前加引导句：「挑选 Mac 剪贴板管理器，重点看这 7 个维度：」。
4. **按场景选（行 155–159）**：适合「best clipboard manager for X」类片段。建议每条用「**程序员**：首选 Maccy、Flycut…」格式，便于抽取。
5. **FAQ（行 179–203）**：已 8 问，直接结构化 `FAQPage`（见模块四），抢 FAQ 富媒体结果与 PAA 直引。

## 1.7 发布前必修清单（中文）

见模块五跨语言清单（含 hreflang / canonical / og-image / alt / lazyload 等逐条 ✓/✗）。

---

# 模块二：英文文章审计

## 2.1 SEO 评分（0–100）及维度分

| 维度 | 权重 | 得分 | 扣分原因 |
|------|------|------|---------|
| 关键词布局 | 15 | **9** | **主词精确 `best clipboard manager mac` 正文中仅 1 次（~0.04%，远低于 1–2%）**；0/8 H2 含主词；H1 为近义变体；长尾/LSI（best free / free / maccy vs paste / raycast clipboard）丰富但主词薄弱 |
| 内容深度/覆盖 | 15 | **13** | ~2950 词，结构完整，较中文略浅 |
| 结构（H1/H2/H3） | 15 | **14** | 单 H1、层级清晰、TL;DR 表好 |
| 元标签 | 15 | **12** | 标题 57 字符优秀；描述 ~152 字符（达标下限，CTA 可更强）；**slug 带 `.html` 但与中文不一致** |
| 内链 | 10 | **9** | 5 条（`/en/blog/...`、`/en/`），锚文本自然 |
| 外链权威 | 10 | **8** | 3 条权威外链；缺 Alfred、Yoink |
| 结构化数据 | 10 | **0** | 未实现 |
| 移动/技术基线 | 10 | **5** | 同中文，草稿不可验证 |
| **合计** | **100** | **70** | |

## 2.2 关键词分布热图（主词 `best clipboard manager mac`）

```
H1                          ~✓  行 1「Best Clipboard Managers for Mac 2026」为近义变体（Managers 复数 + for Mac）
前 100 词                    ✓  行 5（加粗精确 "the best clipboard manager mac options"）
H2 标题(共 8 个)             ✗  0/8（Why You Need / How We Picked / Quick Comparison / In-Depth Reviews / Best for Your Use Case / Why EasyPaste / FAQ / Conclusion 均无主词）
正文密度                     ✗  精确仅 1 次 / ~2950 词 ≈ 0.04%；含 free/for 变体共 8 次（best free clipboard manager mac ×2、free clipboard manager mac ×3、best clipboard managers for mac ×1 等）
结论(行 207–213)            ~✓  行 209「best clipboard managers for mac in 2026」近义变体
Meta Title / Description     ✓  标题含近义；描述含「best clipboard managers for Mac」
```

**风险判定**：该词难度 High（估算 1,000–4,000/月），精确密度 0.04% 意味着 Google 几乎无法从正文确认页面主题。这是英文篇**头号硬伤**，必须补 4–6 处精确短语（含 2 个 H2 + 结论 + TL;DR 引导句 + 评审段）。

## 2.3 Meta 标题备选（英文：50–60 字符，关键词前置、含年份/差异化）

| # | 备选 | 字符 | 说明 |
|---|------|------|------|
| 现有 | Best Clipboard Managers for Mac 2026: Free & Paid Compared | 57 | 优秀，但含近义复数 |
| 1 | Best Clipboard Manager Mac 2026: 10 Tools Tested & Ranked | 56 | **含精确主词** +「10 Tools Tested & Ranked」差异化 |
| 2 | Best Clipboard Manager for Mac 2026: Free vs Paid Compared | 56 | 精确主词、Free vs Paid 钩子 |
| 3 | 10 Best Clipboard Managers for Mac 2026 (Free & Paid) | 52 | 数字+年+免费/付费 |
| 4 | Best Clipboard Manager Mac 2026: Our Top Picks Compared | 55 | 精确主词 + Top Picks |
| 5 | Best Clipboard Managers for Mac 2026: Compared & Ranked | 55 | 近义保原风格 |

**推荐 #1**：唯一同时含精确主词 `Best Clipboard Manager Mac` 且 56 字符合规，最利于主词排名。

## 2.4 Meta 描述备选（英文：150–160 字符，前 60 字含核心词 + CTA）

| # | 备选 | 字符 | 说明 |
|---|------|------|------|
| 现有 | We tested the best clipboard managers for Mac in 2026 — Paste, Maccy, Raycast, Alfred & more. Find the right free or paid tool for your Mac workflow today. | ~152 | 达标下限，CTA 一般 |
| 1 | We tested the best clipboard manager mac in 2026 — Paste, Maccy, Raycast, Alfred & more. Compare free vs paid and pick the right tool for your Mac workflow. | 156 | **含精确主词**，对比钩子 |
| 2 | We tested the best clipboard manager for Mac in 2026 — Paste, Maccy, Raycast & more. Compare free vs paid and find the right tool for your workflow. | 157 | 近义、流畅 |
| 3 | Looking for the best clipboard manager mac in 2026? We compared 10 tools (Paste, Maccy, Raycast, Alfred) so you can pick the right free or paid one. | 154 | 问句钩子 + 精确主词 |
| 4 | The best clipboard manager mac roundup for 2026: we tested Paste, Maccy, Raycast, Alfred & more to help you choose the right free or paid tool. | 158 | 精确主词前置 |

**推荐 #1**：含精确主词、152→156 留余量、CTA「pick the right tool」清晰。

## 2.5 结构化数据 / Schema 建议 → 见模块四

## 2.6 精选摘要捕获建议

同中文逻辑，对应英文区块：
1. **TL;DR 表（行 55–66）**：表前加定义句「Here is the quick comparison of the best clipboard manager mac picks for 2026.」
2. **一句话结论（行 66 下）**：改写为有序清单 `1. Best overall: Paste｜2. Best free: Maccy｜3. Best free + sync: EasyPaste`。
3. **7 维度（行 41–47）**：列表前加「To pick the best clipboard manager for Mac, compare these 7 factors:」。
4. **Use Case（行 158–162）**：用 `**Developers** → Maccy or Flycut…` 格式。
5. **FAQ（行 183–205）**：结构化 `FAQPage`。

## 2.7 发布前必修清单（英文）→ 见模块五

---

# 模块三：双语一致性 & 品牌风险（两篇合并指出）

1. **Slug 一致性（必修）**：中文草稿 `URL Slug: /blog/mac-clipboard-manager-recommend`（无 `.html`），英文 `URL Slug: /en/blog/best-clipboard-manager-mac.html`。全站策略（SEO-STRATEGY-BILINGUAL §3、§4）博客 URL 一律带 `.html`（如 `/blog/mac-clipboard-manager-guide.html`）。**中文 slug 须改为 `/blog/mac-clipboard-manager-recommend.html`**，否则双语 URL 约定撕裂、内部链接（文内已用 `/blog/...html`）会 404。
2. **Hreflang 互链（必修）**：两篇为互译，须各自 `<head>` 互设：
   ```
   <link rel="alternate" hreflang="zh-CN" href="https://DOMAIN/blog/mac-clipboard-manager-recommend.html" />
   <link rel="alternate" hreflang="en"    href="https://DOMAIN/en/blog/best-clipboard-manager-mac.html" />
   <link rel="alternate" hreflang="x-default" href="https://DOMAIN/blog/mac-clipboard-manager-recommend.html" />
   ```
3. **品牌称谓统一（必修，防混淆）**：
   - 指令要求正文本品统一称「**EasyPaste（macOS 剪贴板管理器）**」并链官网，避免与 App Store「EasyPaste 快易贴」、GitHub 同名项目混淆。
   - **中文**：行 63 表格单元格 `EasyPaste（本品）`、行 143 H3 `### 10. EasyPaste（本品）` 两处用「（本品）」，**须改为「（macOS 剪贴板管理器）」**；表格单元格与首次品牌提及建议链官网 `/`。
   - **英文**：行 66 表格 `EasyPaste`（无描述、无链）、行 142 H3 `### 10. EasyPaste — Free, Light, and Synced`（无描述）、行 205 段落无描述，**须补 `(the free macOS clipboard manager)` 并链 `/en/`**。
4. **Canonical（待自定义域）**：当前 canonical 指向 `vercel.app` 子域；自定义域（建议 `easypaste.app`）上线后全站 301 + 更新 canonical 至自定义域。
5. **Sitemap（必修）**：`sitemap.xml` 须扩充这两条双语 URL 并标注 hreflang（策略 §1.2、§8）。

---

# 模块四：结构化数据 / Schema 建议

三篇文章级 JSON-LD：**`Article` + `BreadcrumbList` + `FAQPage`**（文章已含 8 个 FAQ，可直接结构化）。部署位置：`<body>` 顶部或底部 `<script type="application/ld+json">`，`DOMAIN` 上线后替换为自定义域。

## 4.1 中文（zh-CN）

### Article
```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Mac 剪贴板管理器推荐（2026）：10 款主流工具横向对比",
  "description": "2026 年最实用的 Mac 剪贴板管理器推荐清单，横向对比 Paste、Maccy、Raycast、Alfred、EasyPaste 等 10 款工具，按场景帮你选对那一款。",
  "author": { "@type": "Organization", "name": "EasyPaste" },
  "publisher": {
    "@type": "Organization",
    "name": "EasyPaste",
    "logo": { "@type": "ImageObject", "url": "https://DOMAIN/og-image.png" }
  },
  "datePublished": "2026-07-24",
  "dateModified": "2026-07-24",
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://DOMAIN/blog/mac-clipboard-manager-recommend.html" },
  "image": "https://DOMAIN/og-image.png",
  "inLanguage": "zh-CN"
}
```

### BreadcrumbList
```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    { "@type": "ListItem", "position": 1, "name": "首页", "item": "https://DOMAIN/" },
    { "@type": "ListItem", "position": 2, "name": "博客", "item": "https://DOMAIN/blog/" },
    { "@type": "ListItem", "position": 3, "name": "Mac 剪贴板管理器推荐", "item": "https://DOMAIN/blog/mac-clipboard-manager-recommend.html" }
  ]
}
```

### FAQPage（8 问，问题与文章一致）
```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    { "@type": "Question", "name": "macOS 自带的剪贴板历史怎么开启？", "acceptedAnswer": { "@type": "Answer", "text": "在 macOS Tahoe（26 版）中，先按 Command+空格打开聚焦，再按 Command+4 即可查看最近复制记录；更早版本需装第三方工具。" } },
    { "@type": "Question", "name": "剪贴板管理器安全吗？密码会被记录吗？", "acceptedAnswer": { "@type": "Answer", "text": "正规工具只把数据存在本地或你自己的 iCloud，不上传厂商服务器；多数支持把密码管理器、银行网页加入黑名单应用，敏感内容不会被记录。" } },
    { "@type": "Question", "name": "免费的剪贴板管理器够用吗？", "acceptedAnswer": { "@type": "Answer", "text": "对大多数人够用。Maccy、Clipy、Flycut 等开源免费工具已覆盖文本、图片、搜索等核心需求，EasyPaste 还额外提供 iCloud 同步。" } },
    { "@type": "Question", "name": "Maccy 和 Paste 哪个更好？", "acceptedAnswer": { "@type": "Answer", "text": "要免费、隐私、速度选 Maccy；要精致时间线界面、跨设备 iCloud 同步且愿意年付选 Paste。两者定位不同，并非直接竞品。" } },
    { "@type": "Question", "name": "哪款支持 iPhone / iPad 同步？", "acceptedAnswer": { "@type": "Answer", "text": "带 iCloud 同步的 Paste 与 EasyPaste 支持苹果设备接力；Unclutter 仅便签/文件经 Dropbox 同步；其余多仅限 Mac 本地。" } },
    { "@type": "Question", "name": "剪贴板管理器会拖慢 Mac 吗？", "acceptedAnswer": { "@type": "Answer", "text": "轻量工具（Maccy、EasyPaste、Flycut）常驻内存极小几乎无感；Paste、Raycast 在老设备占用略高但日常影响很小。" } },
    { "@type": "Question", "name": "Raycast / Alfred 的剪贴板够用吗，还要单独装吗？", "acceptedAnswer": { "@type": "Answer", "text": "若本就是其重度用户，自带剪贴板通常够用；若只偶尔启动应用，其剪贴板受限（免费版有保留时长、同步需付费），单独装专用工具更纯粹。" } },
    { "@type": "Question", "name": "EasyPaste 适合哪些人？", "acceptedAnswer": { "@type": "Answer", "text": "不想花钱又想要历史记录、全局搜索、iCloud 同步与全局快捷键的人，尤其办公族、学生、轻度创作者及多设备苹果用户。" } }
  ]
}
```

## 4.2 英文（en）

### Article
```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Best Clipboard Managers for Mac 2026: Free & Paid Compared",
  "description": "We tested the best clipboard manager mac options for 2026 — Paste, Maccy, Raycast, Alfred and more. Find the right free or paid tool for your workflow.",
  "author": { "@type": "Organization", "name": "EasyPaste" },
  "publisher": {
    "@type": "Organization",
    "name": "EasyPaste",
    "logo": { "@type": "ImageObject", "url": "https://DOMAIN/og-image.png" }
  },
  "datePublished": "2026-07-24",
  "dateModified": "2026-07-24",
  "mainEntityOfPage": { "@type": "WebPage", "@id": "https://DOMAIN/en/blog/best-clipboard-manager-mac.html" },
  "image": "https://DOMAIN/og-image.png",
  "inLanguage": "en"
}
```

### BreadcrumbList
```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    { "@type": "ListItem", "position": 1, "name": "Home", "item": "https://DOMAIN/en/" },
    { "@type": "ListItem", "position": 2, "name": "Blog", "item": "https://DOMAIN/en/blog/" },
    { "@type": "ListItem", "position": 3, "name": "Best Clipboard Manager for Mac", "item": "https://DOMAIN/en/blog/best-clipboard-manager-mac.html" }
  ]
}
```

### FAQPage（8 问，问题与文章一致）
```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    { "@type": "Question", "name": "How do I enable the built-in Mac clipboard history?", "acceptedAnswer": { "@type": "Answer", "text": "On macOS 26 Tahoe or later, open Spotlight with Cmd+Space, then press Cmd+4 (hold Command). Adjust retention (8 hours–7 days) in System Settings → Spotlight." } },
    { "@type": "Question", "name": "Are clipboard managers safe? Do they log passwords?", "acceptedAnswer": { "@type": "Answer", "text": "Reputable managers store history locally and let you exclude sensitive apps like banking and password managers. Prefer local-first apps such as Maccy or EasyPaste." } },
    { "@type": "Question", "name": "Is a free clipboard manager enough?", "acceptedAnswer": { "@type": "Answer", "text": "For most people, yes. Maccy and EasyPaste prove you don't need to pay for fast search, history, and even iCloud sync." } },
    { "@type": "Question", "name": "Maccy vs Paste — which is better?", "acceptedAnswer": { "@type": "Answer", "text": "Maccy wins on price, speed, and privacy (local-only). Paste wins on design, iCloud sync, images, and OCR. Pick Maccy if you skip sync; Paste for the prettiest synced experience." } },
    { "@type": "Question", "name": "Which clipboard managers support iPhone/iPad sync?", "acceptedAnswer": { "@type": "Answer", "text": "Paste and EasyPaste sync across Mac, iPhone, and iPad via iCloud. The built-in Tahoe history, Maccy, Raycast, and Alfred do not sync clipboard to mobile." } },
    { "@type": "Question", "name": "Do clipboard managers slow down my Mac?", "acceptedAnswer": { "@type": "Answer", "text": "Lightweight ones don't. Maccy, Flycut, and EasyPaste use minimal memory. Heavier apps like Paste use more resources but the impact is small on modern Macs." } },
    { "@type": "Question", "name": "Is Raycast's or Alfred's clipboard enough, or do I need a separate one?", "acceptedAnswer": { "@type": "Answer", "text": "If you already use them daily, their built-in clipboard is probably enough. A separate app helps if you don't use a launcher, want a lighter footprint, or need mobile sync." } },
    { "@type": "Question", "name": "Who is EasyPaste for?", "acceptedAnswer": { "@type": "Answer", "text": "Anyone who wants a real, synced clipboard manager without paying or bloating their Mac: students, developers, designers, writers, and Apple multi-device users." } }
  ]
}
```

---

# 模块五：发布前必修清单（逐条 ✓/✗）

| # | 检查项 | 中文 | 英文 | 说明 / 修复 |
|---|--------|------|------|------------|
| 1 | 主词在 H1 | ✓ | ~✓ | 英文为近义变体，建议标题改用精确主词（见 2.3 #1） |
| 2 | 主词在前 100 词 | ✓ | ✓ | 均已加粗出现 |
| 3 | 主词在 ≥2 个 H2 | ✗ | ✗ | **必修**：中文改 2 个 H2（如「Mac 剪贴板管理器推荐总榜速览（TL;DR）」「按场景选 Mac 剪贴板管理器」）；英文改 2 个（如「Best Clipboard Manager Mac: Quick Comparison (TL;DR)」「Best Clipboard Manager Mac for Your Use Case」） |
| 4 | 主词密度 1–2% | ✓(1.49%) | ✗(~0.04%) | **英文必修**：再补 4–6 处精确 `best clipboard manager mac`（TL;DR 引导句、评审段、结论、Use Case 段） |
| 5 | 3–5 条内链（优质锚文本） | ✓(5) | ✓(5) | 达标 |
| 6 | 2–3 条权威外链 | ✓(3) | ✓(3) | 达标；建议补 Alfred、Yoink 官网 |
| 7 | Meta Title 50–60 字符（中文按 CJK≤~32 字） | ~✓(31字≈510px) | ✓(57) | 中文偏长，建议精简至 24–28 字（见 1.3） |
| 8 | Meta Description 150–160（中文 90–110 字） | ✓(~98) | ~✓(~152 下限) | 英文建议微调至 155+（见 2.4 #1） |
| 9 | 正文 ≥2000 词 | ✓(4025) | ✓(2950) | 达标 |
| 10 | H1/H2/H3 层级正确 | ✓ | ✓ | 无跳级 |
| 11 | 可读性 8–10 年级 | ✓ | ✓ | 通俗流畅 |
| 12 | 结论含明确 CTA | ✓ | ✓ | 均链官网下载 |
| 13 | 无断链 | ✓(待实测) | ✓(待实测) | 上线后 crawl 验证 |
| 14 | 移动端友好 | ⚠(待实测) | ⚠(待实测) | Vercel 静态页基础好，需实测 CWV |
| 15 | JSON-LD（Article+Breadcrumb+FAQ） | ✗ | ✗ | **必修**：按模块四部署 |
| 16 | hreflang 互链（zh/en/x-default） | ✗ | ✗ | **必修**：见模块三 §2 |
| 17 | canonical | ⚠(vercel.app) | ⚠(vercel.app) | 自定义域上线后改 |
| 18 | og:image 1200×630 | ⚠(文件已生成) | ⚠(文件已生成) | 文章页 `<head>` 须引用正确 `og-image.png` |
| 19 | 图片 alt（含关键词） | ⚠(草稿无图) | ⚠(草稿无图) | 若加截图，alt 须含 `Mac 剪贴板管理器` / `clipboard manager mac` |
| 20 | 图片懒加载 `loading="lazy"` | ✗ | ✗ | 用图时加 |
| 21 | **slug 一致性（带 `.html`）** | ✗ | ✓ | **中文必修**：`/blog/mac-clipboard-manager-recommend` → 加 `.html` |
| 22 | **品牌称谓统一** | ✗ | ✗ | **必修**：中文 2 处「（本品）」→「（macOS 剪贴板管理器）」并链官网；英文 H3/表/段落补描述并链 `/en/` |
| 23 | sitemap 扩充双语 URL + hreflang | ✗ | ✗ | **必修**：加入两条 URL |

---

## 发布建议（汇总）

- **中文篇**：`Needs Minor Fixes`。修复清单 #3、#15、#16、#21、#22、#23 后即可发布；#7、#8 为优化项。
- **英文篇**：`Needs Revision`。**#4（主词密度）为硬伤必须先修**，连同 #3、#15、#16、#22、#23 修复后发布；#1、#8 为优化项。
- **预估修复时间**：中文 ~40 分钟（含 JSON-LD 部署与文案微调）；英文 ~60 分钟（主词补密度 + H2 改写 + JSON-LD）。若仅做「必修项」不重写，两篇合计约 1.5–2 小时。
- **优先级**：P0 = #3/#4（关键词）、#15（结构化数据，抢 FAQ 富结果）、#16/#21/#22/#23（双语架构与品牌，避免混淆与 404）；P1 = #7/#8（元标签打磨）、#6（补外链）。
