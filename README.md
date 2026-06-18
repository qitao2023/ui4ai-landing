# 🎨 UI4AI — Design UIs, Export to AI Prompts

**The visual editor that bridges UI design and AI code generation.**

<p align="center">
  <a href="https://qitao2023.github.io/ui4ai-landing/">
    <strong>🌐 Landing Page → qitao2023.github.io/ui4ai-landing/</strong>
  </a>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="https://ui4ai.vercel.app">
    <strong>🚀 Open App → ui4ai.vercel.app</strong>
  </a>
</p>

![](https://img.shields.io/badge/status-live-brightgreen)
![](https://img.shields.io/badge/license-proprietary-red)
![](https://img.shields.io/badge/stack-React%2019%20%7C%20TypeScript%20%7C%20Tailwind%204%20%7C%20Express%205-blue)

---

## What is UI4AI?

UI4AI is a **drag-and-drop UI designer** that exports your designs as **structured JSON with framework-specific instructions** — ready to be fed into AI coding tools like Claude, ChatGPT, Cursor, Copilot, and others.

Instead of describing your UI in prose ("put a login button on the left, then a signup link..."), you visually assemble it, pick a target framework, and get a **machine-readable prompt** with pre-computed CSS that AI tools execute precisely.

---

## ✨ Features

### Controls — 17 types across 3 categories

| Basic | Containers | Data |
|-------|-----------|------|
| Label, Input, Button | Card (nestable) | Table (select/button cells) |
| Select, Checkbox, Radio | CondGroup (conditional branches) | Tree (checkable) |
| Toggle, Textarea, Image | Tabs (tab panels) | |
| Divider, OptionList | Modal (overlay) | |

### Core Capabilities

- **Visual Canvas** — Drag, resize, and position controls with pixel precision
- **Framework-Aware Export** — Choose HTML / React / Vue. Export includes pre-computed CSS styles, smart descriptions, and framework-specific rendering instructions
- **Multi-page Support** — Design full application flows across multiple screens
- **Property Editor** — Configure colors, borders, text, placeholders, and behavior for each control
- **Device Preview** — Switch between mobile (375px), tablet (768px), desktop (1024px), and fullscreen views

### Editing & Productivity

- **Format Painter** — Copy styles between controls instantly
- **Alignment Tools** — Align left, center, right, top, middle, bottom across multiple selections
- **Match Size** — Match width, height, or both across selected controls
- **Distribute** — Evenly space controls horizontally or vertically
- **Layer Panel** — Indented hierarchy view with right-click context menu, lock/unlock, visibility toggle, and drag reorder
- **Keyboard Shortcuts** — Fast operations for power users
- **English & 中文** — Full bilingual UI with one-click switch

### Import & Data

- **GDS Import** — Import from GUI Design Studio XML files. Maps 50+ element types, preserves column widths, row heights, and container nesting
- **Clipboard Table Parsing** — Paste tabular data from Excel, Google Sheets, or web pages — auto-creates a styled table control
- **Save / Load** — Export designs as `.json` files and share with your team

### Conditional Logic

- **CondGroup** — Conditional container with named branches. Triggered by select, radio, or table cell values
- **Button Actions** — goToPage, openModal, alert, clearCell
- **Table Row Visibility** — Show/hide/gray-out table rows based on dropdown selection

---

## 🚀 How It Works

```
1. Drag controls onto the canvas (17 types to choose from)
          ↓
2. Arrange & style them visually (align, distribute, format-paint)
          ↓
3. Pick target framework (HTML / React / Vue)
          ↓
4. Copy JSON + instructions → paste into Claude, GPT, or Cursor
          ↓
5. AI generates working code — no manual prompt tweaking needed
```

---

## 💰 Pricing

| Plan | Price | What You Get |
|------|-------|---------------|
| **Free** | $0 | All 17 controls, all 3 frameworks, 1 page, watermarked JSON export |
| **Pro** | $7.99/mo or $59.99/yr | Everything in Free + unlimited pages, no watermark, priority support |

👉 **[Upgrade to Pro](https://qitao.gumroad.com/l/ui4ai-monthly)** — or go **[annual](https://qitao.gumroad.com/l/ui4ai-annual)** and save 37%.

---

## 🛠 Built With

- **React 19** + **TypeScript**
- **Tailwind CSS 4**
- **dnd-kit** (drag & drop)
- **Zustand** (state management)
- **Vite** (build tool)
- **Express 5** (desktop server)
- **PWA** (installable web app)

---

## 📬 Feedback & Issues

Found a bug? Have a feature request? **[Open an issue](../../issues)** in this repo.

For license key support or billing questions, reach out via [Gumroad](https://qitao.gumroad.com).

---

## 🔒 Source Code

UI4AI is **source-available with a proprietary license**. The source code is hosted in a private repository. If you're interested in contributing or licensing the code, please contact the maintainer.

---

<p align="center">
  <b>UI4AI</b> — Make your AI understand UI design.
</p>
