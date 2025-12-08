# AI Prompt Collection 2025

![Version](https://img.shields.io/badge/version-3.0.1-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Accessibility](https://img.shields.io/badge/accessibility-WCAG%202.1%20AA-brightgreen.svg)

A curated collection of premium AI prompts for 2025, featuring infographic designs, image generation, and problem-solving templates optimized for Gemini, ChatGPT, Claude, and other leading AI models.

## ✨ Features

- **41 Premium Prompts**: Carefully crafted prompts for various use cases
- **Smart Search**: Real-time search by title or tags
- **Category Filtering**: Filter by Infographic, Image Generation, or Problem Solving
- **One-Click Copy**: Modern clipboard API with fallback support
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility First**: Full WCAG 2.1 AA compliance with ARIA labels and keyboard navigation
- **SEO Optimized**: Complete meta tags for search engines and social sharing

## 📚 Prompt Categories

### Image Generation (8 prompts)
- Paris at Night (Eiffel Tower)
- Captain Jack Sparrow Portrait
- Hyper-Realistic Product Visualization
- Creative Photo Transformations
- Traditional Dussehra Portrait
- 90s Bollywood Movie Poster
- Collectible Figurine Style
- Hyper-realistic Seasonal Panorama

### Infographic (5 prompts)
- Minimalist Timeline Infographic
- AI Progress November 2025 Watercolor Infographic
- Gemini 3 Prompting Guide Infographic
- PDF-to-Infographic Summary
- Modern Timeline Infographic

### Video Generation (5 prompts)
- Crane Shot: Hiker on a Canyon
- Shallow Depth of Field: Woman on a Bus
- Dynamic Transition: Pop Star Performance
- Dialogue Scene: Detective Office
- Timestamp Prompting: Jungle Exploration

### Image Editing (5 prompts)
- Product Photography: Gold Necklace
- Manga Style: Messi vs Ronaldo
- Photo Editing: Background Replacement
- Polaroid Photo Booth
- 3x3 Grid Photo

### Design (5 prompts)
- Modern Tech Logo Design
- Full Branding Set Creation
- UI/UX Homepage Design
- Floor Plan to Interior Visualization
- Text Rendering: IMAGINE

### Problem Solving (3 prompts)
- Garden Pathway Problem
- Logic Puzzle: Office Arrangement
- Math Reasoning: Quadratic Formula

### Marketing (2 prompts)
- Marketing Campaign Copy
- Social Media Caption Generator

### Writing (2 prompts)
- Blog Post Outline
- Email Polisher

### Best Practices (3 prompts)
- Be Specific
- Use Natural Language
- Edit, Don't Re-roll

### Other Categories (3 prompts)
- **Coding**: Python Web Scraper
- **Education**: Concept Explainer
- **Career**: Resume Bullet Point Generator

## 🚀 Quick Start

### Option 1: Direct Use
Simply open `index.html` in any modern web browser:
```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option 2: Local Server
For the best experience, serve via a local HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 💻 Technology Stack

- **Frontend Framework**: React 18 (Production Build)
- **Styling**: Tailwind CSS 3.x (CDN)
- **Icons**: Custom SVG components
- **Fonts**:
  - Inter (UI text)
  - JetBrains Mono (code/prompt display)
- **Build**: Single-file HTML (no build process required)

## 🎨 Usage

1. **Browse Prompts**: Click on any prompt in the sidebar to view its full content
2. **Search**: Use the search bar to find prompts by title or tags
3. **Filter**: Click category buttons to filter prompts by type
4. **Copy**: Click the "Copy Prompt" button to copy the entire prompt to your clipboard
5. **Mobile**: Tap the menu icon to access the sidebar on mobile devices

## ♿ Accessibility Features

This application is built with accessibility as a priority:

- ✅ **Keyboard Navigation**: Full support for Tab, Enter, and Escape keys
- ✅ **Screen Reader Support**: ARIA labels, live regions, and semantic HTML
- ✅ **Color Contrast**: WCAG AA compliant color ratios
- ✅ **Focus Management**: Clear focus indicators for all interactive elements
- ✅ **Responsive Text**: Readable font sizes across all devices

## 🌐 Browser Compatibility

| Browser | Minimum Version | Status |
|---------|----------------|--------|
| Chrome | 143+ | ✅ Fully Supported |
| Firefox | 145+ | ✅ Fully Supported |
| Safari | 26+ | ✅ Fully Supported |
| Edge | 142+ | ✅ Fully Supported |
| Opera | 124+ | ✅ Fully Supported |

**Note**: The modern Clipboard API is used with automatic fallback for older browsers.

## 📝 Version History

### Version 3.0.1 (December 7, 2025)
- Added new "Hyper-realistic Seasonal Panorama" prompt.

### Version 3.0.0 (December 4, 2025)

**Major Improvements:**
- ✨ Added 18 new high-quality prompts from Google's AI teams and other expert sources.
- 🚀 Introduced a new "Best Practices" category with prompts that teach effective prompting techniques.
- 🎨 Enhanced the "Copy to Clipboard" functionality with a modern, non-intrusive toast notification system, removing disruptive `alert()` pop-ups.
- 📈 Expanded prompt categories to include Design, Writing, Education, Career, and more.

**Technical Fixes:**
- 🛠️ Fixed a critical React rendering bug that caused parts of the UI to be duplicated.
- 🧹 General code cleanup and improved readability in the `index.html` file.

**Documentation:**
- 📝 Updated README.md with the latest version, an expanded prompt catalog, and a detailed changelog.

### Version 2.0.0 (December 4, 2025)

**Major Improvements:**
- ✨ Upgraded to modern Clipboard API with fallback support for older browsers
- ⚡ Switched from React development builds to production builds (improved performance)
- 🔍 Added comprehensive SEO meta tags (description, keywords, Open Graph, Twitter Cards)
- ♿ Implemented full accessibility features:
  - ARIA labels on all interactive elements
  - ARIA live regions for dynamic content announcements
  - ARIA expanded/pressed states for toggle buttons
  - Keyboard navigation support (Escape key to close mobile menu)
  - Screen reader only utility class for status announcements
- 🎨 Added sparkle emoji (✨) favicon using SVG data URI
- 🧹 Removed legacy code comments for cleaner codebase
- 📱 Enhanced mobile menu with proper ARIA attributes
- 🎯 Improved semantic HTML structure

**Technical Fixes:**
- Replaced deprecated `document.execCommand('copy')` with `navigator.clipboard.writeText()`
- Added error handling for clipboard operations
- Optimized React bundle size by using production minified builds
- Added `crossorigin` attribute to React script tags
- Implemented proper focus management for modal overlays

**Documentation:**
- Created comprehensive README.md with full project documentation
- Added usage instructions and technology stack details
- Documented browser compatibility and accessibility features

### Version 1.0.0 (Initial Release)
- Initial prompt collection with 9 curated prompts
- Basic search and filtering functionality
- Responsive design with mobile support
- Copy to clipboard feature

## 🤝 Contributing

Contributions are welcome! If you have premium AI prompts to add:

1. Fork the repository
2. Add your prompt to the `promptData` array in `index.html`
3. Follow the existing format:
   ```javascript
   {
       id: 10, // Next available ID
       title: "Your Prompt Title",
       category: "Infographic|Image Generation|Problem Solving",
       description: "Brief description (1-2 sentences)",
       tags: ["Tag1", "Tag2", "Tag3"],
       content: `Your full prompt content here...`
   }
   ```
4. Test thoroughly across browsers
5. Submit a pull request

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

## 🙏 Acknowledgments

- Prompt designs inspired by the latest AI model capabilities (Gemini 3, GPT-5.1, Claude Opus 4.5)
- UI/UX inspired by modern design systems
- Community feedback and contributions

## 📧 Contact & Support

For questions, suggestions, or issues:
- Open an issue on GitHub
- Submit a pull request with improvements
- Share your favorite prompts!

---

**Made by [Darshil](https://github.com/darshil0) with ❤️** | Version 3.0.0 | December 2025
