# 🎨 Text & Code Formatter

A browser-based tool for formatting text and source code with customizable colors, syntax highlighting, and live preview.

## ✨ Features

- **Live Preview:** See formatting changes instantly while typing.
- **Markdown Support:** Format content using headings, bullet lists, and numbered lists.
- **Automatic Code Detection:** Detects common programming code patterns and formats them into code blocks.
- **Syntax Highlighting:** Highlights code syntax using Highlight.js.
- **Custom Colors:** Customize the colors of:
  - Main headings (H1)
  - Subheadings (H2)
  - Small headings (H3)
  - Regular text
- **Dark & Light Themes:** Switch between two code preview themes.
- **Copy as Rich Text:** Copy formatted content for pasting into Canva and other supported applications.
- **Export to Word:** Download formatted content as a Word-compatible document.
- **Export to PDF:** Generate a PDF version of your formatted content.
- **Responsive Design:** Works on desktop and mobile screens.
- **Arabic Support:** Designed with Arabic typography and RTL layout support.

## 🚀 Getting Started

1. Download or clone the repository.
2. Open `index.html` in your browser.
3. Start typing in the editor.
4. Customize colors and switch between themes.
5. Use the export buttons to save or copy your work.

No build process or installation is required.

## 📝 Supported Formatting

| Syntax | Result |
|---|---|
| `# Heading` | Main heading |
| `## Heading` | Subheading |
| `### Heading` | Small heading |
| `- Item` | Bullet list |
| `* Item` | Bullet list |
| `1. Item` | Numbered list |
| Code blocks | Syntax-highlighted code |

You can also write code directly, and the tool attempts to detect common programming patterns automatically.

### Code Block Example

\```python
def hello():
    print("Hello, CodePrint!")
\```

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- [Highlight.js](https://highlightjs.org/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [html2canvas](https://html2canvas.hertzen.com/)

## 📤 Export Options

- **Rich Text:** Copy formatted HTML to the clipboard.
- **Word:** Export as a `.doc` file compatible with Microsoft Word.
- **PDF:** Export the preview as an image-based PDF.

*Note: PDF export uses html2canvas, so the exported content is rendered as an image rather than selectable text.*

## 🌐 CodePrint

Developed as part of the **CodePrint** project collection.

- **GitHub:** https://github.com/codeprintomar
- **Website:** https://code-print.wasmer.app/
- **Projects:** https://code-print.wasmer.app/projects.html

---

**Made with ❤️ by CodePrint**
