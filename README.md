# Spicy Hut - Modern Restaurant Website

A responsive, elegant, and interactive single-page landing ecosystem tailored for **Spicy Hut**, showcasing premium multi-cuisine vegetarian operations. The system is built with native semantic HTML5 layouts, robust centralized CSS3 custom component variables, complex pseudo-elements, and high-performance JavaScript integration handling smooth hardware-accelerated scroll animations.

## 🚀 Live Demo

Check out the live application here: **[Live Demo Link](https://mathewjebis.github.io/RESTAURANT/)** 

## 🛠️ Built With

- **HTML5**: Structural semantic layouts (`<header>`, `<nav>`, `<address>`, `<footer>`) maximizing document hierarchy.
- **CSS3 Variables & Grid**: Built on an auto-fitting CSS Grid model, responsive flexible box layouts, blur filters, custom theme definitions, and hardware-accelerated fluid micro-interactions.
- **JavaScript (ES6+)**: Intersection Observers, performance-optimized scroll triggers, window event listeners, and dynamic DOM token list overrides.
- **Font Awesome (v6.5.0)**: Embedded typography iconography linked through safe external web standard CDN pathways.

## ✨ Technical Architecture & Styling Features

### ⚙️ JavaScript Interaction & Scroll Animations

- **High-Performance Fade-Ins**: Uses the modern **Intersection Observer API** to gracefully animate menu grids and location cards on scroll. Components begin at `opacity: 0` and are lifted via a `translateY(20px)` transformation matrix. They snap cleanly to their base state (`opacity: 1`, `translateY(0)`) once 10% of the item enters the active viewport threshold.
- **Auto-Unobserve Processing**: To save device memory and runtime performance, the script explicitly detaches elements from the layout listener tracker once their intro animation has completed.
- **Asynchronous Mobile Overlay Toggles**: Tapping the hamburger button updates classes asynchronously (`.open`). Clicking any internal anchor link triggers an automatic listener cleanup that closes the full-screen display overlay.
- **Dynamic Sticky Header Shadows**: Listens globally to window scroll positions. If the scroll vertical offset surpasses `50px`, the JavaScript automatically applies a soft ambient bottom drop-shadow layer (`rgba(0,0,0,0.5)`) over the navbar, returning to flush-flat defaults if you scroll back to the top of the landing zone.

### 🎨 Modular CSS3 Configuration Variable Matrix

The design architecture is styled out using structural, pre-compiled global custom properties (`:root`) for instant, site-wide layout color tracking:

- `--red (#dc2626)`: Primary accent handles, badges, headers, and indicator underlines.
- `--green (#538f9d)`: Pricing numbers, visual location tags, and direct branch calls.
- `--yellow (#ffc54d)`: Header logo signatures, category tables, and anchor links.
- `--dark / --dark2 / --dark3`: Multi-layered deep slate background canvas block layout.

### 💎 Premium Translucent UI Glassmorphism

- **Dynamic Blur Layers**: The header tracks sticky alignments directly across scrolling layouts via active `position: sticky` and implements clean alpha-channel translucent backdrop filtering (`backdrop-filter: blur(10px)`).
- **Hero Image Integration**: Features a parallax-ready cover element powered by double-layered composite linear tracking overlays (`linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55))`) to keep text readable against high-contrast assets.

### 📋 Responsive Grid Mechanics

- **Auto-Fitting Menus**: Category tables map cleanly across auto-wrapping grids (`grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))`) to seamlessly reorganize content grids.
- **Asynchronous Keyframe Bouncers**: A custom endless translation framework (`@keyframes bounce`) guides user flow downward toward table data panels.

## 📦 Project Structure

```text
├── index.html          # Structural templates, menu item matrix, and address tags
├── index.css           # Custom property declarations, grid parameters, and web variables
└── index.js            # Intersection observers, viewport tracking, and shadow listeners
```

## 💻 Setup & Installation

To run this project locally, simply follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mathewjebis/RESTAURANT.git
   ```

2. **Navigate to the project folder:**

   ```bash
   cd your-repository-name
   ```

3. **Open the project:**
   - Double-click `index.html` to run the project directly inside your local web browser.
   - Alternatively, right-click and open via the **Live Server** extension in VS Code for real-time live-reloading style changes.
