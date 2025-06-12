## 🧪 Project: Comparison Table Page

In this lab, you’ll build a one-page **comparison page** for two fictional or real products, services, or games. The goal is to structure a clean table-based layout, paired with a short pitch, styled with dark-mode CSS.

---

### 📄 Structure (HTML)

Your `index.html` should include:

- Proper `<!DOCTYPE>` and `<html lang="en">`
- `<head>` with charset and linked `styles.css`
- `<header>` with:
  - `<h1>` title
  - Short paragraph intro
- `<main>` containing:
  - A `<table>` that compares **2 products** across at least 4 features
    - Use a `<thead>` for product names
    - Use a `<tbody>` for the comparisons
  - A `<blockquote class="quote">` with a final verdict or user opinion
  - A `<footer>` with a CTA or contact link

---

### 🧱 Example Table Features

| Feature         | Product A        | Product B        |
|-----------------|------------------|------------------|
| Price           | £49.99           | £69.99           |
| Resolution      | 1080p            | 4K               |
| Multiplayer     | Yes              | Yes              |
| Custom Skins    | No               | Yes              |

---

### 🎨 CSS Styling Guidelines

- Page background: `#121212`
- Font: `"Inter"` or `"Segoe UI"`, fallback to sans-serif
- Table:
  - Full-width (`width: 100%`)
  - Left-aligned text
  - Header row background: `#1e1e1e`
  - Body rows alternate using `:nth-child(even)` with `#2a2a2a`
  - Text color: `#ccc`
  - Padding inside cells: `12px`
  - Optional: soft borders
- Quote block:
  - Background: `#1f1f1f`
  - Border-left: `6px solid #1e90ff`
  - Padding: `20px`
  - Text: italic
- Footer:
  - Small text
  - Centre aligned
  - Muted colour like `#888`

---

