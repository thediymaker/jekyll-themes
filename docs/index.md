---
layout: mac
title: GOOD 2025 HPC Dashboard Tutorial
permalink: /tutorial/good/2025/
---

<link rel="stylesheet" href="tutorial-style.css">
<script src="tutorial-script.js" defer></script>

# Tutorial Theme

A clean, modern theme for technical documentation and tutorials with special emphasis on readability and information hierarchy.

![version](https://img.shields.io/badge/version-2.1.0-blue)
![license](https://img.shields.io/badge/license-MIT-green)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/tutorial-theme?style=social)](https://github.com/yourusername/tutorial-theme)

## Features

This theme includes various styled components to enhance documentation readability:

- Styled code blocks with copy functionality
- Information boxes with distinct visual styles for different content types
- Clean typography optimized for technical content
- Responsive design for all devices
- Easy customization via CSS variables

## Demo

### Information Boxes

The theme includes several types of styled information boxes to highlight different types of content:

#### Note Box

```html
<div class="note-box">
<strong>Note:</strong> This is important information that deserves attention but isn't crucial.
</div>
```

Renders as:

<p align="center">
  <img src="screenshots/note-box.png" alt="Note Box" width="600">
</p>

#### Warning Box

```html
<div class="warning-box">
<strong>Warning:</strong> This highlights potential issues or dangers the user should be aware of.
</div>
```

Renders as:

<p align="center">
  <img src="screenshots/warning-box.png" alt="Warning Box" width="600">
</p>

#### Explanation Box

```html
<div class="explanation-box">
<strong>Explanation:</strong> This provides additional context or details about a concept.
</div>
```

Renders as:

<p align="center">
  <img src="screenshots/explanation-box.png" alt="Explanation Box" width="600">
</p>

#### Notice Box

```html
<div class="notice-box">
<strong>Notice:</strong> This highlights announcements or special considerations.
</div>
```

Renders as:

<p align="center">
  <img src="screenshots/notice-box.png" alt="Notice Box" width="600">
</p>

### Code Blocks

Code blocks come with syntax highlighting and a copy button:

```html
<div class="code-container">
<pre class="code-block"><code>npm install tutorial-theme</code></pre>
<button class="copy-button" onclick="copyToClipboard(this)" aria-label="Copy code"></button>
</div>
```

Renders as:

<p align="center">
  <img src="screenshots/code-block.png" alt="Code Block with Copy Button" width="600">
</p>

## Installation

1. Add the stylesheet to your HTML:

```html
<link rel="stylesheet" href="tutorial-style.css">
```

2. Add the JavaScript for interactive elements:

```html
<script src="tutorial-script.js" defer></script>
```

3. Optional: Add GitHub buttons script if you're using GitHub buttons:

```html
<script async defer src="https://buttons.github.io/buttons.js"></script>
```

## Usage

### Basic Structure

```html
---
layout: default
title: Your Tutorial Title
---

<link rel="stylesheet" href="tutorial-style.css">
<script src="tutorial-script.js" defer></script>

# Tutorial Title

Welcome to this tutorial! This will guide you through...

<div class="note-box">
<strong>Note:</strong> Important information goes here.
</div>

## Step 1: Installation

<div class="code-container">
<pre class="code-block"><code>npm install your-package</code></pre>
<button class="copy-button" onclick="copyToClipboard(this)" aria-label="Copy code"></button>
</div>

<div class="explanation-box">
<strong>Explanation:</strong> This installs the package you need.
</div>
```

### CSS Variables for Customization

You can customize the theme by overriding these CSS variables:

```css
:root {
  --primary-color: #007bff;
  --warning-color: #dc3545;
  --note-color: #17a2b8;
  --explanation-color: #6610f2;
  --notice-color: #ffc107;
  
  --box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  --border-radius: 6px;
  
  --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  --code-font-family: 'Courier New', Courier, monospace;
}
```

## Files Included

- `tutorial-style.css` - Main stylesheet
- `tutorial-script.js` - JavaScript for interactive elements
- `README.md` - Documentation
- Example tutorial files

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
Made with ❤️ for better documentation
</p>