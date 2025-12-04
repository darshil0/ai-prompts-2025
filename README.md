# AI Prompt Collection 2025: The Blueprint

A modern, interactive library for storing, organizing, and accessing advanced AI prompts, designed for efficiency and collaboration. This single-file application serves as a comprehensive management tool for complex system prompts used across coding, design, and reasoning tasks.

## Status & Badges

| Status | Component    | Description                       |
|--------|--------------|-----------------------------------|
| ✅     | Frontend     | Single-page application logic     |
| ✅     | Styling      | Utility-first CSS framework       |
| ✅     | Architecture | Everything compiled into one file |

🚀 Live Demo

(If you deploy this to GitHub Pages, replace this line with your URL: https://darshil0.github.io/ai-prompts-2025/)

✨ Features at a Glance

- **Prompt Management**: Store and retrieve complex, multi-line prompts easily.
- **Dynamic Filtering**: Quickly filter prompts by Category (System Prompt, Coding & Web, Image Gen, etc.) or search using keywords and Tags.
- **Instant Copy**: One-click functionality to copy the full prompt content to the clipboard.
- **Code Readability**: Custom typography (JetBrains Mono) enhances the readability of code and JSON structures within the prompt content.
- **Zero Configuration**: The entire application is contained within a single `index.html` file, requiring no local build steps or package installations.

🛠️ Project Setup

### Required Files

To run this project, you only need the following two files in your repository root:

- `index.html` (The application source code)
- `README.md` (This documentation file)

### Installation & Execution

**1. Run Locally**

1.  Download or copy the contents of `index.html`.
2.  Save it as `index.html` on your computer.
3.  Double-click the file to open it in any modern web browser.

**2. Host on GitHub Pages (Recommended)**

1.  Upload `index.html` and `README.md` to your GitHub repository (e.g., `ai-prompts-2025`).
2.  Go to your repository **Settings** and navigate to the **Pages** section.
3.  Select the `main` branch as the deployment source and save.

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

All prompt data is stored directly within the `<script type="text/babel">` block inside `index.html`.

To add a new prompt, simply edit the `promptData` array in `index.html` by adding a new JavaScript object following this structure:

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

## Changelog

### Version 2.0.2 (December 2025)
- **Feature**: Replaced the favicon with a user-provided image.

### Version 2.0.1 (December 2025)
- **New Prompts**: Added new prompts for Design, Coding, and Marketing to expand the collection.

### Version 2.0.0 (December 2025)
- **UI Revamp**: Complete overhaul of the user interface with a modern, card-based design, an improved search bar, and a more vibrant color scheme. The application is now more responsive and user-friendly.
- **New Prompts**: Added a collection of new prompts for "Nano Banana Pro," "Google Veo 3," and "Google Veo 3.1," covering a wide range of use cases from product photography to advanced cinematography.

### Version 1.1.0 (November 2025)
- **Modernized Clipboard API**: Replaced the deprecated `document.execCommand('copy')` with the modern, more secure `navigator.clipboard.writeText` API for all copy-to-clipboard functionality. A fallback is retained for older browsers.
- **Improved Rendering Performance**: Removed `backdrop-blur` and fractional opacity (`bg-white/80`) from the sidebar to prevent potential rendering glitches on certain browsers and improve performance. The sidebar now uses a solid `bg-white` background.
- **Enhanced Code Readability**: Added comments to `index.html` to clarify the purpose of icon components and semantic list structures.

### Version 1.0.0 (Initial Release)
- Initial release of the AI Prompt Collection 2025 application.
- Features include prompt management, dynamic filtering, instant copy, and a zero-configuration setup.

## License

This project is open source and available for personal or commercial use. Respect all applicable licenses for any third-party libraries, fonts, or frameworks referenced within `index.html`.
