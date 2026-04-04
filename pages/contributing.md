---
layout: wiki
nav_order: 2
permalink: /pages/contributing/
nav_group: guides
title: Contributing to the wiki
hero_image: /assets/images/control-room-banner.jpg
hero_title: Contributing to the wiki
hero_subtitle: Guide on how to add pages to the wiki 
status: reviewed
---

# Contributing to the Looped Operations Wiki

## Overview

The Looped Operations Wiki is designed to be simple to maintain.  
In most cases, contributors only need to create or edit Markdown pages
inside the `pages` folder.

---

## 📄 Full Template


```md
---
title: Page Title
layout: wiki
permalink: /pages/page-title/
nav_group: general
nav_order: 1
status: draft
---

## Overview

Write a short explanation of what this page covers.

## Main Section

Add your content here.

> ⚠️ **Warning**  
> Example warning text

> ℹ️ **Note**  
> Example note text

> 💡 **Tip**  
> Example tip text

## Related Pages

- [Example Link](/pages/example/)
```

---


## ✅ Example Page (Rendered)

## Overview

This page explains an example system.

## Main Section

Content goes here.

> ⚠️ **Warning**  
> Do not exceed safe limits

> ℹ️ **Note**  
> This system runs automatically

> 💡 **Tip**  
> Monitor trends, not single values

---

## 📁 Where to add pages

Place all pages in:

```text
/pages/
```

---

## 🧭 Navigation Groups

Use one of:

- general
- guides
- emergency
- maintenance
- systems
- reactor

---

## 🖼️ Adding Images

Place images in:

```text
/assets/images/
```

Use them like:

```md
![Example](/assets/images/example.png)
```

---

## 🎬 Hero Banner (Optional)

Add to frontmatter:

```yaml
hero_image: /assets/images/example.jpg
hero_title: Page Title
hero_subtitle: Optional subtitle
```

---

## ⚙️ Hiding Pages

To hide a page from sidebar:

```yaml
nav_hidden: true
```

---

## ✍️ Writing Guidelines

- Keep it clear and structured
- Use headings and lists
- Keep tone professional
- Link related pages

---

## 🚀 Quick Workflow

1. Create/edit page
2. Add frontmatter
3. Write content
4. Commit + push

---

## 📌 Final Note

> ℹ️ **Note**  
> Keep pages simple, clear, and consistent.