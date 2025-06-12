## 🧪 Project: Personal Homepage (Capstone Level)

In this lab, you’ll build a full-featured **Personal Homepage** — a complete one-pager that introduces you, your work, your thoughts, and your contact details. This will test your ability to structure, organise, and design a full page using everything you’ve learned so far.

---

### 📄 Structure (HTML)

Your `index.html` should include:

- DOCTYPE and `<html lang="en">`
- `<head>` with:
  - `<meta charset="utf-8">`
  - `<title>` (e.g. “Winterr | Home”)
  - Linked `styles.css`

- Use semantic layout:
  - `<header>` for your name, tagline, and site nav
  - `<main>` with 5 sections:
    1. **About**
    2. **Projects**
    3. **Skills**
    4. **Quote Block**
    5. **Contact**

  - `<footer>` with a short note or copyright

---

### 🧱 Section Requirements

#### 1. **About Section**
- `<h2>` heading
- 1 image
- 1–2 paragraphs about you

#### 2. **Projects Section**
- `<h2>` heading
- At least 2 projects in `<div class="project">` blocks
  - Use `h3`, `p`, and a placeholder `<a>` for each

#### 3. **Skills Section**
- `<h2>` heading
- Use a `<ul>` or `<div class="skill-list">` with at least 5 skills

#### 4. **Quote Block**
- `<blockquote class="quote">` and a `<cite>`
- Should reflect something personal or motivational

#### 5. **Contact Section**
- `<h2>` heading
- Simple `<table>` listing:
  - Contact method (email, Discord, etc.)
  - Info (mailto, handle, etc.)

---

### 🎨 CSS Styling Guidelines

- Page background: dark (`#121212`) or deep gradient
- Font: `"Segoe UI"`, `"Poppins"`, or `"Inter"`
- Max-width: `800px`; centre with `margin: auto`
- All sections:
  - Padding: `40px`
  - Margin-bottom: `40px`
  - Rounded corners and subtle background (`#1e1e1e` or `#2a2a2a`)
- Headings: bold, light-coloured (`#f1f1f1`)
- Paragraphs: soft grey (`#ccc`)
- Links: highlight colour (`#1e90ff`), hover underline
- Quote: italic, border-left `6px solid #1e90ff`, `max-width: 600px`, centred
- Project cards: background `#2c2c2e`, padding `20px`, spacing between them
- Skills list: flex or block style with spacing and simple borders
- Table: styled with full-width, left-aligned text, zebra-striping optional
- Footer: smaller font, muted tone, centre-aligned

---
