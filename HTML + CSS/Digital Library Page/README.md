In this lab, you will create a Digital Library Page using HTML and CSS. You’ll practise semantic layout, text organisation, and visual styling of structured content like book listings.

---

### User Stories:

- You should have a DOCTYPE declaration.

- You should have an html element with lang set to en.

- You should have a head element with:
  - A meta charset of utf-8
  - A title of your choice (e.g., Digital Library)
  - A linked external stylesheet (`styles.css`)

- You should have a header with:
  - An h1 element with the page title
  - A paragraph describing what this digital library is about

- You should have a main element with a section for book listings.

- Each book should be inside a `<div class="book">` and include:
  - An image of the book cover (use placeholder or meme images if you want)
  - A title (`<h2>`)
  - The author's name (`<p>`)
  - A short description (`<p>`)
  - A link that says “Read more” or “Preview”

- You should include at least 3 books.

- You should have a footer with a short message like “Built by Winterr” or “Updated 2025”.

---

### In your styles.css:

- Set a background colour for the page

- Use `max-width` and `margin: auto` to centre the layout

- Style each book card with:
  - A border and background colour
  - Padding and spacing
  - Text-align: left
  - Consistent sizing for book cover images

- Style links with `:hover` and `:visited`

- Optional: Use a different font family for titles and descriptions
