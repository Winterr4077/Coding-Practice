## 🧪 Project: “Tools I Can’t Live Without” Feature Page

Create a feature page highlighting **5 tools, apps, or websites** you use constantly — developer tools, meme sites, writing apps, AI tools, whatever.

This page is meant to look like a **clean editorial layout**, almost like a section from a tech blog or product spotlight page.

---

### 📄 HTML Structure

Your `index.html` must include:

- Valid `<!DOCTYPE>` and `<html lang="en">`
- `<head>` with `<meta charset="utf-8">`, viewport, and linked `styles.css`
- `<header>` with a title and subheading
- `<main>` containing 5 tool blocks
- `<footer>` with your name or handle

#### Each tool block should be inside `<section class="tool">` and include:
- `<h2>` tool name
- `<p>` description
- `<img>` of logo/screenshot (real or placeholder)
- `<a>` link to the tool (use `target="_blank"`)

---

### 🎨 CSS Styling Guidelines

- Background: `#0f0f0f` (charcoal black)
- Font: `"Poppins"` or `"Segoe UI"`, fallback to sans-serif
- Page max-width: `1000px`, centred with `margin: auto`

#### Typography
- `h1`: very large, uppercase or wide font (`font-size: 48px`)
- `h2`: `font-size: 24px`, colour `#f5f5f5`
- Paragraphs: `color: #bbb`, `line-height: 1.6`

#### `.tool` Blocks
- Background: `#1a1a1a`
- Padding: `24px`
- Margin-bottom: `32px`
- Border-radius: `8px`
- Display each block in a **2-column layout**:
  - Left: image (fixed width or 40%)
  - Right: text (60%)
- Use `display: flex; gap: 24px;`

#### Images
- Max-width: `100%`
- Border-radius: `6px`
- Optional: add `box-shadow`

#### Links
- Colour: `#1e90ff`
- Underline on hover
- Consider styling as a button (`padding`, `border`, `background`)

#### Footer
- Centered text
- `color: #666`, small font

---

### 🧠 Goal

Use this project to practise:
- Multi-column layout using `flexbox`
- Text/image pairing
- Creating contrast between sections
- Clear link styling

---
