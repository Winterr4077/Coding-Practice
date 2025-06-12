## 🧪 Project: Developer Profile Page

Build a polished one-page **Developer Profile** for yourself. The goal is to structure it like a real portfolio, showcasing personal info, skills, and a highlighted project.

---

### 📄 Content Structure (HTML):

Your single `index.html` file should include:

- `<!DOCTYPE html>` and `<html lang="en">`
- Proper `<head>` with:
  - `<meta charset="utf-8">`
  - Page `<title>`
  - Link to `styles.css`

---

### 🧱 Page Layout:

#### 1. **Header**
- `<h1>` with the developer name
- A `<p>` with a short tagline or title (e.g. “Front-End Developer”)
- Optional: an image or icon

#### 2. **About Section**
- `<h2>` for the section title
- 1–2 paragraphs introducing the developer

#### 3. **Skills Section**
- `<h2>` for the section title
- Use a `<ul>` or styled list of at least 5 skills (HTML, CSS, Git, etc.)

#### 4. **Featured Project**
- `<h2>` title
- A `<div class="project-card">` containing:
  - Project name (`<h3>`)
  - Description (`<p>`)
  - A link (e.g., "View on GitHub")

#### 5. **Quote Block**
- Use a `<blockquote class="quote">` with a motivational quote
- Include a `<cite>` for attribution

#### 6. **Footer**
- A short message like “© 2025 Winterr. All rights reserved.”
- Optional: email or social handle

---

### 🎨 CSS Styling Guidelines:

- Set a **rich charcoal background** for the page: `#1c1c1e`
- Use `max-width: 800px` and `margin: auto` to centre content
- Apply `font-family: "Segoe UI", "Roboto", sans-serif` for a modern, readable font
- Style **all sections** with:
  - Background: `#2c2c2e`
  - Padding: `30px`
  - Margin-bottom: `40px`
  - Border-radius: `6px`
- Headings (`h1`, `h2`, `h3`) in **cool off-white**: `#f2f2f7`
- Paragraph text in **soft grey**: `#d1d1d6`
- Style the **quote block** with:
  - Background: `#3a3a3c`
  - Border-left: `6px solid #64a9ff`
  - Padding: `20px`
  - Margin: `40px auto`
  - Max-width: `600px`
  - Font-style: italic
  - Text color: `#d1d1d6`
- Style `cite` below the quote with:
  - Font-size: `14px`
  - Text color: `#9a9a9e`
  - Text-align: right
  - Display: block
  - Margin-top: `12px`
- Style the **project card** (`.project-card`) with:
  - Background: `#3a3a3c`
  - Padding: `20px`
  - Border-radius: `6px`
  - Margin-top: `20px`
- Project links (`a`) should be:
  - Color: `#64a9ff`
  - No underline by default
  - Underline or colour shift on hover

---
