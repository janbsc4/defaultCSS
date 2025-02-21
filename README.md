# How to Use defaultCSS

DefaultCSS is a CSS starting point that includes a minimal styling for the most used html tags.
No tailwind, sass or bootstrap needed. Pure CSS.
[Demo here](https://janbsc4.github.io/defaultCSS/).

Includes:
- Automatic dark mode
- Mobile friendly
- Easy to understand and change custom variables at the start

## Quick Start (CDN)
Add this line in your HTML's `<head>` section:
```html
<link rel="stylesheet" href="https://janbsc4.github.io/defaultCSS/defaultCSS.css">
```

## Alternative Methods

### Local Download
1. Download the CSS file:
   ```bash
   curl -O https://janbsc4.github.io/defaultCSS/defaultCSS.css
   ```
2. Place it in your project directory
3. Link it in your HTML:
   ```html
   <link rel="stylesheet" href="path/to/defaultCSS.css">
   ```

### Git Submodule
If your project uses Git:
```bash
git submodule add https://github.com/janbsc4/defaultCSS.git
```

## Customization
To customize the default variables, add this to your own CSS file:
```css
:root {
    --primary-color: #your-color;
    --hover-color: #your-hover-color;
    --text-color: #your-text-color;
    /* Add any other variables you want to override */
}
```

## Browser Support
- Works with all modern browsers
- Includes dark mode support via `prefers-color-scheme`
- Responsive design included

## Note
Make sure to include this CSS file before any custom stylesheets to allow proper overriding of styles.

## Contributing
Contributions are welcome! Here's how you can help improve the default CSS:

1. Fork the repository on GitHub
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Test your changes thoroughly
5. Commit with a clear message:
   ```bash
   git commit -m "Add: brief description of your changes"
   ```
6. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. Create a Pull Request with:
   - Clear description of changes
   - Screenshots if visual changes were made

### Guidelines
- Keep it extremely simple and maintainable
- Follow existing code style
- Test across different browsers and devices

### Issues
Found a bug or have a suggestion? Open an issue on GitHub with:
- Clear description
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots if applicable
