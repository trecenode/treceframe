# 13Frame CSS Framework

<div align="center">

![13Frame Logo](https://img.shields.io/badge/13Frame-v1.0.0-7c3aed?style=for-the-badge)
![License](https://img.shields.io/badge/License-CC_BY_SA_4.0-blue?style=for-the-badge)
![CSS](https://img.shields.io/badge/CSS-Pure-success?style=for-the-badge)

**A modern, accessible CSS framework with stunning glass effects and premium design**

[View Demo](https://trecenode.github.io/treceframe/) • [Documentation](#documentation) • [Getting Started](#getting-started)

</div>

---

## ✨ Features

- 🎨 **Modern Design** - Vibrant gradients, glassmorphism effects, and smooth animations
- 📱 **Fully Responsive** - Mobile-first approach with flexible breakpoints
- ♿ **Accessible** - WCAG compliant with proper focus states and ARIA support
- ⚡ **Lightweight** - Pure CSS, no JavaScript dependencies
- 🛠️ **Easy to Use** - Intuitive `.trece-*` class naming convention
- 🎯 **Complete** - Grid system, components, utilities, and more
- 🌈 **Customizable** - CSS variables for easy theming

## 🚀 Quick Start

### Installation

Include the CSS file in your HTML:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/trecenode/treceframe@main/13frame.css">
```

Or download and include locally:

```html
<link rel="stylesheet" href="path/to/13frame.css">
```

### Optional: Google Fonts

For the best experience, include Inter font:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

### Basic Usage

```html
<div class="trece-container">
    <div class="trece-grid trece-grid-gap-4">
        <div class="trece-col-6 trece-col-sm-12">
            <div class="trece-glass-card">
                <h3 class="trece-card-title">Beautiful Glass Card</h3>
                <p>With modern glassmorphism effects!</p>
                <button class="trece-btn trece-btn-primary">Click Me</button>
            </div>
        </div>
    </div>
</div>
```

## 📚 Documentation

### Grid System

13Frame uses a flexible 12-column grid system:

```html
<div class="trece-grid trece-grid-gap-4">
    <div class="trece-col-6 trece-col-md-12">Half width on desktop, full on tablet</div>
    <div class="trece-col-6 trece-col-md-12">Half width on desktop, full on tablet</div>
</div>
```

**Available columns:** `.trece-col-1` through `.trece-col-12`

**Responsive modifiers:**
- `.trece-col-sm-*` - Mobile (< 768px)
- `.trece-col-md-*` - Tablet (768px - 1024px)
- `.trece-col-lg-*` - Desktop (> 1024px)

**Gap utilities:** `.trece-grid-gap-1` through `.trece-grid-gap-8`

### Cards

Beautiful card components with multiple variants:

```html
<!-- Default Card -->
<div class="trece-card">
    <div class="trece-card-header">
        <h3 class="trece-card-title">Card Title</h3>
        <p class="trece-card-subtitle">Subtitle</p>
    </div>
    <div class="trece-card-body">Content here</div>
    <div class="trece-card-footer">Footer content</div>
</div>
```

**Card variants:**
- `.trece-card` - Default card
- `.trece-card-primary` - Purple gradient
- `.trece-card-secondary` - Blue gradient
- `.trece-card-bordered` - Bordered style
- `.trece-card-elevated` - Enhanced shadow

### Glassmorphism

Modern glass effects with backdrop blur:

```html
<div class="trece-glass-card">Glass card with blur effect</div>
<div class="trece-glass-light">Light glass variant</div>
<div class="trece-glass-dark">Dark glass variant</div>
```

### Buttons

Complete button system with variants and sizes:

```html
<!-- Button Variants -->
<button class="trece-btn trece-btn-primary">Primary</button>
<button class="trece-btn trece-btn-secondary">Secondary</button>
<button class="trece-btn trece-btn-accent">Accent</button>
<button class="trece-btn trece-btn-outline">Outline</button>
<button class="trece-btn trece-btn-ghost">Ghost</button>

<!-- Button Sizes -->
<button class="trece-btn trece-btn-primary trece-btn-sm">Small</button>
<button class="trece-btn trece-btn-primary">Medium</button>
<button class="trece-btn trece-btn-primary trece-btn-lg">Large</button>
<button class="trece-btn trece-btn-primary trece-btn-xl">Extra Large</button>
```

### Forms

Accessible form components:

```html
<div class="trece-form-group">
    <label for="email" class="trece-label">Email Address</label>
    <input type="email" id="email" class="trece-input" placeholder="email@example.com">
    <span class="trece-form-help">We'll never share your email.</span>
</div>

<div class="trece-form-group">
    <label for="message" class="trece-label">Message</label>
    <textarea id="message" class="trece-textarea" placeholder="Your message..."></textarea>
</div>

<div class="trece-form-group">
    <label for="country" class="trece-label">Country</label>
    <select id="country" class="trece-select">
        <option>Select a country</option>
    </select>
</div>
```

**Form states:**
- `.trece-input-error` - Error state
- `.trece-form-error` - Error message
- `.trece-form-help` - Helper text

### Utility Classes

#### Spacing

```html
<!-- Margin -->
.trece-m-{0-8}   <!-- All sides -->
.trece-mt-{0-8}  <!-- Top -->
.trece-mb-{0-8}  <!-- Bottom -->

<!-- Padding -->
.trece-p-{0-8}   <!-- All sides -->
.trece-pt-{0-8}  <!-- Top -->
.trece-pb-{0-8}  <!-- Bottom -->
```

#### Typography

```html
<!-- Text Sizes -->
.trece-text-xs, .trece-text-sm, .trece-text-base, .trece-text-lg
.trece-text-xl, .trece-text-2xl, .trece-text-3xl, .trece-text-4xl
.trece-text-5xl, .trece-text-6xl

<!-- Font Weights -->
.trece-font-normal, .trece-font-medium, .trece-font-semibold, .trece-font-bold

<!-- Text Alignment -->
.trece-text-left, .trece-text-center, .trece-text-right
```

#### Colors

```html
<!-- Text Colors -->
.trece-text-primary, .trece-text-secondary, .trece-text-accent
.trece-text-success, .trece-text-warning, .trece-text-danger

<!-- Background Colors -->
.trece-bg-primary, .trece-bg-secondary, .trece-bg-accent
.trece-bg-dark, .trece-bg-light, .trece-bg-white

<!-- Gradients -->
.trece-gradient-primary, .trece-gradient-secondary
.trece-gradient-sunset, .trece-gradient-ocean
```

#### Flexbox

```html
.trece-flex, .trece-inline-flex
.trece-flex-row, .trece-flex-col
.trece-items-center, .trece-items-start, .trece-items-end
.trece-justify-center, .trece-justify-between, .trece-justify-around
.trece-gap-{1-6}
```

#### Other Utilities

```html
<!-- Border Radius -->
.trece-rounded-sm, .trece-rounded, .trece-rounded-lg
.trece-rounded-xl, .trece-rounded-2xl, .trece-rounded-full

<!-- Shadows -->
.trece-shadow-sm, .trece-shadow, .trece-shadow-lg
.trece-shadow-xl, .trece-shadow-2xl

<!-- Transitions -->
.trece-transition, .trece-transition-fast, .trece-transition-slow

<!-- Hover Effects -->
.trece-hover-lift, .trece-hover-scale
```

## 🎨 Customization

All design tokens are defined as CSS variables. Override them to customize:

```css
:root {
  /* Colors */
  --trece-primary: hsl(260, 80%, 60%);
  --trece-secondary: hsl(200, 90%, 55%);
  --trece-accent: hsl(340, 85%, 60%);
  
  /* Spacing */
  --trece-space-4: 1rem;
  
  /* Typography */
  --trece-font-sans: 'Your Font', sans-serif;
  --trece-text-base: 1rem;
  
  /* Border Radius */
  --trece-radius-lg: 0.75rem;
  
  /* And many more... */
}
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

**Note:** Glassmorphism effects require `backdrop-filter` support.

## 📦 What's Included

```
treceframe/
├── 13frame.css      # Core framework (~30KB)
├── index.html       # Showcase & documentation
└── README.md        # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

**13Frame** is created and maintained by [13node](https://github.com/trecenode).

### Usage Terms

✅ **Free to use** in both personal and commercial projects  
✅ **Modify** and customize as needed  
✅ **Distribute** in your projects  

**Attribution Required:** Please include credit to 13node in your project documentation or footer:

```html
<!-- Example attribution -->
<p>Built with <a href="https://github.com/trecenode/treceframe">13Frame</a> by 13node</p>
```

**Copyright © 2025 13node. All rights reserved.**

---

## 🔗 Links

- **GitHub:** [github.com/trecenode](https://github.com/trecenode)
- **Twitter/X:** [@13node_es](https://x.com/13node_es)
- **Instagram:** [@13node](https://www.instagram.com/13node)

---

<div align="center">

**Made with ❤️ by [13node](https://github.com/trecenode)**

If you find this framework useful, please give it a ⭐ on GitHub!

</div>
