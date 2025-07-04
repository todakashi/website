# MLBB Account Store Website

A concise website for Mobile Legends: Bang Bang (MLBB) account buying and selling services with modern design and responsive layout.

## 🎮 Main Features

### ✨ Design & UI/UX
- **Modern Design**: Gradient background, card-based layout, and smooth animations
- **Responsive**: Optimized for desktop, tablet, and mobile
- **Animations**: Hover effects, scroll animations, and loading transitions
- **Color Scheme**: Purple-blue gradient with yellow accents

### 📱 Navigation & Interaction
- **Fixed Navigation**: Sticky menu with blur effect
- **Mobile Menu**: Hamburger menu for small screens
- **Smooth Scrolling**: Smooth navigation between sections
- **Progress Bar**: Scroll progress indicator at the top

### 🛒 Account System
- **3 Package Tiers**: Bronze, Gold (Featured), and Diamond
- **Complete Details**: Rank, number of skins, diamonds, heroes, and warranty
- **Buy Buttons**: Direct WhatsApp integration
- **Hover Effects**: Animations on card hover

### 💬 Contact & Support
- **Multiple Channels**: WhatsApp, Telegram, and Email
- **Contact Form**: Form with email validation
- **Notification System**: User feedback alerts
- **Auto-Response**: Message sending simulation

### 🎯 Additional Features
- **Loading Animation**: Fade-in effect on page load
- **Ripple Effect**: Click effects on buttons
- **Keyboard Support**: ESC to close menu/notifications
- **Touch Support**: Swipe detection for mobile

## 🚀 How to Run

1. **Download/Clone** all files to a local folder
2. **Open** `index.html` in a browser
3. **Or** use live server for development

### File Structure:
```
Website/
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## 🎨 Customization

### Changing Contact Information
Edit in `index.html`:
```html
<!-- WhatsApp -->
<p>+1 (555) 123-4567</p>

<!-- Telegram -->
<p>@mlbbstore</p>

<!-- Email -->
<p>info@mlbbstore.com</p>
```

### Changing Prices & Packages
Edit in the accounts section:
```html
<div class="price">$35</div>
<ul>
    <li><i class="fas fa-check"></i> Epic Rank</li>
    <li><i class="fas fa-check"></i> 50+ Skins</li>
    <!-- ... -->
</ul>
```

### Changing Colors
Edit in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #fbbf24;
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px  
- **Mobile**: < 480px

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Animations, Media Queries
- **JavaScript**: ES6+, DOM manipulation, Event handling
- **Font Awesome**: Icons
- **Google Fonts**: Poppins font family

## 🎯 SEO & Performance

- **Meta Tags**: Proper title, description, viewport
- **Semantic HTML**: Proper heading structure
- **Optimized Images**: WebP format support
- **Minimal Dependencies**: Fast loading

## 📞 WhatsApp Integration

This website integrates with WhatsApp Business API for:
- **Pre-filled Messages**: Automatic messages with package details
- **Direct Contact**: Click button to open WhatsApp directly
- **Quick Response**: Fast customer service

## 🛡️ Security

- **Form Validation**: Client-side validation
- **XSS Prevention**: Sanitized inputs
- **HTTPS Ready**: SSL compatible
- **No External Dependencies**: Self-contained

## 📈 Analytics Ready

Website ready for integration with:
- Google Analytics
- Facebook Pixel
- WhatsApp Business API
- Custom tracking

## 🚀 Deployment

### Static Hosting
- Netlify
- Vercel
- GitHub Pages
- Firebase Hosting

### Custom Domain
- Update meta tags
- Configure SSL
- Set up redirects

## 📝 License

Free to use for commercial and personal projects.

## 🤝 Support

For questions or custom development:
- Email: info@mlbbstore.com
- WhatsApp: +1 (555) 123-4567

---

**MLBB Store** - Trusted place for premium Mobile Legends accounts! 🎮✨ 