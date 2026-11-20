Link:- https://kumawatvikash3121-del.github.io/Portfolio/

# Vikash Kumawat | Student Portfolio Website

A responsive, single-page portfolio website built with plain **HTML5** and **CSS3** as part of the BCA first-year curriculum at **Dezyne École College, Ajmer**.

No frameworks, no JavaScript. Just HTML and CSS.

---

## Preview

The page has six sections, from top to bottom:

| Section | What it shows |
|---|---|
| **Home** | Name, short intro, buttons, social icons, and a photo in an arch frame with a rotating dashed circle |
| **Marquee** | A scrolling strip of skills (HTML5, CSS3, JavaScript, Responsive Design, Flexbox & Grid) |
| **About** | A sticky photo on the left, with the story, college card and learning path on the right |
| **Skills** | Six skill cards with progress bars on a dark background |
| **Assignments** | Six assignment cards with task details and a list of what was done |
| **Contact** | Banner image, contact details and a message form |

A footer closes the page.

---

## Features

- Fully responsive layout for desktop, tablet and mobile
- Rotating dashed circle in the hero section (CSS animation)
- Infinite scrolling marquee (CSS animation)
- Sticky photo in the About section while the text scrolls
- Floating HTML5 and CSS3 tags in the hero section
- Smooth zoom on the hero photo when hovered
- Slow automatic zoom on the contact banner image
- Hover lift and shadow on the assignment cards
- Progress bars with a gradient fill in the Skills section
- Contact form that opens the visitor's email app
- Colors and fonts controlled from one place using CSS variables

---

## Project structure

```
Project/
├── index.html     # all the page content
├── style.css      # all the styling
├── laptop.jpg     # hero section photo
├── about.jpg      # about section photo
├── contact.jpg    # contact banner photo
└── README.md
```

> Make sure the three image files have exactly these names, or update the `src` in `index.html`.

---

## How to run

1. Download or clone the project folder.
2. Keep `index.html`, `style.css` and the images in the same folder.
3. Double-click `index.html` to open it in your browser.

An internet connection is needed the first time, because the fonts and icons load from the web.

---

## Built with

- **HTML5**: semantic structure
- **CSS3**: Flexbox, Grid, variables, transitions, keyframe animations, media queries
- **Google Fonts**: Bricolage Grotesque (headings) and Figtree (body text)
- **Font Awesome 6**: icons

---

## Color palette

All colors are set once at the top of `style.css` in `:root`.

| Variable | Color | Used for |
|---|---|---|
| `--paper` | `#F4F7FF` | page background |
| `--white` | `#FFFFFF` | cards and text on dark backgrounds |
| `--ink` | `#0E1B4D` | main text, dark sections |
| `--muted` | `#4A5578` | paragraph text |
| `--cobalt` | `#1E40D8` | buttons, links, icons |
| `--turquoise` | `#0E9F9A` | accents and progress bars |
| `--marigold` | `#FFB627` | yellow highlights |

To change the look of the whole site, edit these values.

---

## Responsive breakpoints

| Screen width | Layout |
|---|---|
| Above 1024px | Full desktop layout |
| 601px to 1024px | Tablet: sections stack, cards show 2 per row |
| 600px and below | Mobile: single column, smaller text and images |

The responsive CSS is at the very end of `style.css`.

---

## How to customize

- **Name and text:** edit the content in `index.html`.
- **Skill levels:** in each skill card, change the number in `style="width:95%"` and the percentage text next to it.
- **Marquee speed:** change `20s` in `.track { animation: scroll 20s ... }`. A smaller number is faster.
- **Circle speed:** change `25s` in `.dashed` (hero) or `50s` in `.skills-circle` (skills).
- **Contact email:** change the address in the form's `action="mailto:..."`.
- **Photos:** replace `laptop.jpg`, `about.jpg` and `contact.jpg` with your own pictures.

---

## What I learned

- Building page layouts with Flexbox and Grid
- Making a website responsive with media queries
- Using CSS variables to keep colors consistent
- Creating animations with `@keyframes` and `transition`
- Using `position: sticky` for the About photo
- Styling forms, cards and hover effects

---

## Author

**Vikash Kumawat**
BCA First Year, Dezyne École College, Ajmer

© 2026 Vikash Kumawat | Student Portfolio | HTML5 & CSS3 Assignment Project
