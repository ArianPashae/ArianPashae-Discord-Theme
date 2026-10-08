<div align="center">

<img src="assets/logo.svg" width="96" height="96" alt="ArianPashae Logo" />

# ArianPashae Discord Theme

**A modern cyber-violet & obsidian UI theme for Discord (Vencord & BetterDiscord), crafted by [ArianPashae](https://github.com/ArianPashae).**

[![Version](https://img.shields.io/badge/Version-2.0.0-a855f7?style=for-the-badge)](https://github.com/ArianPashae/ArianPashae-Discord-Theme)
[![Author](https://img.shields.io/badge/Author-ArianPashae-d8b4fe?style=for-the-badge)](https://github.com/ArianPashae)
[![Website](https://img.shields.io/badge/Website-arianpashae.com-6366f1?style=for-the-badge)](https://arianpashae.com)
[![License](https://img.shields.io/badge/License-MIT-14141b?style=for-the-badge)](LICENSE)

</div>

---

## Preview

![ArianPashae Discord Theme Preview](assets/preview.png)

---

## Key Features

- **100% Self-Contained Vector Branding**: Includes an embedded SVG `AP` hexagon emblem on the Home button and a gradient `ARIANPASHAE` titlebar badge with zero external image dependencies.
- **Obsidian & Cyber-Violet Palette**: Engineered around deep obsidian surfaces (`#14141b` / `#1f1f2b`) paired with electric violet (`#a855f7`) and soft lavender (`#d8b4fe`) accents.
- **Auto-Expanding Member Drawer**: Keeps the chat area wide by collapsing the right-hand member list to `60px` and smoothly expanding it on hover.
- **Modern Message Bubbles**: Styled chat messages with subtle borders, glowing avatars, and smooth hover elevation.
- **Built-In Privacy Shield**: Automatically blurs sensitive account details in User Settings until hovered.

---

## Installation

### Method 1: Vencord / Vesktop
1. Download [`ArianPashae-Standalone.theme.css`](ArianPashae-Standalone.theme.css) (or [`ArianPashae.theme.css`](ArianPashae.theme.css)).
2. Open Discord **User Settings** → **Vencord** → **Themes**.
3. Click **Open Themes Folder** and drop the `.theme.css` file inside.
4. Enable the theme from the **Local Themes** tab.

### Method 2: BetterDiscord
1. Download [`ArianPashae-Standalone.theme.css`](ArianPashae-Standalone.theme.css) (or [`ArianPashae.theme.css`](ArianPashae.theme.css)).
2. Open Discord **User Settings** → **BetterDiscord** → **Themes**.
3. Click **Open Themes Folder** and move the downloaded file into the folder.
4. Toggle **ArianPashae** on in your themes list.

---

## Customization (`:root` Tokens)

You can customize the colors, home button logo, and corner radii directly inside `ArianPashae.theme.css`:

```css
:root {
  /* Core Palette */
  --ap-surface-base: #14141b;
  --ap-surface-elevated: #1f1f2b;
  --ap-surface-border: #2e2e40;
  --ap-brand-primary: #a855f7;
  --ap-brand-secondary: #d8b4fe;
  --ap-brand-glow: rgba(168, 85, 247, 0.38);

  /* Geometry & Motion */
  --ap-radius-xs: 8px;
  --ap-radius-sm: 12px;
  --ap-radius-md: 16px;
  --ap-radius-lg: 24px;
  --ap-ease: 0.32s cubic-bezier(0.16, 1, 0.3, 1);
}
```

---

<div dir="rtl">

## راهنمای فارسی

تم اختصاصی **ArianPashae** برای دیسکورد با ترکیب رنگی مشکی ابسیدین و بنفش نئونی طراحی شده است. تمام آیکون‌ها و لوگوهای این تم به‌صورت گرافیک برداری (SVG) درون خود کد جاسازی شده‌اند و به هیچ لینک یا عکس خارجی وابسته نیستند.

### ویژگی‌ها

- لوگوی وکتور اختصاصی `AP` روی دکمهٔ Home دیسکورد به همراه درخشش نئونی هنگام قرار گرفتن ماوس روی آن
- نشان وکتور `ARIANPASHAE` در نوار بالای پنجرهٔ دیسکورد با گرادیان بنفش
- حباب‌های پیام مدرن با حاشیهٔ ظریف و افکت درخشش آواتارها
- لیست اعضای جمع‌شونده در سمت راست که فضای چت را بازتر می‌کند و با بردن ماوس روی آن باز می‌شود
- تار شدن خودکار اطلاعات حساس اکانت در بخش تنظیمات کاربری برای حفظ حریم خصوصی در استریم یا اسکرین‌شات

### روش نصب در Vencord و BetterDiscord

۱. فایل [`ArianPashae-Standalone.theme.css`](ArianPashae-Standalone.theme.css) را دانلود کنید.  
۲. در تنظیمات دیسکورد به بخش **Themes** بروید و دکمهٔ **Open Themes Folder** را بزنید.  
۳. فایل دانلودشده را داخل پوشهٔ بازشده قرار دهید و کلید تم **ArianPashae** را روشن کنید.

</div>

---

## Repository Structure

```text
ArianPashae-Discord-Theme/
├── ArianPashae.theme.css             # Lightweight loader theme file (@import)
├── ArianPashae-Standalone.theme.css  # Full standalone theme file (works offline)
├── src/
│   └── main.css                      # Core stylesheet for GitHub Pages @import
├── assets/
│   ├── logo.svg                      # Standalone AP vector monogram
│   └── preview.png                   # Full theme screenshot
├── LICENSE                           # MIT License
└── README.md                         # Documentation
```

## Author & Links

- **Creator**: [ArianPashae](https://github.com/ArianPashae)
- **Website**: [https://arianpashae.com](https://arianpashae.com)
- **Repository**: [https://github.com/ArianPashae/ArianPashae-Discord-Theme](https://github.com/ArianPashae/ArianPashae-Discord-Theme)
