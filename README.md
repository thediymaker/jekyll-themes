# Tutorial Theme for GitHub Pages

A clean, interactive theme for technical tutorials and documentation on GitHub Pages with styled information boxes and code blocks.

![Theme Preview](preview.png)

## Quick Start

1. **Fork or clone this repository**

2. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Select the branch to deploy (usually `main` or `master`)
   - Choose the `/ (root)` folder
   - Click Save

3. **Create your tutorial**
   - Edit the existing `index.md` or create new markdown files
   - Add YAML front matter to each page:
     ```yaml
     ---
     layout: tutorial
     title: Your Tutorial Title
     ---
     ```

4. **Use the theme components**

   ```markdown
   # My Tutorial

   Welcome to this guide!

   <div class="note-box">
   <strong>Note:</strong> Important information here.
   </div>

   ## Installation

   <div class="code-container">
   <pre class="code-block"><code>npm install my-package</code></pre>
   <button class="copy-button" onclick="copyToClipboard(this)" aria-label="Copy code"></button>
   </div>

   <div class="warning-box">
   <strong>Warning:</strong> Be careful about this step.
   </div>
   ```

## Available Components

- **Note Box**: `<div class="note-box">...</div>`
- **Warning Box**: `<div class="warning-box">...</div>`
- **Explanation Box**: `<div class="explanation-box">...</div>`
- **Notice Box**: `<div class="notice-box">...</div>`
- **Code Block**:
  ```html
  <div class="code-container">
  <pre class="code-block"><code>your code here</code></pre>
  <button class="copy-button" onclick="copyToClipboard(this)" aria-label="Copy code"></button>
  </div>
  ```

## Customization

Modify `_config.yml` to change site-wide settings:

```yaml
title: Your Site Title
description: Your site description
theme_color: "#007bff"
```

## License

MIT
