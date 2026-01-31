# ✦ The Writing Tracker

> *"Bleed onto the page."*

A minimalist word tracker and sprint timer designed for authors, and ADHD brains. 

Designed to be hosted on GitHub Pages and embedded directly into **Notion**.

## ⚡ Features

* **The Daily goal:** A visual progress ring that fills as you meet your daily word count goals.
* **The Sprint mod:** A dedicated timer for writing sprints. 
    * *Visual Panic:* The timer includes a "heartbeat" animation that intensifies as you enter the final minute of a sprint.
* **Streak Tracking:** keep the chain alive. Logic is adjusted for late-night writers (so 2 AM sessions don't break your streak).
* **Privacy First:** Zero data leaves your device. All stats are saved to your browser's Local Storage.
* **Atmospheric UI:** Deep violets, gothic fonts (`Cinzel`), and subtle glow effects.

## 💻 How to Use

### Option 1: The Notion Embed (Recommended)
1.  Ensure this repository has **GitHub Pages** activated (Settings > Pages > Branch: Main).
2.  Copy your generated URL (e.g., `https://yourusername.github.io/writing-tracker/`).
3.  Open **Notion**.
4.  Type `/embed` and paste the URL.
5.  Resize the widget to fit your dashboard.

### Option 2: Desktop App
1.  Download the `index.html` file.
2.  Double-click to open it in your browser.
3.  Pin the tab or bookmark it for daily access.

## ⚙️ Customization

If you want to change the colors, edit `index.html` and look for the `:root` section at the top of the CSS:

```css
:root {
  --bg-color: #0f0a1e;       /* Background */
  --primary-color: #a855f7;  /* The main glow/accent */
  --text-color: #d4b5f7;     /* Main text */
}
