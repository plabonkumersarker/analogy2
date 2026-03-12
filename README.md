# Analogy Master

A minimalistic, student-friendly flashcard app for practicing GRE-style analogies.

**🌐 Live Demo:** [https://plabonkumersarker.github.io/analogy2/](https://plabonkumersarker.github.io/analogy2/)

## ✨ Features

- **Dark Mode** - Easy on the eyes for long study sessions
- **Instant Search** - Filter analogies by citation number (01, 5, 12) or "Other"
- **4-Direction Navigation** - Swipe or tap up/down/left/right to navigate cards
- **Text Selection** - Select and copy any text for note-taking
- **Zero Dependencies** - Single HTML file, works offline
- **Mobile First** - Optimized for phones and tablets

## 🚀 Usage

1. Open the [live demo](https://plabonkumersarker.github.io/analogy2/)
2. Type a number (e.g., `01`, `5`, `12`) or `Other` in the search box
3. Press **Enter** to load matching analogies
4. Navigate cards by:
   - **Swiping** in any direction
   - **Tapping** edges of screen
   - **Arrow keys** (desktop)
   - **Mouse wheel** scroll

## 🎯 Search Examples

| Input | Result |
|-------|--------|
| `1` or `01` | Shows all `01-*` citations |
| `5` or `05` | Shows all `05-*` citations |
| `12` | Shows all `12-*` citations |
| `Other` | Shows non-numeric citations (etc, prince) |

## 🛠️ Data Format

Add your own analogies to the `analogyData` array:

```javascript
{
  "analogy": "word1:word2",
  "relation": "explanation of relationship",
  "answer": "answer1:answer2",
  "cite": "01-3"  // or "etc", "prince" for non-numeric
}

## 📦 Installation

No installation needed! Just open the HTML file in any modern browser.

For local use:
1. Download `index.html`
2. Double-click to open in browser
3. Or serve with any static server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000

---

## 📝 License

```markdown
## 📝 License

MIT License - feel free to use for your own study materials!
