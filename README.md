# AI Prompt Collection 2025: The Blueprint

A modern, interactive library for storing, organizing, and accessing advanced AI prompts, designed for efficiency and collaboration. This single-file application serves as a comprehensive management tool for complex system prompts used across coding, design, and reasoning tasks.

## Status & Badges

| Status | Component    | Description                       |
|--------|--------------|-----------------------------------|
| ✅     | Frontend     | Single-page application logic     |
| ✅     | Styling      | Utility-first CSS framework       |
| ✅     | Architecture | Everything compiled into one file |

## Live Demo

If deployed to GitHub Pages, add your live URL here:

`https://<your-username>.github.io/ai-prompts-2025/`

Example:

`https://darshil0.github.io/ai-prompts-2025/`

## Features

- **Prompt Management**: Store and retrieve complex, multi-line prompts (including system prompts and templates) in one place.
- **Dynamic Filtering**: Filter prompts by Category (e.g., System Prompt, Coding & Web, Image Gen) and search by keywords or Tags.
- **Instant Copy**: One-click copy for the full prompt content to your clipboard.
- **Code Readability**: Custom typography (JetBrains Mono) for clear display of code, JSON, and structured prompts.
- **Zero Configuration**: Entire app is a single `index.html`—no builds, dependencies, or package installation required.

## Project Structure

To run this project, you only need the following two files in your repository root:

- `index.html` – The complete single-page application source.
- `README.md` – Project documentation (this file).

No additional configuration, bundlers, or servers are required.

## Installation & Usage

### 1. Run Locally

1. Download or copy the contents of `index.html`.
2. Save it as `index.html` on your computer.
3. Double-click `index.html` to open it in any modern web browser (Chrome, Edge, Firefox, etc.).

### 2. Host on GitHub Pages (Recommended)

1. Create a new GitHub repository (for example: `ai-prompts-2025`).
2. Upload `index.html` and `README.md` to the repository root.
3. In the GitHub repository, go to **Settings → Pages**.
4. Under **Source**, select the `main` (or `master`) branch and the root folder, then click **Save**.
5. After a short build time, your prompt library will be live at the GitHub Pages URL shown (for example:  
   `https://<your-username>.github.io/ai-prompts-2025/`).

## Customization: Adding and Editing Prompts

All prompt data is stored directly inside the `<script type="text/babel">` block in `index.html`, in a `promptData` array. Edit this array to add, remove, or update prompts.

### Editing `promptData`

Search for the `promptData` definition in `index.html` and add a new object following this structure:

```javascript
const promptData = [
  // ... existing prompts
  {
    id: 14, // Must be a unique number
    title: "Your New Prompt Title",
    category: "New Category Name", // e.g., "Reasoning", "Data Analysis"
    tags: ["Keyword1", "Keyword2"], // Used for search and filtering
    description: "A short, engaging summary visible in the sidebar.",
    content: `
      Paste your full, multi-line, complex prompt text here.
      Use backticks (\`) for multi-line strings.
      You can include code blocks like \`\`\`json or \`\`\`javascript here.
    `
  }
];
```

**Guidelines:**

- Ensure each `id` is unique and numeric.
- Use consistent `category` names so filters remain clean (e.g., `"System Prompt"`, `"Coding & Web"`, `"Image Gen"`, `"Reasoning"`).
- Add relevant `tags` to improve keyword-based search.
- Keep `description` concise; it appears in the sidebar or list view.
- Place your full reusable prompt in `content`; it can include formatted text and code blocks.

After saving changes, refresh the browser to see new or updated prompts. If using GitHub Pages, commit and push changes to redeploy automatically.

## Technology Overview

- **Frontend**: Single-page application rendered directly from `index.html`.
- **Styling**: Utility-first CSS framework (e.g., Tailwind-style utilities) embedded or CDN-loaded for quick customization.
- **Fonts**: JetBrains Mono (or similar developer font) for clean code and JSON display.
- **Runtime**: Pure client-side application—no backend or database required.

## License

This project is open source and available for personal or commercial use. Respect all applicable licenses for any third-party libraries, fonts, or frameworks referenced within `index.html`.

