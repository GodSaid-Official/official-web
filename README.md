# God Said - Official Website & Legal Pages

This directory contains the official website and all required legal pages for Google Play Store submission of the God Said app.

## 📁 File Structure

```
docs/
├── index.html                      # Homepage
├── privacy.html                    # Privacy Policy
├── terms.html                      # Terms of Service
├── support.html                    # Help & Support
├── about.html                      # About Us
├── contact.html                    # Contact Us
├── data-deletion.html              # Data Deletion Request
├── google-play-store-listing.md    # Google Play Store Description
├── _config.yml                     # GitHub Pages Configuration
└── README.md                       # Documentation
```

## 🚀 GitHub Pages Deployment

### 1. Push to GitHub Repository

```bash
# Add all files to git
git add docs/

# Commit changes
git commit -m "Add official website and legal pages"

# Push to GitHub
git push origin main
```

### 2. Enable GitHub Pages

1. Go to GitHub repository settings
2. Scroll to "Pages" section
3. Select "Deploy from a branch"
4. Choose branch: "main"
5. Choose folder: "/docs"
6. Click "Save"

### 3. Custom Domain (Optional)

If you have your own domain (e.g., godsaid.app):

1. Add CNAME record in domain DNS settings:
   ```
   www -> yourusername.github.io
   ```

2. Create `CNAME` file in repository root:
   ```
   echo "www.godsaid.app" > CNAME
   ```

3. Enter your domain in GitHub Pages settings

## 📱 Google Play Store Preparation

### Required Page Links

In Google Play Console, you need to provide these links:

- **Privacy Policy:** `https://yourusername.github.io/godsaid/privacy.html`
- **Terms of Service:** `https://yourusername.github.io/godsaid/terms.html`
- **Support Page:** `https://yourusername.github.io/godsaid/support.html`
- **Data Deletion:** `https://yourusername.github.io/godsaid/data-deletion.html`

### App Store Description

Use content from `google-play-store-listing.md` to fill out:

1. **Short Description:** Get biblical wisdom and guidance for your prayers through AI technology
2. **Full Description:** Copy the complete description from the markdown file
3. **Keywords:** Use the keyword tags listed in the file

## 🛠️ Customization

### Update Contact Information

Update actual contact information in these files:

- `contact.html` - Update email addresses and contact methods
- `privacy.html` - Update contact emails
- `support.html` - Update customer service info
- `data-deletion.html` - Update data protection contact details

### Modify Styling

All pages use inline CSS, you can modify styles directly in HTML files:

- Change color themes
- Adjust fonts and layouts
- Add your own logo
- Modify background styles

### Add Analytics Code

Add before the `</head>` tag in each HTML file:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 📧 Email Setup

Make sure to set up these email addresses (can use email aliases or forwarding):

- `support@godsaid.app` - Customer service
- `privacy@godsaid.app` - Privacy issues
- `tech@godsaid.app` - Technical support
- `legal@godsaid.app` - Legal affairs
- `business@godsaid.app` - Business partnerships
- `urgent@godsaid.app` - Emergency matters

## 🔍 SEO Optimization

### Sitemap

GitHub Pages will automatically generate sitemap.xml, but you can also create one manually:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://yourusername.github.io/godsaid/</loc>
    <changefreq>monthly</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://yourusername.github.io/godsaid/privacy.html</loc>
    <changefreq>yearly</changefreq>
    <priority>0.8</priority>
  </url>
  <!-- Other pages... -->
</urlset>
```

### Meta Tag Optimization

Each page includes basic SEO meta tags that can be further optimized as needed.

## 📱 Mobile Optimization

All pages are optimized for mobile devices:

- Responsive design
- Touch-friendly interface
- Fast loading
- Accessibility support

## 🔒 Security and Privacy

- All pages served over HTTPS
- No user data collection (static pages)
- GDPR compliant
- Complete privacy policy included

## 📞 Support

If you encounter issues during deployment or usage:

1. Check GitHub Pages build status
2. Confirm all file paths are correct
3. Verify DNS settings (if using custom domain)
4. Check browser developer tools for error messages

## 📝 License

These page templates can be freely used and modified to suit your needs. Please ensure you update all contact information and app-specific content.

---

**May God bless your app launch journey!** 🙏 