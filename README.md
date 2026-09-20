# web-proje-ornek

Assignment 1 - a 4-page website written with **HTML5 only** (no CSS, no JavaScript).

## Theme

The website is called **Code Corner**. It is the personal portfolio of a computer engineering student.
It shows the student's projects, a short "about" page and a contact form.

## File Organization

```
.
├── index.html       # Home page (two articles with images)
├── about.html       # About page (section, figure, semantic tags)
├── services.html    # Projects page (table with thead, tbody, tfoot)
├── contact.html     # Contact page (form)
├── assets/
│   └── images/      # project.svg, learning.svg, about.svg
└── README.md
```

- All pages use the same `<nav>` menu, so you can go from any page to any other page.
- All links and image paths are **relative** (for example `about.html` and `assets/images/about.svg`).

## Challenges I Faced

- Without CSS the pages look very plain, so I had to focus only on a clean and correct structure.
- I had to remember to copy the same navigation menu to every page and keep it identical.
- Building the table was confusing at first: `<thead>`, `<tbody>` and `<tfoot>` must be used in the right places, and `colspan` was needed in the footer row.
- Choosing the right semantic tag (`<section>`, `<aside>`, `<article>`, ...) was harder than I expected.
- Using relative paths correctly, so that the images and links still work when the folder is moved.
