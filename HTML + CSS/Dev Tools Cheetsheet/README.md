## 🧪 Project: Dev Tools Cheatsheet (Interactive-Style Layout)

Build a clean, responsive, single-page **Developer Tools Cheatsheet** — designed like a quick-reference sheet for commands, shortcuts, or concepts in one topic.

---

### 💡 Concept:

It’s not a tutorial — it’s a **cheatsheet**, like something you’d pin on your wall or keep open while coding. Think fast info delivery, sectioned grid layout, and a code-snippet vibe.

---

### 📄 HTML Structure

Your `index.html` should include:

- DOCTYPE and `<html lang="en">`
- `<head>` with charset, title, and linked `styles.css`
- Use `<header>` for the page title
- Use `<main>` to group all cheatsheet content
- Use `<section class="cheat-block">` for each command/info unit

#### Each `.cheat-block` should include:
- A `<h2>` for the command/topic
- A `<pre><code>` block to format the syntax
- A `<p>` short description

Have at least **6 cheat blocks** (can be Git commands, CSS tricks, whatever you want)

---

### 🧱 Optional Section Ideas:
- Git Commands
- HTML Tags
- Bash One-Liners
- CSS Selectors

---

### 🎨 CSS Styling Guidelines

- Font: `"Fira Code"`, `"Courier New"`, or monospaced
- Background: `#0d1117` (dark GitHub-like)
- Text: `#c9d1d9`
- Cheat block background: `#161b22`, padding `20px`, margin-bottom `16px`, border-radius `6px`
- Use `.cheat-block code` to apply:
  - `background-color: #21262d`
  - `padding: 4px 8px`
  - `border-radius: 4px`
- Add subtle hover effects on each cheat block (`box-shadow` or background darken)
- Keep `max-width: 900px; margin: auto` for centre layout

---
