# Dog Nutrition Feature Section – Technical Test

This is a front-end implementation of a homepage section based on a design mockup provided by the employer. The section highlights the unique benefits of the dog food brand and is built to match the visual and functional layout as closely as possible.

---

## 📌 Overview

This section includes:

- A responsive three-column layout
- Feature icons and descriptions
- A center circular image (static or optionally draggable for interaction)
- A call-to-action (CTA) button and payment method visuals
- Nutrition statistics and content blocks
- A clean, modular layout ready for integration into any WordPress or Shopify theme

---

## 🛠️ Tools & Technologies

- **HTML5**
- **CSS3 (Flexbox Layout)**
- **Custom CSS (No frameworks used)**
- **Fully mobile-responsive**
- Optional JS (for interactive slider, if enabled)

---

## 📂 Folder Structure

project/
│
├── index.html # Main HTML file
├── style.css # All layout and component styling
├── script.js # (Optional) Slider interaction (not active in final build)
│
├── /images/ # Optimized image assets (PNG, JPG, SVG)
│ ├── Frame 1171276495.png # Central dog bowl image
│ ├── Rectangle 7.png # Sectional images
│ └── ... # Other graphics
│
├── /icons/ # Feature icons
│ ├── food 1.png
│ ├── pet-bowl 1.png
│ └── ...
│
└── README.md # This file

---

## 🖼️ Design Reference

The layout is implemented to closely match the provided visual design (`Frame 1171276402.jpg`). It ensures:

- Visual balance across all screen sizes
- Typography and spacing consistency
- Accurate icon placement
- Matching button, icon, and image dimensions

---

## ⚙️ How to Use

### Open in Browser

1. Download or clone the repository.
2. Open `index.html` in any browser.

### For WordPress or Shopify Integration

- The layout can be wrapped inside a shortcode or custom section.
- Image paths can be swapped with dynamic URLs (e.g., `{{ asset('...') }}` or `<?php echo get_template_directory_uri(); ?>`).

---

## 🔧 Optional Enhancement (Not Enabled)

There is an optional **slider feature** that makes the dog bowl image interactive (split-screen effect). It was disabled in the final build for simplicity but can be enabled by uncommenting the JavaScript in `script.js`.

---

## 📬 Contact

If you have questions or need clarification on any section of this test, feel free to reach out.

Thanks for the opportunity!
