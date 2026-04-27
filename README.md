# PIXLOGIX

A pet care services website built with **HTML5**, **Tailwind CSS**, and **Font Awesome** icons.

## Features

- **Responsive & Scalable:** The webpage is fully scalable and responsive across all screen sizes and devices.
- **Accessible & Semantic HTML:** Built using semantic HTML tags to ensure high accessibility and better SEO.
- **Theme-First Approach:** The design utilizes a theme-first approach. By changing the core color variables (e.g., in `variables.css`), you can directly and instantly change the entire visual theme of the website.

## Quick Start

### Prerequisites
- Node.js v14+
- npm

### Setup
```bash
npm install
npm run dev      # Start dev server (http://localhost:5173)
npm run build    # Production build
npm run preview  # Preview production build
```

## Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| Vite | 8.0.10 | Build tool & dev server |
| Tailwind CSS | 3.4.1 | Utility-first CSS framework |
| PostCSS | 8.4.33 | CSS processing |
| Font Awesome | 6.5.1 | Icon library (self-hosted) |
| Fontsource Inter | 5.0.16 | Typography |

## Project Structure

```
src/
├── css/
│   ├── variables.css    # CSS custom properties & design tokens
│   ├── main.css         # Tailwind + custom components
│   └── fonts.css        # Typography setup
├── js/
│   └── main.js          # Application logic
└── pages/
    └── index.html       # Main page

public/
├── icons/               # SVG icons
├── images/
│   ├── main/           # Hero & main content
│   ├── moments/        # Gallery & testimonials
│   ├── service/        # Service images
│   ├── team/           # Team photos
│   └── update/         # Blog & updates
└── fonts/              # Custom fonts (if needed)
```

## Color System

| Variable | Color | Use |
|----------|-------|-----|
| Primary | #f16e53 | Buttons, accents |
| Secondary | #6a89b6 | Links, hover states |
| Dark | #1a1a1a | Text |
| Light | #ffffff | Backgrounds |

## CSS Architecture

- **variables.css** - Design tokens (colors, spacing, shadows)
- **main.css** - Tailwind imports + custom utility classes
- **fonts.css** - Font face declarations & typography

## Build & Deployment

```bash
# Production build creates optimized dist/ folder
npm run build

# Deploy dist/ folder to hosting
# Supports: Netlify, Vercel, GitHub Pages, or any static host
```

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Configuration Files

- `vite.config.js` - Build configuration
- `tailwind.config.js` - Tailwind theme customization
- `postcss.config.js` - PostCSS plugins
- `.gitignore` - Git ignore rules
