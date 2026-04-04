🤝 Contributing to the Looped Operations Wiki

Thank you for helping improve the Looped Operations Wiki.

This documentation is designed to be simple to maintain, meaning contributors only need to edit or create Markdown files — no HTML or complex setup required.

---

✍️ How to Contribute

➕ Adding a New Page

1. Navigate to:

/pages/

2. Create a new ".md" file
   Example:

startup.md
cooling-system.md
emergency-scram.md

3. Add the required frontmatter at the top:

---
title: Page Title
layout: wiki
nav_group: guides
nav_order: 1
---

---

✏️ Editing a Page

Simply open any ".md" file inside "/pages/" and edit the content.

No additional configuration is required — changes will automatically appear on the site.

---

🧭 Navigation System

Pages are automatically added to the sidebar using:

"nav_group"

Controls which section the page appears in:

- "general"
- "guides"
- "emergency"
- "systems"
- "maintenance"

"nav_order"

Controls ordering within that section:

nav_order: 1

---

⚠️ Adding Warnings, Notes & Tips

Use Markdown blockquotes with emojis for consistency:

⚠️ Warning

> ⚠️ **Warning**  
> Reactor instability may occur if limits are exceeded.

🚨 Critical

> 🚨 **Critical**  
> Immediate action required to prevent system failure.

ℹ️ Note

> ℹ️ **Note**  
> This system operates automatically under normal conditions.

💡 Tip

> 💡 **Tip**  
> Monitor temperature trends rather than single values.

---

🖼️ Adding Images

1. Place images in:

/assets/images/

2. Reference them in Markdown:

![Control Panel](/assets/images/control-panel.png)

---

📏 Image Tips

- Use clear, high-resolution images
- Prefer screenshots of actual systems
- Keep file names simple:

reactor-panel.png
scram-button.png

---

🧱 Writing Guidelines

To keep the wiki consistent:

- Use clear section headings ("##", "###")
- Keep paragraphs short and readable
- Use bullet points where possible
- Write in a professional, procedural tone

---

🧠 Style Example

## Startup Procedure

Follow these steps to safely bring the reactor online:

1. Verify coolant flow
2. Enable control systems
3. Gradually raise reactor power

> ⚠️ **Warning**  
> Rapid power increases may cause instability.

---

🚧 Work in Progress Pages

If a page is incomplete, include:

> ⚠️ **Work in Progress**  
> This page is currently under development.

---

✅ That’s It

There’s no need to edit layouts, HTML, or navigation manually.

Just:

- Create or edit a page
- Add frontmatter
- Write your content

The system will handle the rest automatically.

---

👷 Final Note

«“There is no such thing as a small anomaly.”»

Accuracy and clarity are critical — document carefully.