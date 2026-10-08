# FitForge - Premium Fitness & Wellness Landing Page

FitForge is a modern, high-conversion landing page designed for a fitness and wellness ecosystem. Built with a fully responsive layout using raw HTML and Tailwind CSS, it features high-end UI trends like Glassmorphism, interactive hover states, dynamic flex layouts, and smooth grid transitions.

## 🚀 Features

- **Glassmorphic Navigation & Sections:** Integrated `backdrop-blur-md` and `bg-white/10` containers to maintain a sleek, premium, transparent aesthetic.
- **Alternating Plan Grid Layout:** Employs explicit responsive breakpoints (`md:order-last`, `order-first`) to create a balanced, engaging zig-zag visual hierarchy on desktop, which perfectly shifts to standard stacked layouts on mobile screens.
- **Glow & Gradient FX:** Clean background radial blurs (`blur-3xl`), dual-tone text gradient masking (`bg-clip-text`), and soft custom drop shadows (`shadow-pink-500/20`).
- **Clean Structure:** Fully validated, syntactically clean single-file layout with corrected structural wrappers and eliminated double-headers.

## 📂 File Architecture

```bash
├── index.html          # Main application file containing structured Tailwind markup
├── README.md           # Documentation for development and deployment
└── images/             # Directory containing local asset resolutions
    ├── luke-witter-k47w6BeapCs-unsplash.jpg
    ├── trainer.png
    ├── personalized.png
    ├── community.png
    ├── mark-deyoung-mjcJ0FFgdWI-unsplash.jpg
    ├── anastase-maragos-FP7cfYPPUKM-unsplash.jpg
    ├── slaapwijsheid-nl-Ip3Z-FoLl1Q-unsplash.jpg
    ├── benjamin-child-rOn57CBgyMo-unsplash.jpg
    └── giorgio-trovato-3c7tpmlJxXo-unsplash.jpg
```

## 🛠️ Built With

- **HTML5:** Modern structural elements (`<header>`, `<section>`, `<footer>`).
- **Tailwind CSS (via CDN):** Component classes for utility-first styling.
- **Google Fonts / Inter-style system:** Clean system type layout.

## 🔧 Optimizations Made During Code Cleanup

1. **Duplicate Document Node Excision:** Removed the dual declaration block of `<!DOCTYPE html>`, `<html lang="en">`, and `<head>` fields present in the original snippet.
2. **Fixed Syntax Class Identifiers:** Swapped React-specific `className` attributes out in favor of proper native DOM `class` properties inside the subscription section layout.
3. **Container Alignment:** Wrapped and resolved missing element closing markers (`</div>`, `</form>`) to avoid layout breaks during browser execution.
4. **Layout Layering Fix:** Added an appropriate tracking margin (`mt-24`) to the main Hero container to prevent the floating sticky navbar from overlapping the top section titles.
