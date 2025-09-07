# Fine Graduation Website - Deployment Guide

## 🚀 Quick Deployment to GitHub Pages

### Step 1: Repository Setup
1. **Create a new repository** on GitHub named `finegraduation.github.io_v2`
2. **Initialize the repository** with the files from this project
3. **Push all files** to the main branch

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **"Deploy from a branch"**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 3: Automatic Deployment
The GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically:
- Build the site when you push to main branch
- Deploy to GitHub Pages
- Make your site available at: `https://yourusername.github.io/finegraduation.github.io_v2`

## 📱 Adding Video Assets (Optional but Recommended)

### Before Going Live:
1. **Download a graduation ceremony video** from:
   - Pexels Videos: https://pexels.com/videos
   - Pixabay Videos: https://pixabay.com/videos
   - Unsplash Videos: https://unsplash.com

2. **Video Requirements:**
   - Format: MP4 (H.264 codec)
   - Resolution: 1920x1080 or higher
   - Duration: 10-30 seconds (will loop)
   - File size: Under 10MB
   - Content: Graduation ceremony or elegant abstract

3. **Add to Project:**
   - Rename video to `graduation-bg.mp4`
   - Place in `assets/` directory
   - Optionally add `graduation-fallback.jpg`

### Search Terms for Video:
- "graduation ceremony"
- "university campus"
- "academic achievement"
- "elegant abstract background"
- "minimalist video background"

## ⚙️ Configuration

### Update WhatsApp Number
In `index.html`, line 85, replace the phone number:
```html
<a href="https://wa.me/6281234567890?text=..."
```
Change `6281234567890` to your actual WhatsApp business number.

### Custom Domain (Optional)
1. Add a `CNAME` file to the root directory
2. Add your custom domain (e.g., `finegraduation.com`)
3. Configure DNS settings with your domain provider
4. Update GitHub Pages settings to use custom domain

## 🔧 Local Development

### Testing Locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## 📊 Performance Tips

### For Production:
1. **Optimize video file** - compress to reduce file size
2. **Add video poster image** - for faster initial loading
3. **Enable CDN** - consider using a CDN for assets
4. **Monitor performance** - use Google PageSpeed Insights

### SEO Optimization:
1. **Add meta tags** for social media sharing
2. **Include structured data** for business information
3. **Add sitemap.xml** if expanding to multiple pages
4. **Set up Google Analytics** for tracking

## 🚨 Troubleshooting

### Common Issues:

**1. GitHub Pages not updating:**
- Check Actions tab for deployment status
- Ensure main branch has latest changes
- Verify Pages settings are correct

**2. Video not loading:**
- Check file path in `index.html`
- Ensure video file is in `assets/` directory
- Verify video format is MP4

**3. WhatsApp link not working:**
- Verify phone number format (include country code)
- Test URL encoding of message text
- Check for typos in the href attribute

**4. Responsive issues:**
- Test on actual devices
- Use browser developer tools
- Check CSS media queries

## 📈 Next Steps After Deployment

1. **Test on multiple devices** (mobile, tablet, desktop)
2. **Verify WhatsApp integration** works correctly
3. **Check loading speed** and optimize if needed
4. **Add Google Analytics** for visitor tracking
5. **Set up contact form** if needed (using Netlify Forms or similar)
6. **Add more pages** (About, Portfolio, Services) if expanding

## 🎯 Success Checklist

- [ ] Repository created and files uploaded
- [ ] GitHub Pages enabled and deployed
- [ ] Website accessible via GitHub Pages URL
- [ ] WhatsApp button working with correct number
- [ ] Responsive design tested on mobile/tablet/desktop
- [ ] Video assets added (optional)
- [ ] Custom domain configured (optional)
- [ ] Analytics tracking set up (optional)

## 📞 Support

If you encounter any issues:
1. Check the GitHub Actions logs for deployment errors
2. Verify all file paths are correct
3. Test locally before deploying
4. Refer to GitHub Pages documentation

---

**Your Fine Graduation website is ready to showcase beautiful graduation photography services! 📸✨**
