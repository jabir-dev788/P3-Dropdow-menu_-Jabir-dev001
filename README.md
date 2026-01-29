# Modern Dropdown Navigation Menu

A fully responsive, accessible, and production-ready dropdown navigation menu built with HTML5 and CSS3.

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Multi-level Dropdowns** - Supports nested dropdown menus with smooth animations
- **Accessibility** - Semantic HTML with ARIA labels for screen readers
- **Modern Styling** - Clean, professional design with smooth transitions
- **CSS Variables** - Easy to customize colors and spacing
- **No Dependencies** - Pure HTML & CSS with Font Awesome for icons
- **Sticky Navigation** - Navigation stays at top while scrolling
- **Cross-browser Compatible** - Works on all modern browsers

## 📂 Project Structure

```
├── HOME-portfolio.html      # HTML file with menu structure
├── STYLE-portfolio.css      # Main stylesheet with responsive design
└── README.md                # Documentation
```

## 🚀 Quick Start

### Installation

1. **Clone the repository:**
```bash
git clone [https://github.com/yourusername/dropdown-menu.git](https://github.com/jabir-dev788/P3-Dropdow-menu_-Jabir-dev001.git)
cd P3-Dropdow-menu_-Jabir-dev001
```

2. **Open in your browser:**
- Simply open `HOME-portfolio.html` in your web browser
- Or use a local server: `python -m http.server` (Python 3)

## 🎨 Customization

### Change Colors

Edit the CSS variables in `STYLE-portfolio.css`:

```css
:root {
	--primary-color: #2bab0d;      /* Main menu color */
	--primary-dark: rgb(0, 100, 0); /* Dark background */
	--text-light: #fff;            /* Light text */
	--hover-color: #237a09;        /* Hover state color */
}
```

### Modify Spacing

Adjust spacing values:

```css
:root {
	--spacing-sm: 10px;   /* Small spacing */
	--spacing-md: 15px;   /* Medium spacing */
	--spacing-lg: 20px;   /* Large spacing */
}
```

### Adjust Animation Speed

Change the transition duration:

```css
:root {
	--transition: all 0.3s ease; /* Adjust 0.3s to your preference */
}
```

## 🏗️ HTML Structure

```html
<div class="menu-bar">
  <nav aria-labelledby="primary navigation">
    <ul>
      <li><a href="#">Home</a></li>
      <li>
        <a href="#">Services</a>
        <div class="sub-menu-1">
          <ul>
            <li><a href="#">Option 1</a></li>
            <li><a href="#">Option 2</a></li>
          </ul>
        </div>
      </li>
    </ul>
  </nav>
</div>
```

## 📱 Responsive Breakpoints

- **Desktop**: Full horizontal menu with hover dropdowns
- **Tablet & Mobile (< 768px)**: Vertical layout with improved touch targets

## ♿ Accessibility Features

- Semantic HTML5 structure
- ARIA labels for navigation
- Font Awesome icons for visual enhancement
- Keyboard navigable
- High contrast colors for readability

## 🔧 Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Usage Tips

1. **Add Font Awesome Icons**: Use the `<i>` tag with Font Awesome classes:
   ```html
   <i class="fa fa-home"></i> Home
   ```

2. **Make Item Active**: Add the `active` class:
   ```html
   <li class="active"><a href="#">Home</a></li>
   ```

3. **Add Nested Dropdowns**: Wrap level-2 menus with `sub-menu-2` class

## 📝 Code Quality

- Clean, commented CSS
- Organized with sections
- CSS Variables for maintainability
- BEM-inspired naming convention
- No unnecessary classes or HTML elements

## 🤝 Contributing

Want to improve this project? 

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License - feel free to use it for personal and commercial projects.

## 👨‍💻 Author

Created by Jabir Zakariyyya

## 🐛 Issues & Support

Found a bug or have a suggestion? [Open an issue](https://github.com/jabir-dev788/P3-Dropdow-menu_-Jabir-dev001/issues)

---

**Made with ❤️ for developers everywhere**
