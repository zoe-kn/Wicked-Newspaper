# Wicked-Newspaper

## Newspaper Article – “For Good”

A small frontend mini project that recreates a newspaper-style article layout inspired by the song **“For Good”** from *Wicked*.  
The page focuses on typography, layout, and subtle visual effects.

---

## Preview

The page displays:

- A newspaper “nameplate” (`Wicked`)
- Date, headline, sub-headline and author line
- A large main image
- Two text columns with a drop-cap first letter
- A secondary image aligned with the second column

---

## Tech Stack

- **HTML5** – semantic page structure (headings, paragraphs, images)
- **CSS3**
  - CSS Grid for the two-column layout (`.separator`)
  - Typography (custom Google Font + system fonts)
  - Gradient text with `background-clip: text`
  - Drop cap using `::first-letter`
  - Image hover effects with `filter`, `transform` and `box-shadow`

---

## Project Structure

```text
.
├── index.html   # Main HTML file
└── styles.css   # All styling for the newspaper layout
