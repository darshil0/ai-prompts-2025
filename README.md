# AI Prompt Collection 2025: The Blueprint

A modern, interactive library for storing, organizing, and accessing advanced AI prompts, designed for efficiency and collaboration. This single-file application serves as a comprehensive management tool for complex system prompts used across coding, design, and reasoning tasks.

🌟 Status & Badges

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

Your prompt library will be instantly live at the URL provided by GitHub Pages.

⚙️ Customization: Adding and Editing Prompts

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


📄 License

This project is open source and available for personal or commercial use.
