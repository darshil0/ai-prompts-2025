###ai-prompts-2025 

AI Prompt Collection 2025

A modern, interactive library for storing, organizing, and accessing advanced AI prompts. This single-file web application features a clean, responsive interface designed to help users manage complex system prompts for coding, design, and reasoning tasks.

🚀 Live Demo

(If you deploy this to GitHub Pages, replace this line with your URL: https://www.google.com/search?q=https://yourusername.github.io/your-repo-name)

✨ Features

Interactive Sidebar: Filter prompts by categories (System Prompt, Coding & Web, Image Gen, etc.) or search by keywords/tags.

One-Click Copy: Easily copy complex prompts to your clipboard with a single click.

Syntax Highlighting: Prompts containing code blocks (like JSON) are automatically formatted for readability.

Responsive Design: Works seamlessly on desktop and mobile devices.

Single File Architecture: The entire app runs from a single index.html file—no build process or complex installation required.

🛠️ Tech Stack

React 18: For UI components and state management.

Tailwind CSS: For styling and responsive design.

Lucide React: For consistent iconography.

Babel Standalone: Enables JSX compilation directly in the browser.

📦 Installation & Usage

Method 1: Run Locally

Download the index.html file.

Double-click it to open it in any modern web browser (Chrome, Firefox, Safari, Edge).

No server or internet connection is strictly required (though CDN scripts are loaded from the web).

Method 2: Host on GitHub Pages

Fork or clone this repository.

Go to your repository Settings.

Navigate to the Pages section.

Select the main branch as the source and save.

Your prompt library will be live at https://<username>.github.io/<repository-name>/.

📂 Project Structure

/
├── index.html      # Contains all logic, styles, and prompt data
└── README.md       # Project documentation


📝 Customizing Prompts

To add or edit prompts, open index.html in any text editor (like VS Code or Notepad). Look for the promptData array near the top of the script section:

const promptData = [
    {
        id: 1,
        title: "Your New Prompt Title",
        category: "Category Name",
        tags: ["Tag1", "Tag2"],
        description: "Short description for the sidebar.",
        content: `Paste your full prompt text here...`
    },
    // ... more prompts
];


📄 License

This project is open source and available for personal or commercial use.
