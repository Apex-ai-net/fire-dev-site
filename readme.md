# Fire Dev LLC - Professional Website

🔥 Professional terminal-themed website for The Fire Dev LLC featuring a cyberpunk Matrix aesthetic with real-time contact form integration.

## 🌟 Features

- **Matrix Rain Animation** - Authentic cyberpunk background effects
- **CRT Terminal Styling** - Retro scanlines and screen flicker
- **Professional Contact Form** - EmailJS integration for direct inquiries
- **Responsive Design** - Optimized for mobile and desktop
- **Social Media Integration** - Links to deployed applications and profiles

## 🚀 Live Site

- **Production:** [Deploy on Netlify](https://app.netlify.com/start/deploy?repository=https://github.com/Apex-ai-net/fire-dev-site)
- **Repository:** https://github.com/Apex-ai-net/fire-dev-site

## 📁 Project Structure

```
fire-dev-site/
├── index.html          # Main landing page with Matrix effects
├── about.html          # About page with capabilities and portfolio
├── _redirects          # Netlify routing configuration
├── netlify.toml        # Netlify build and deploy settings
└── robots.txt          # SEO configuration
```

## 🛠 Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Apex-ai-net/fire-dev-site.git
   cd fire-dev-site
   ```

2. **Start local server:**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server . -p 8000 -o
   ```

3. **Open browser:** http://localhost:8000

## 🌐 Netlify Deployment

### Automatic Deployment
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty for static site)
3. Set publish directory: `.` (root)
4. Deploy!

### Manual Deployment
1. Zip the entire project folder
2. Drag and drop to Netlify deploy area
3. Site will be live instantly

### Troubleshooting 404 Errors
- ✅ `_redirects` file handles routing
- ✅ `netlify.toml` configures build settings
- ✅ All paths redirect to `index.html` for client-side routing

## 📧 Contact Form Configuration

The contact form uses EmailJS for direct email delivery:
- **Service ID:** Configured in EmailJS dashboard
- **Template ID:** Custom template for business inquiries  
- **Destination:** contact@thefiredev.com

## 🎨 Design Features

- **Terminal Aesthetic** - Green-on-black cyberpunk styling
- **Matrix Digital Rain** - Continuous falling character animations
- **CRT Effects** - Authentic retro monitor scanlines and flicker
- **Glitch Effects** - Random text corruption for dramatic flair
- **Responsive Layout** - Mobile-optimized with scroll animations

## 🔗 Portfolio Links

- **IntelliSense.io** - AI-powered business intelligence platform
- **HealthyWholesale.org** - Wholesale marketplace solution
- **GitHub:** [@Apex-ai-net](https://github.com/Apex-ai-net)
- **Instagram:** [@thefiredev.com_](https://instagram.com/thefiredev.com_)

## 🛡 Security

- Content Security Policy headers
- XSS protection enabled
- Frame options configured
- Secure referrer policy

---

**Built with:** HTML5, CSS3, JavaScript, EmailJS
**Styled with:** Terminal/Matrix aesthetic, responsive design
**Deployed on:** Netlify