# CSS Components Showcase

A premium-looking collection of clean, responsive, and reusable CSS-only components designed for modern UI development.

## 🚀 Project Overview

The **CSS Components Showcase** is a lightweight, zero-dependency library of interactive user interface elements. Built with pure HTML5 and CSS3, it offers developers a reference layout and copyable snippets to implement high-quality visual components in any web project without framework overhead.

## 🛠️ Technologies Used

*   **HTML5**: Semantic elements and responsive structure.
*   **CSS3**: CSS Custom Variables, CSS Grid, Flexbox layouts, dynamic animations, backdrop filters, and custom transitions.
*   **Vanilla JavaScript**: Extremely lightweight clipboard copy interactions and scroll state tracking.

## 📂 Folder Structure

```text
/
├── index.html       # The main interface, navigation layout, component structures, and code viewers.
├── style.css        # The complete styling system, theme colors, responsive grids, and components.
└── README.md        # Documentation, running instructions, and future roadmap.
```

## 🎨 Design System Overview

The showcase uses a dark, slate-blue neon theme with customized accents:
*   **Backgrounds**: Dark space slate (`#080b11`) and card containers (`#0f141c`).
*   **Typography**: *Outfit* for modern headlines/text, and *Fira Code* for monospace styling of code snippets.
*   **Accents**: Indigo (`#6366f1`) for main focus/primary buttons, violet/purple (`#a855f7`) for gradient layouts, and neon cyan (`#06b6d4`) for alerts, neon glows, and active states.
*   **Transitions**: Fluid cubic-bezier timing (`cubic-bezier(0.4, 0, 0.2, 1)`) used globally to deliver micro-interactions.

## 🛠️ Component Breakdown (Version 1)

### 1. Buttons (6)
*   **Primary Button**: Standard CTA button with hover elevation and shadow expansion.
*   **Secondary Button**: Muted card-toned border button with hover scaling.
*   **Outline Button**: Clean stroke-based button that transitions to a solid background fill.
*   **Gradient Button**: Dual-color backplate with moving background position on hover.
*   **Neon Glow Button**: Intense cyan glow shadow that scales and illuminates on mouse-over.
*   **Sliding Fill Button**: Button using pseudo-elements to slide a background overlay block from left to right.

### 2. Cards (3)
*   **Simple Card**: Classic box element with rounded borders and hover translation (lift).
*   **Glassmorphism Card**: Semi-transparent border card using backdrop blur filters to show background elements.
*   **Gradient Border Card**: Card with continuous linear gradient borders using overlay techniques.

### 3. Inputs (3)
*   **Minimal Input**: Inline bottom border input featuring label float adjustments.
*   **Floating Label Input**: Floating text input that shifts size and alignment on focus.
*   **Glowing Focus Input**: Standard field transitioning to an intense indigo focus box-shadow.

### 4. Loaders (3)
*   **Spinner Loader**: Infinite gradient ring spinning animation.
*   **Three Dots Loader**: Sequential bouncing loader using animation delays.
*   **Pulse Loader**: Twin expanding pulse rings that fade in opacity.

## ⚙️ How to Run

1.  **Clone or Download** the folder structure into your local system.
2.  **Open `index.html`** in any modern web browser:
    *   Double-click the file to open it directly.
    *   Alternatively, run it using a local development server (such as VS Code's *Live Server* extension or python's `http.server` command: `python -m http.server`).

## 🔮 Planned Future Components (Version 2+)

*   Navigation Bars
*   Modals
*   Pricing Cards
*   Hero Sections
*   Tooltips
*   Accordions
*   Badges
*   Alerts
*   Tables
*   Timelines
*   Progress Bars
*   Avatars
*   Dropdowns
*   Tabs
*   Pagination
*   Breadcrumbs
*   Skeleton Loaders
*   Toast Notifications
*   Switches
*   Checkboxes
