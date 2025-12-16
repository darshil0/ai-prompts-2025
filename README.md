# 🤖 AI Prompt Collection 2025

A definitive, open-source library of **premium AI prompts** designed for 2025—optimized for **Gemini 3**, **ChatGPT**, **Claude**, and other advanced generative models.

This collection focuses on high-utility prompts for **image generation, infographics, video, design, and complex problem-solving**, all built within an accessible and fully responsive interface.

---

## 🛡️ Status

| Badge | Value |
|:------|:------|
| **Version** | v3.0.2 |
| **License** | MIT |
| **Accessibility** | WCAG 2.1 AA Compliant |

---

## ✨ Features & Highlights

* **Total Prompts:** 61 Handcrafted Prompts across writing, image, and logic categories.
* **Search & Filter:** Instant Search and filters by title, tags, or category for quick discovery.
* **Copy Integration:** Modern Clipboard API for seamless, one-click copying with robust fallback support.
* **Responsive Design:** Fully Responsive UI optimized for all devices (desktop, tablet, mobile).
* **Accessibility:** WCAG 2.1 AA compliant for an inclusive user experience.
* **SEO:** SEO-Ready Metadata for improved search engine visibility.

---

## 📚 Prompt Categories & Examples

A breakdown of the utility categories and a few examples from the collection:

### 🎨 Image Generation (9)

* **Focus:** Hyper-realistic visuals, stylized portraits, and commercial renders.
* **Examples:** Eiffel Tower at Night, Jack Sparrow Portrait, Collectible Figurines, Seasonal Panoramas.

### 📊 Infographics (5)

* **Focus:** Structured data visualization and complex topic summarization.
* **Examples:** Minimalist Timelines, Gemini 3 Prompting Guide, PDF-to-Infographic Summaries.

### 🎬 Video Generation (5)

* **Focus:** Cinematic camera movements, dynamic transitions, and scene direction.
* **Examples:** Dynamic Transitions, Crane Shots, Depth-of-Field Settings, Jungle Timestamp Prompting.

### 🖼️ Image Editing (5)

* **Focus:** Post-production effects, background manipulation, and stylistic overlays.
* **Examples:** Manga-Style Edits, Background Swaps, Polaroid Effects, Grid Layout Photos.

### 💡 Design (5)

* **Focus:** Conceptualizing full design systems, layouts, and rendering specific text effects.
* **Examples:** Tech Logos, Branding Sets, UX/UI Layouts, Floor Plan Visualizations.

### 🧠 Problem Solving (3)

* **Focus:** Testing and leveraging the model's analytical and reasoning capabilities.
* **Examples:** Logic Puzzles, Reasoning Tasks, Math Problems (Quadratic Formulas).

### 📣 Marketing & Writing (4)

* **Focus:** Generating high-quality campaign assets and refining existing copy.
* **Examples:** Campaign Copy, Social Posts, Blog Outlines, Email Polishers.

### 🧰 Best Practices (3)

* **Focus:** Educational prompts demonstrating effective communication with AI models.
* **Examples:** Be Specific, Use Natural Language, Edit Don't Re-roll.

### ⚙️ Other Fields (3)

* **Coding:** Python Web Scraper
* **Education:** Concept Explainer
* **Career:** Resume Bullet Generator

---

## 🚀 Quick Start

You can run this project locally without any complex build steps.

### Option 1 — Open Directly

Navigate to the repository folder and execute the following command:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option 2 — Serve Locally (Recommended)

Run a local HTTP server to prevent potential browser security restrictions:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server -p 8000

# PHP
php -S localhost:8000
```

Then, open your web browser and navigate to **http://localhost:8000**.

---

## 💻 Tech Stack

| Component | Technology | Description |
|:----------|:-----------|:------------|
| **Framework** | React 18 | Single-page application architecture. |
| **Styling** | Tailwind CSS 3.x | Utility-first CSS for fast styling. |
| **Fonts** | Inter, JetBrains Mono | Accessible UI font and clean monospace font for prompts. |
| **Build** | Single-file HTML | No bundler required for simple deployment. |

---

## 🧩 How to Use the App

1. Use the **Search bar** or **Category Filters** to find a specific prompt.
2. Click the **Copy Prompt** button next to any item.
3. The prompt is instantly copied to your clipboard, ready to be pasted into your preferred AI model (**Gemini, ChatGPT, Claude**, etc.).
4. **(Mobile)** Access the category filters and search via the tap-to-open menu icon.

---

## ♿ Accessibility Standard

This project adheres to **WCAG 2.1 AA** compliance standards, ensuring maximum accessibility:

* **Keyboard Navigation:** Full support for Tab, Enter, and Esc key navigation.
* **ARIA:** Proper use of Semantic HTML and ARIA attributes.
* **Visuals:** High color contrast ratios and clear focus indicators.
* **Responsiveness:** Fluid and responsive typography across all screen sizes.

---

## 📝 Version History

### **v3.0.2** — *December 16, 2025*

* Added "Male Educator with Neural Network Diagram" prompt.

### **v3.0.1** — *December 7, 2025*

* Added "Hyper-realistic Seasonal Panorama" prompt.

### **v3.0.0** — *December 4, 2025*

* Major content update with **18 new prompts** (Design, Writing, Education).
* New **"Best Practices"** category added to guide users in effective prompting.
* Refined UX: Replaced old `alert()` pop-ups with modern **toast notifications**.
* Technical fix: Resolved a React rendering duplication bug.

### **v2.0.0**

* Technical Migration: Switched to modern **Clipboard API**.
* Build change: Migrated to official React production builds.
* Improved SEO and comprehensive accessibility integration.

---

## 🤝 Contributing

We welcome contributions to grow this library!

1. **Fork** the repository.
2. **Add** your new prompt object directly into the data structure within `index.html`.
   ```javascript
   {
     id: 42, // Next available ID
     title: "Your Prompt Title",
     category: "Infographics|Image Generation|Problem Solving",
     description: "Short description (1–2 sentences for the card)",
     tags: ["new", "Tag2", "Tag3"],
     content: `Your full, powerful prompt text here...`
   }
   ```
3. **Test** the new prompt across different browsers.
4. **Submit** a pull request with a descriptive title.

---

## 📄 License

This project is licensed under the **MIT License**. You are free to use and modify it for both personal and commercial projects.

---

## 💬 Acknowledgments

* Inspiration drawn from the capabilities of leading 2025 models: **Gemini 3**, **GPT-5.1**, and **Claude Opus 4.5**.
* Thanks to the community for valuable feedback and contributions.

---

Made with ❤️ by [Darshil](https://github.com/darshil0) · **v3.0.1**
