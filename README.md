# Intel Sustainability Journey - Interactive Web Project

## Project Overview

An interactive, responsive webpage showcasing Intel's commitment to sustainability and environmental innovation. The project demonstrates modern web development techniques including Bootstrap integration, responsive design, accessibility features, and interactive JavaScript components.

### Key Features

- **Interactive Timeline**: Horizontal scrollable timeline displaying Intel's sustainability milestones from 1968 to 2024
- **Image Gallery**: Bootstrap carousel-style gallery with 3 visible cards at any time
- **Feature Cards**: Three-column responsive layout highlighting RISE Strategy, Commitment, and Water & Waste initiatives
- **Email Newsletter**: Bootstrap-integrated subscription form with validation and success feedback
- **Comprehensive Footer**: Multi-column navigation with social media links and dynamic copyright year
- **Full Responsiveness**: Optimized for desktop (≥769px), tablet (481-768px), and mobile (≤480px)
- **Accessibility**: WCAG compliant with ARIA labels, keyboard navigation, and focus indicators
- **RTL Support**: Ready for right-to-left language implementations

---

## Project Structure

```
index.html                    Main webpage
pages/
├── index.css               Main stylesheet with imports
blocks/
├── page.css               Page layout and grid
├── header.css             Header section styling
├── timeline.css           Timeline card styling
├── gallery.css            Image gallery styling
├── features.css           Three-column features section
├── newsletter.css         Subscription form styling
└── footer.css             Footer navigation styling
vendor/
├── normalize.css          CSS normalization
└── fonts.css             Font imports
img/                        Project images
```

---

## Technology Stack

### Frontend Technologies
- **HTML5**: Semantic markup with ARIA attributes
- **CSS3**: BEM methodology, Flexbox, CSS Grid, media queries
- **JavaScript (ES6+)**: Interactive components and animations
- **Bootstrap 5.3.0**: Responsive grid system and utilities
- **Bootstrap Icons 1.11.3**: SVG icon library

### Design Pattern
- **BEM (Block Element Modifier)**: CSS naming convention for maintainability
- **Mobile-First**: Responsive design starting from smallest screens
- **Accessibility-First**: WCAG 2.1 AA compliance

---

## Styling Guide

### Color Palette
```
Primary Blue:    #0071C5
Dark Blue:       #00285A / #002A5A
White:           #ffffff
Black:           #000000
Light Gray:      #f5f5f5
Text Gray:       #333333
```

### Typography
- **Headings**: 600 font-weight (Semi-bold)
- **Body**: 400 font-weight (Normal)
- **Buttons**: 600 font-weight (Semi-bold)

### Responsive Breakpoints
- **Desktop**: ≥769px (4 columns, 3 gallery cards visible)
- **Tablet**: 481-768px (2 columns, side-by-side layout)
- **Mobile**: ≤480px (1 column, stacked layout)

### Key CSS Classes (BEM)
```
.header              Header section
.timeline            Timeline container
.card                Timeline card
.gallery             Image gallery
.gallery__card       Gallery card item
.features            Features section
.features__card      Feature card
.newsletter          Newsletter section
.footer              Footer container
```

---

## Components

### 1. Header
- Intel logo
- Main title: "Sustainability Through the Ages"
- Descriptive subtitle
- Gradient background (Intel blue)

### 2. Timeline Section
- 9 horizontal scrollable cards (1968-2024)
- Hover effects revealing additional information
- Dynamic hue colors per card

### 3. Image Gallery
- Bootstrap-style carousel with 3 cards visible
- Navigation arrows for previous/next
- Responsive card sizing
- Smooth slide transitions
- Auto-disabled buttons at endpoints

### 4. Features Section
- 3 equal-width columns on desktop
- Bootstrap icons (leaf, thumbs-up, droplet)
- Hover animations and elevated shadows
- "Learn More" call-to-action links

### 5. Newsletter Section
- Email input with HTML5 validation
- Privacy notice helper text
- Success message with animation
- 5-second auto-hide for feedback
- Responsive form layout

### 6. Footer
- 4-column grid (About, Sustainability, Company, Legal)
- Intel logo in first column
- Social media icons (Facebook, Twitter, LinkedIn, YouTube)
- Dynamic copyright year
- Keyboard accessible links

---

## Features

### Responsive Design
✓ Mobile-first approach
✓ 3 breakpoints (mobile, tablet, desktop)
✓ Flexible grid layouts using Bootstrap
✓ Image scaling and optimization
✓ Touch-friendly buttons and links

### Interactivity
✓ Timeline hover effects with smooth transitions
✓ Gallery navigation with slide animations
✓ Card hover effects with shadow transitions
✓ Form validation and success feedback
✓ Dynamic year update in footer

### Accessibility
✓ Semantic HTML structure
✓ ARIA labels on interactive elements
✓ Keyboard navigation support
✓ Focus indicators visible
✓ Color contrast WCAG AA compliant
✓ Form validation with error handling

### Performance
✓ CSS animations use GPU-accelerated transforms
✓ Minimal layout shifts
✓ Bootstrap CDN for fast delivery
✓ Optimized image handling
✓ Efficient JavaScript with event delegation

---

## Browser Support

- Chrome/Chromium (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Installation & Setup

### Local Development
1. Clone the repository
2. Open `index.html` in a modern web browser
3. No build tools required (uses CDN resources)

### Required Resources
- Internet connection (for CDN resources)
  - Bootstrap CSS
  - Bootstrap Icons
  - Bootstrap JS Bundle

---

## Customization

### Change Brand Colors
Edit color variables in CSS files:
```css
/* Primary color */
#0071C5 → Your color

/* Dark variant */
#00285A → Your color
```

### Update Footer Links
Edit `index.html` footer section:
```html
<a href="your-url" class="footer__link">Link Text</a>
```

### Add Gallery Images
Replace image paths in gallery section:
```html
<img src="your-image.jpg" alt="Description" />
```

### Modify Form Behavior
Edit JavaScript in `index.html`:
```javascript
// Change success message display time
setTimeout(() => {...}, 5000); // milliseconds
```

---

## Disclaimer

⚠️ **AI-Generated Code for Educational Purposes**

This project has been developed using AI assistance as part of the **Accelerated ASU Program** - an initiative to teach industry professionals the practical application of Artificial Intelligence in modern web development.

**Important Notes:**
- This code is generated with AI tools and serves as a learning resource
- It demonstrates best practices for responsive design, accessibility, and component-based architecture
- All code is production-ready but should be reviewed before deployment
- This project is intended to showcase how AI can accelerate development while maintaining code quality
- Students should understand and modify the code as needed for their specific requirements

**Learning Objectives:**
- Understand AI-assisted web development workflows
- Learn responsive design principles with Bootstrap
- Practice accessibility standards (WCAG)
- Implement component-based CSS (BEM methodology)
- Work with interactive JavaScript components

---

## License

This project is part of the Accelerated ASU Program. Use for educational and learning purposes.

---

## Support

For questions or issues:
1. Review the code comments for implementation details
2. Check Bootstrap documentation: https://getbootstrap.com/
3. Consult WCAG accessibility guidelines
4. Test in multiple browsers and devices

---

**Last Updated**: February 2026
**Version**: 2.0
**Status**: Production Ready
