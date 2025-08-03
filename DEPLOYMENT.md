# Deployment Guide - Hon. Patrick Lumumba Campaign Website

This guide provides step-by-step instructions for deploying the campaign website to various hosting platforms.

## 🚀 Quick Start - GitHub Pages (Recommended for Free Hosting)

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click "New repository"
3. Name it: `patricklumumba-campaign`
4. Make it public
5. Click "Create repository"

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag and drop all website files
3. Add commit message: "Initial website upload"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch
5. Click "Save"
6. Your site will be available at: `https://username.github.io/patricklumumba-campaign`

## 🌐 Netlify Deployment (Alternative Free Option)

### Step 1: Prepare Files
1. Ensure all files are in a single folder
2. Make sure `index.html` is in the root directory

### Step 2: Deploy to Netlify
1. Go to [Netlify.com](https://netlify.com)
2. Sign up/Login with GitHub
3. Click "New site from Git" or drag folder to deploy area
4. If using Git: Select your repository
5. If dragging: Drop your folder
6. Site will be deployed automatically

### Step 3: Custom Domain (Optional)
1. In Netlify dashboard, go to "Domain settings"
2. Click "Add custom domain"
3. Enter your domain (e.g., `patricklumumba.co.ke`)
4. Follow DNS configuration instructions

## 📧 cPanel Hosting (Paid Option)

### Step 1: Purchase Hosting
1. Choose a hosting provider (e.g., Hostinger, Bluehost, GoDaddy)
2. Purchase hosting plan with cPanel
3. Register domain name

### Step 2: Access cPanel
1. Login to hosting control panel
2. Open cPanel
3. Find "File Manager"

### Step 3: Upload Files
1. Open File Manager
2. Navigate to `public_html` folder
3. Upload all website files
4. Ensure `index.html` is in the root

### Step 4: Configure Domain
1. In cPanel, go to "Domains"
2. Point domain to `public_html`
3. Wait for DNS propagation (24-48 hours)

## 🔧 Post-Deployment Checklist

### Essential Updates
- [ ] Replace placeholder images with real campaign photos
- [ ] Update contact information with real phone numbers
- [ ] Add actual YouTube video IDs
- [ ] Update social media links
- [ ] Test contact form functionality
- [ ] Verify mobile responsiveness

### SEO Optimization
- [ ] Add Google Analytics tracking code
- [ ] Submit sitemap to Google Search Console
- [ ] Optimize page titles and meta descriptions
- [ ] Add Open Graph tags for social sharing

### Security
- [ ] Enable HTTPS (automatic on most platforms)
- [ ] Set up SSL certificate
- [ ] Configure security headers
- [ ] Regular backups

## 📱 Mobile Testing

### Test on Multiple Devices
- [ ] iPhone (Safari)
- [ ] Android (Chrome)
- [ ] iPad (Safari)
- [ ] Desktop browsers (Chrome, Firefox, Safari, Edge)

### Key Areas to Test
- [ ] Navigation menu
- [ ] Contact form
- [ ] Image galleries
- [ ] Video embeds
- [ ] Social media links
- [ ] Page loading speed

## 🔄 Content Updates

### Regular Maintenance
1. **Weekly**: Update news and events
2. **Monthly**: Add new project photos
3. **Quarterly**: Review and update manifesto
4. **As needed**: Update contact information

### Content Management
- Keep images optimized (max 1MB each)
- Use descriptive file names
- Maintain consistent image dimensions
- Update copyright year annually

## 📊 Analytics Setup

### Google Analytics
1. Create Google Analytics account
2. Add tracking code to all pages
3. Set up goals for contact form submissions
4. Monitor traffic and user behavior

### Social Media Tracking
1. Set up Facebook Pixel
2. Configure conversion tracking
3. Monitor social media referrals
4. Track engagement metrics

## 🆘 Troubleshooting

### Common Issues

**Images not loading:**
- Check file paths
- Verify image files exist
- Ensure correct file extensions

**Contact form not working:**
- Add form processing script
- Configure email settings
- Test form submission

**Mobile display issues:**
- Check viewport meta tag
- Test responsive breakpoints
- Verify CSS media queries

**Slow loading:**
- Optimize image sizes
- Minify CSS/JS files
- Enable compression
- Use CDN for assets

## 📞 Support Contacts

### Technical Support
- Email: campaign@patricklumumba.co.ke
- Phone: +254 733 000 000

### Hosting Support
- Contact your hosting provider's support team
- Most providers offer 24/7 live chat support

---

**Remember**: Always backup your website before making major changes! 