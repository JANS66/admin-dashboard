# Dashboard Project

A modern, responsive dashboard application with a sleek dark theme, featuring project management, announcements, and trending sections.

## Features

- **Responsive Design** - Fully responsive layout that adapts to desktop, tablet, and mobile devices
- **Dark Theme** - Modern dark color scheme optimized for readability and reduced eye strain
- **Sidebar Navigation** - Persistent sidebar with primary and secondary navigation links
- **Project Cards** - Grid-based project display with hover effects
- **Announcements Panel** - Dedicated section for site-wide announcements
- **Trending Section** - Highlights popular projects and users
- **Security-First** - Includes Content Security Policy headers for enhanced protection

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Responsive Design (Mobile-first approach)

## Color Palette

The application uses a carefully crafted dark theme:

- Background: `#0f172a`
- Sidebar: `#0b1120`
- Cards: `#1e293b`
- Accent: `#38bdf8` (Sky Blue)
- Text: `#f1f5f9`
- Muted Text: `#94a3b8`
- Border: `#334155`

## Layout Structure

```
├── Sidebar
│   ├── Logo
│   ├── Primary Navigation (Home, Profile, Messages, History, Tasks, Communities)
│   └── Secondary Navigation (Settings, Support, Privacy)
│
└── Main Content
    ├── Header
    │   ├── Search Bar
    │   └── User Profile
    ├── Projects Grid (6 project cards)
    └── Right Panel
        ├── Announcements
        └── Trending
```

## Responsive Breakpoints

- **Desktop**: Full layout with sidebar (1024px+)
- **Tablet**: Compressed sidebar (768px - 1024px)
- **Mobile**: Sidebar hidden, single column layout (<768px)

## Accessibility Features

- Semantic HTML elements (`<nav>`, `<aside>`, `<article>`, `<section>`)
- ARIA labels for navigation landmarks
- Alt text for images
- Proper heading hierarchy
- Focus-visible states for interactive elements

## Security

The application implements a Content Security Policy (CSP) that:
- Restricts content sources to same-origin
- Allows images from pravatar.cc for avatars
- Prevents inline scripts and styles
- Blocks object embeds
- Restricts form actions

## Browser Support

Compatible with all modern browsers supporting CSS Grid and Custom Properties:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## Getting Started

1. Clone or download the project files
2. Open `index.html` in a web browser
3. No build process or dependencies required

## File Structure

```
project/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
└── README.md          # Project documentation
```

## Customization

To customize the color scheme, modify the CSS custom properties in `:root`:

```css
:root {
    --background: #0f172a;
    --accent: #38bdf8;
    /* ... other colors */
}
```

## Future Enhancements

- JavaScript interactivity for buttons and navigation
- Dynamic project loading
- User authentication
- Real-time announcements
- Dark/light theme toggle
- Enhanced accessibility features

## License

This project is open source and available for personal and commercial use.