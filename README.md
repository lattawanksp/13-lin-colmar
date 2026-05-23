# Colmar Academy — Landing Page

A responsive landing page for a fictional coding academy, built with **HTML** and **Tailwind CSS**.  
Designed from a wireframe and deployed live on Vercel.

🔗 **Live demo:** [13-lin-colmar.vercel.app](https://13-lin-colmar.vercel.app)

---

## What this project is about

Colmar Academy is a front-end layout challenge. The goal was to take a wireframe design and turn it into a working webpage — making sure it looks good on both mobile and desktop.

No JavaScript was used. Everything here is pure HTML structure + Tailwind utility classes.

---

## Pages / Sections

| Section         | What it shows                                      |
| --------------- | -------------------------------------------------- |
| Header & Nav    | Logo + navigation links, switches layout on mobile |
| Hero            | Full-width banner with headline and CTA button     |
| Information     | Mixed image/text layout with responsive grid       |
| Start Learning  | Course category list                               |
| Thesis Exhibits | Video + image cards                                |
| Footer          | Simple copyright footer                            |

---

## Tech stack

- **HTML5** — semantic structure
- **Tailwind CSS** — utility-first styling, responsive classes (`md:`, `lg:`)
- **Excalidraw** — wireframe planning before coding
- **Vercel** — deployment

---

## Key things I practiced

- **Responsive layout** — same HTML, different layout at different screen sizes using Tailwind breakpoints
- **Flexbox & Grid** — for aligning and arranging content
- **Image handling** — using `object-cover` and `shrink-0` to prevent layout breaks
- **Video embed** — learned that autoplay needs `muted` and `loop` attributes to work in modern browsers
- **Mobile-first thinking** — hiding/showing elements with `hidden`, `md:hidden`, `md:inline`

---

## Wireframe

Designed in Excalidraw before writing any code. You can view the wireframe file [`excalidraw.excalidraw`](./excalidraw.excalidraw) by opening it at [excalidraw.com](https://excalidraw.com).

---

## Project structure

```
13-lin-colmar/
├── index.html
├── tailwind.config.js
├── excalidraw.excalidraw   ← wireframe
├── sheet.markdown          ← personal notes & Tailwind cheatsheet
└── src/
    ├── 01_header/
    ├── 02_hero/
    ├── 03_information/
    ├── 04_courses/
    └── 05_thesis/
```

---

## How to run locally

```bash
# Clone the repo
git clone https://github.com/lattawanksp/13-lin-colmar.git
cd 13-lin-colmar

# Open in browser
open index.html
```

> No build step needed — Tailwind is loaded via CDN.

---

_Part of JSD12 bootcamp coursework — Generation Thailand_
