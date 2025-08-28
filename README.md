# Interactive Collage (Digital Companion)

An interactive web version of **Kellie Anne Dunn’s** physical art collage.  
This project digitizes the real-life collage and makes it **zoomable, explorable, and clickable**, so viewers can read the associated metadata journal entries that explain how each visual element relates to the research question.

> Built by **Afnan Jasim** for Kellie Anne Dunn’s PhD art/research project.

---

## What it does
- **Pan & Zoom** around a high-resolution collage
- **Clickable points** (map dots) reveal curated notes/journal metadata
- **Two exploration modes**
  - **Thematic:** view clusters of imagery in proximity
  - **Chronological:** follow numbered points in the order they were created
- **Responsive UI** designed for desktops and laptops (mobile-friendly where possible)
- **Lightweight styling** via Tailwind CSS

---

## Tech Stack
- **Next.js (React)** — application framework
- **TypeScript** — type-safe component logic
- **Tailwind CSS** — styling
- **Lucide Icons** — UI icons

---

## Getting Started

### Prerequisites
- **Node.js 18+** (recommend LTS)
- One of: **npm / pnpm / yarn**

### Install & Run
```bash
git clone https://github.com/<your-username>/interactive-collage.git
cd interactive-collage
# choose your package manager
npm install
npm run dev
