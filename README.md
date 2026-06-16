# ☕ 9 Coffee — Marketing Workspace

A single-page, RTL (Arabic) marketing strategy document built as an interactive web page. It consolidates the full go-to-market plan for **9 Coffee** — a specialty coffee brand targeting the Egyptian market — into one shareable, branded workspace.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Language](https://img.shields.io/badge/lang-Arabic%20%2F%20RTL-yellow)
![Type](https://img.shields.io/badge/type-Static%20HTML-black)

## Overview

This project replaces a scattered set of slides and docs with a single, navigable HTML workspace covering the entire marketing plan — from execution timeline to brand identity. It's designed to be opened directly in a browser, with no build step or server required.

## Sections

| Section | Description |
|---|---|
| 📅 خطة العمل (Plan) | Three-team execution timeline with weekly tasks and dependencies |
| 🎯 الجمهور المستهدف (Audience) | Target audience breakdown, psychographics, and detailed personas |
| 🧭 الاستراتيجية (Strategy) | Vision, mission, and tactical roadmap |
| 📊 السوق (Market) | Competitor analysis in the Egyptian coffee market |
| 🛠️ الأدوات (Tools) | Free tools used by each team (Foundation, Brand Identity, Market Analysis) |
| 🔍 SWOT | Strengths, weaknesses, opportunities, and threats analysis |
| 🎨 الهوية البصرية (Visual Identity) | Brand colors, typography, and visual direction |
| 👥 التيم (Team) | Marketing team and roles |
| 📋 التقديم (Submit) | Final deliverables checklist |

## Gallery

A look at 9 Coffee in real life — the space, the products, and the packaging the brand identity in this workspace is built around.

<table>
  <tr>
    <td><img src="./assets/cafe-interior.jpeg" width="100%" alt="9 Coffee cafe interior"/><br/><sub>Cafe interior — seating area</sub></td>
    <td><img src="./assets/drinks-and-candy.jpeg" width="100%" alt="9 Coffee branded drinks"/><br/><sub>Branded drinks on the table</sub></td>
  </tr>
  <tr>
    <td><img src="./assets/candy-mix-bag.jpeg" width="100%" alt="9 Coffee branded candy bag"/><br/><sub>Branded candy mix packaging</sub></td>
    <td><img src="./assets/packaged-orders.jpeg" width="100%" alt="9 Coffee packaged orders"/><br/><sub>Packaged orders ready for pickup</sub></td>
  </tr>
</table>

## Features

- **Fully responsive** — works on desktop and mobile, with a sticky horizontal-scroll navigation bar
- **RTL-native** — built ground-up for Arabic content with proper `dir="rtl"` handling
- **Interactive tabs** — switchable panels for audience data and customer personas (Sara, Adam, Dina)
- **Branded design system** — custom black-and-yellow visual identity with CSS custom properties (design tokens) for easy theming
- **Zero dependencies** — pure HTML/CSS/JS, no frameworks or build tools

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, flexbox/grid layouts, keyframe animations (e.g. steam animation)
- **Vanilla JavaScript** — tab and persona panel switching
- **Google Fonts** — Playfair Display, Inter, DM Mono

## Getting Started

No installation needed — this is a static, self-contained HTML file.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open 9coffee-workspace.html   # or just double-click the file
```

Alternatively, serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/9coffee-workspace.html
```

## Project Structure

```
.
├── 9coffee-workspace.html   # Single-file workspace (HTML + CSS + JS)
├── README.md
└── assets/                  # Brand photos used in this README
    ├── cafe-interior.jpeg
    ├── drinks-and-candy.jpeg
    ├── candy-mix-bag.jpeg
    └── packaged-orders.jpeg
```

## Customization

Brand colors and core design tokens are defined as CSS variables at the top of the stylesheet (`:root`), making it straightforward to re-theme the page for a different brand:

```css
:root {
  --espresso: #111111;
  --amber:    #f5e600;
  --honey:    #fff04d;
  --cream:    #fffde8;
  ...
}
```

## License

This project is intended for internal/educational use. Add a license of your choice (e.g. MIT) if you plan to distribute it publicly.

## Contributing

This is a course/internal marketing deliverable. If you'd like to suggest improvements, feel free to open an issue or submit a pull request.
