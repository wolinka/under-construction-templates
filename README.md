# Under Construction Page Templates

A collection of modern, interactive "Under Construction" page templates with particle animations, countdown timers, and social media integration. Built with vanilla JavaScript and CSS3, these templates provide elegant solutions for websites in development.

## 🚀 Features

- **🎨 Modern Glassmorphism Design** - Beautiful semi-transparent elements with backdrop blur effects
- **✨ Interactive Particle Animation** - Dynamic particle system using HTML5 Canvas API
- **⏱️ Countdown Timer** - Real-time countdown to launch date
- **📱 Fully Responsive** - Mobile-first design that works on all devices
- **🔗 Social Media Integration** - Pre-built social media buttons
- **🎭 CSS3 Animations** - Smooth animations and transitions
- **⚡ Zero Dependencies** - Pure vanilla JavaScript and CSS
- **🔧 Easy Customization** - Simple to modify colors, fonts, and content

## 📋 Template Variants

### 1. Basic Template (`index.html`)
- Clean under construction message
- Interactive particle background
- Progress indicator
- Company branding footer

### 2. Countdown Template (`index-2.html`)
- All features from Basic Template
- Real-time countdown timer
- Animated countdown units
- Glass container styling

### 3. Social Template (`index-3.html`)
- All features from Countdown Template
- Social media buttons (Facebook, Instagram, X/Twitter, Email, LinkedIn)
- Enhanced responsive design
- Complete contact integration

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and Canvas API
- **CSS3** - Modern features including:
  - CSS Custom Properties (Variables)
  - CSS Grid & Flexbox
  - Backdrop Filter (Glassmorphism)
  - CSS Animations & Keyframes
  - Responsive Design with Media Queries
- **JavaScript ES6+** - Vanilla JavaScript for:
  - Particle System Animation
  - Countdown Timer Logic
  - Interactive Mouse Effects
  - Responsive Canvas Handling

## 📦 Installation

### Quick Start
1. **Download** or clone this repository
   ```bash
   git clone https://github.com/wolinka/under-construction-templates.git
   ```

2. **Choose** your preferred template:
   - `index.html` - Basic template
   - `index-2.html` - With countdown timer
   - `index-3.html` - With countdown + social media

3. **Upload** to your web server or open directly in browser

### CDN Dependencies
The templates use Google Fonts which load automatically:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Poppins:wght@700&display=swap" rel="stylesheet">
```

## ⚙️ Customization

### Changing Colors
Modify the CSS custom properties in the `:root` section:
```css
:root {
    --primary-navy: #2C3E50;
    --gradient-bg: linear-gradient(135deg, #E3F2FD 0%, #F8F9FA 50%, #F0F8FF 100%);
}
```

### Setting Countdown Date
In `index-2.html` and `index-3.html`, update the target date:
```javascript
const targetDate = new Date('2025-12-15T12:00:00');
```

### Updating Social Media Links
In `index-3.html`, modify the social media URLs:
```html
<a href="https://facebook.com/yourpage" target="_blank" rel="noopener noreferrer" class="social-btn">
```

### Progress Bar Percentage
Update the progress fill width and percentage text:
```css
.progress-fill {
    width: 75%; /* Change this value */
}
```

### Company Information
Replace the footer content with your company details:
```html
<p>&copy; 2025 <a href="https://yourwebsite.com/" target="_blank">Your Company</a></p>
```

## 🎨 Particle Animation System

The particle system features:
- **Dynamic Particle Count** - Automatically adjusts based on screen size
- **Mouse Interaction** - Particles respond to cursor movement
- **Performance Optimized** - Uses `requestAnimationFrame` for smooth animation
- **High DPI Support** - Automatically scales for retina displays

### Customizing Particles
```javascript
// Adjust particle density
let numberOfParticles = (window.innerHeight * window.innerWidth) / 18000;

// Modify particle size range
let size = (Math.random() * 3) + 0.5;

// Change particle speed
let dirX = (Math.random() * 0.4) - 0.2;
let dirY = (Math.random() * 0.4) - 0.2;
```

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ iOS Safari 12+
- ✅ Android Chrome 60+

## 🔧 Performance Features

- **Responsive Images** - Optimized for different screen densities
- **GPU Acceleration** - CSS transforms utilize hardware acceleration
- **Efficient Animations** - RequestAnimationFrame for smooth 60fps
- **Lightweight** - No external JavaScript libraries
- **Fast Loading** - Minimal HTTP requests

## 🔴 Live Preview

- 🧊 **Basic:** https://wolinka.github.io/under-construction-templates/
- ⏱️ **Countdown:** https://wolinka.github.io/under-construction-templates/index-2.html
- 🌐 **Social + Countdown:** https://wolinka.github.io/under-construction-templates/index-3.html

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- 📧 **Email**: selam@wolinka.com.tr

## 🎯 Use Cases

- **Website Maintenance** - Display during site updates
- **Product Launches** - Build anticipation with countdown
- **Business Launches** - Professional coming soon page
- **Event Websites** - Countdown to event date
- **Portfolio Sites** - Temporary placeholder during development

## ⭐ Acknowledgments

- Design inspiration from modern web design trends
- Particle system concept from interactive web animations
- Glassmorphism design methodology
- Community feedback and contributions

---

**Made with ❤️ for the web development community**

If you find this project helpful, please consider giving it a ⭐ on GitHub!