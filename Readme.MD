# Tessa Studio — Personal Portfolio

A modern, elegant personal portfolio website built with HTML, CSS, and JavaScript. The design features a lavender-and-black aesthetic with editorial typography, floating sparkles, and smooth animations.

## Project Structure

##Features

- **Custom Design System** — Lavender & black palette with CSS variables for easy theming.
- **Editorial Typography** — Cormorant Garamond (serif) + Jost (sans-serif).
- **Floating Sparkles** — Animated ✦ / ✧ elements drifting across every page.
- **Fade-Up & Float Animations** — Smooth entrance effects on the homepage hero.
- **Responsive Layout** — Mobile-friendly navigation, stacked layouts, and adjusted font sizes.
- **Interactive Contact Form** — Client-side validation for name, email, phone, and message.
- **Task Planner** — Add, complete, and delete academic tasks in real time.
- **Project Detail Pages** — Dedicated write-ups for each showcased project.
- **Arched Image Frames** — Signature "window" shape for the profile photo.

##Built With

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, grid/flexbox layouts, animations |
| **JavaScript (Vanilla)** | Form validation, task manager, interactivity |
| **Google Fonts** | Cormorant Garamond & Jost |


## Getting Started

1. **Clone or download** the project files into a single folder.
2. Make sure the following assets are present (or replace with your own):
   - `aoki.jpg` — my profile photo
   - `kk.png` — To-Do List project screenshot
   - `video.mp4` — my video
3. Open `index.html` in any modern browser.

## Pages Overview

| Page | Description |
|------|-------------|
| **Home** (`index.html`) | Hero split layout with headline, intro, CTA, and profile image. |
| **About** (`about.html`) | Bio, technical skills, interests, and a portfolio video. |
| **Education** (`education.html`) | Table of academic history. |
| **Projects** (`projects.html`) | List of showcased projects with links to detail pages. |
| **Planner** (`planner.html`) | Interactive to-do list for academic tasks. |
| **Contact** (`contact.html`) | Validated contact form. |

##Customization

All colors, fonts, and core spacing live in the `:root` block at the top of `style.css`:

```css
:root {
  --bg:            #faf8fb;
  --text:          #0f0f11;
  --lavender:      #d8cce6;
  --lavender-dark: #bbaad6;
  --card-bg:       #ffffff;

  --font-sans:  'Jost', sans-serif;
  --font-serif: 'Cormorant Garamond', serif;
}