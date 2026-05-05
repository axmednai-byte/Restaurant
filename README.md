# Timeless - Luxury Venue Website

A premium, multi-page luxury venue website combining fine dining, bespoke weddings, and private event services. Built with pure HTML5, CSS3, and vanilla JavaScript following a sophisticated design system inspired by Mastercard, Apple, and Airbnb aesthetics.

## 🎯 Features

### Pages
- **Homepage** - Hero carousel, experience showcase, testimonials, newsletter
- **Restaurant** - Menu tabs, chef profile, reservation system, awards
- **Weddings** - Services, packages, gallery, inquiry form
- **Private Parties** - Event types, amenities, gallery, inquiry form
- **Gallery** - Filterable masonry with lightbox
- **Contact** - Contact form, location info, hours
- **Footer** - Global navigation and social links

### Interactive Components
- ✅ Auto-rotating hero carousel with keyboard/touch navigation
- ✅ Testimonial carousel with auto-advance
- ✅ Filterable gallery with lightbox viewer
- ✅ Menu tab system with smooth transitions
- ✅ Form validation with error feedback
- ✅ Smooth scroll animations via Intersection Observer
- ✅ Sticky navigation with active link tracking
- ✅ Mobile hamburger menu

### Design System
- **Colors**: Warm cream canvas, deep burgundy primary, champagne gold accents
- **Typography**: Playfair Display (serif) for headlines, Inter (sans-serif) for body
- **Components**: Glass-morphism nav, pill buttons, circular image containers
- **Spacing**: 8-level scale (4px to 120px sections)
- **Shadows**: Multi-layer depth with card and elevated variants
- **Radius**: 24px cards, 40px heroes, pill-shaped interactive elements

### Accessibility & Performance
- ✅ Semantic HTML5 with ARIA labels
- ✅ Keyboard navigation throughout
- ✅ Reduced motion support
- ✅ JSON-LD structured data (LocalBusiness, Restaurant, EventVenue)
- ✅ Mobile-first responsive design (480px, 768px, 1024px, 1440px breakpoints)
- ✅ Optimized images and CSS
- ✅ Fast page loads with lazy loading support

## 🚀 Quick Start

### Local Development (No Setup Required)
1. Clone this repository
2. Open `index.html` in your browser
3. That's it! No build tools or dependencies needed.

### Docker Deployment

**Prerequisites**: Docker Desktop installed and running

```bash
# Build and start the container
docker-compose up --build

# Visit the site at http://localhost:8080
```

### Production Deployment

Deploy the entire `Restaurant/` folder to any static hosting:
- **Vercel**: Drag-and-drop deploy
- **Netlify**: Connect GitHub repo
- **AWS S3**: Upload and enable static hosting
- **GitHub Pages**: Push to gh-pages branch
- **Traditional hosting**: FTP/SFTP the files

## 📁 Project Structure

```
Restaurant/
├── index.html                 # Homepage
├── restaurant.html            # Restaurant & Bar page
├── weddings.html              # Wedding venue page
├── parties.html               # Private events page
├── gallery.html               # Photo gallery
├── contact.html               # Contact page
├── css/
│   ├── reset.css              # CSS reset and base styles
│   ├── design-system.css      # Design system tokens and utilities
│   ├── components.css         # Reusable component styles
│   └── pages.css              # Page-specific styles
├── js/
│   ├── main.js                # Core functionality (nav, scroll effects)
│   ├── carousel.js            # Carousel and testimonial logic
│   ├── animations.js          # Gallery filters, lightbox, transitions
│   └── forms.js               # Form validation and submission
├── Dockerfile                 # Docker container configuration
├── docker-compose.yml         # Docker Compose setup
├── nginx.conf                 # Nginx server configuration
├── .dockerignore              # Docker build exclusions
└── README.md                  # This file
```

## 🎨 Design System Reference

### Colors
```css
--color-canvas: #F9F6F0          /* Warm cream background */
--color-ink: #2B2B2B             /* Warm charcoal text */
--color-primary: #8B1E3F         /* Deep burgundy CTAs */
--color-accent: #D4AF37          /* Champagne gold accents */
```

### Typography
```css
Headlines: 'Playfair Display', serif (weight: 500, letter-spacing: -0.02em)
Body: 'Inter', sans-serif (weight: 400, line-height: 1.6)
Labels: 'Inter', sans-serif (weight: 600, letter-spacing: 1.5px, uppercase)
```

### Spacing Scale
```css
4px (xs) | 8px (sm) | 16px (md) | 24px (lg) | 40px (xl) | 64px (2xl) | 120px (section)
```

## 🛠️ Customization

### Change Brand Colors
Edit `css/design-system.css`:
```css
:root {
    --color-primary: #YOUR_COLOR;
    --color-accent: #YOUR_COLOR;
    /* ... etc */
}
```

### Update Content
- Edit HTML files directly for text and structure
- Replace gradient backgrounds with your images
- Update phone number, email, and address in footer

### Modify Component Behavior
- `js/carousel.js` - Carousel timing, autoplay speed
- `js/forms.js` - Form validation rules, submission handling
- `js/animations.js` - Gallery filtering, lightbox behavior

## 📱 Responsive Breakpoints

- **Mobile**: < 480px (single column, hamburger menu)
- **Tablet**: 480px - 768px (optimized touch targets)
- **Laptop**: 768px - 1024px (2-column layouts)
- **Desktop**: 1024px+ (full 3-4 column grids)

## ♿ Accessibility Features

- ARIA labels on all interactive elements
- Keyboard navigation (Tab, Enter, Arrow keys, Escape)
- Focus indicators on all buttons and links
- Skip to main content link
- Semantic HTML5 structure
- Color contrast ratios meet WCAG AA standards
- Respects `prefers-reduced-motion` media query

## 🔒 Security & Performance

- No external dependencies or vulnerabilities
- No third-party tracking scripts
- Content Security Policy ready
- Gzip compression enabled
- Browser caching optimized
- Mobile-first progressive enhancement

## 📊 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

This is a static website template. To customize:
1. Edit HTML files for content
2. Modify CSS in `css/` folder for styling
3. Update JavaScript in `js/` folder for interactivity
4. Test responsive design with browser DevTools

## 📝 License

Free to use and modify for personal and commercial projects.

## 🎓 Learning Resources

This project demonstrates:
- Semantic HTML5 structure
- Modern CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript (Intersection Observer, Event Delegation)
- Mobile-first responsive design
- Web accessibility best practices
- Performance optimization techniques
- Docker containerization

## 🚀 Deployment Checklist

- [ ] Update all contact information
- [ ] Add your actual images/media
- [ ] Customize colors and fonts if desired
- [ ] Test all forms and validations
- [ ] Check all links and navigation
- [ ] Test on mobile devices
- [ ] Verify accessibility with screen reader
- [ ] Optimize images for web
- [ ] Set up analytics (if desired)
- [ ] Deploy to production

## 📞 Support

For questions or customization requests, refer to the inline code comments and structure your custom HTML/CSS/JS following the established patterns.

---

Built with ❤️ using pure HTML5, CSS3, and vanilla JavaScript. No frameworks. No dependencies. Pure web excellence.