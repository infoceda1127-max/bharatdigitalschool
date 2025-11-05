# Bharat Digital School Website

A modern educational platform offering K-12 animated classes, olympiad preparation, live sessions, career counseling, and more.

## 🚀 Deployment to GitHub Pages

This is a static HTML website that deploys automatically to GitHub Pages.

### Initial Setup

1. **Push your code to GitHub:**
   ```bash
   git add .
   git commit -m "Add GitHub Pages deployment and SEO improvements"
   git push origin master
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under **Source**, select "GitHub Actions"
   - The workflow will automatically deploy your site

3. **Your site will be available at:**
   ```
   https://infoceda1127-max.github.io/bharatdigitalschool/
   ```

### Making Updates

Simply push changes to the `master` branch, and the site will automatically redeploy:

```bash
git add .
git commit -m "Update content"
git push origin master
```

## 🔍 SEO Optimization

The site includes:
- ✅ Proper meta descriptions for all pages
- ✅ Open Graph tags for social media sharing
- ✅ Sitemap.xml for search engines
- ✅ Robots.txt for crawler instructions
- ✅ Semantic HTML structure

### Update Google Search Results

After deployment:
1. Go to [Google Search Console](https://search.google.com/search-console)
2. Add and verify your site
3. Submit your sitemap: `https://infoceda1127-max.github.io/bharatdigitalschool/sitemap.xml`
4. Use "URL Inspection" to request re-indexing of pages
5. Wait 3-7 days for Google to update search results

## 📁 Project Structure

```
bharatdigitalschool/
├── index.html          # Home page
├── about.html          # About page
├── features.html       # Features page
├── olympiad.html       # Olympiad page
├── quiz.html          # Quiz page
├── counseling.html    # Career counseling page
├── doubtclass.html    # Doubt section page
├── contact.html       # Contact page
├── sitemap.xml        # SEO sitemap
├── robots.txt         # Crawler instructions
├── .nojekyll         # Disable Jekyll processing
└── images/           # Image assets
```

## 🛠️ Technologies Used

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## 📞 Contact

Bharat Digital School  
Powered by Chhattisgarh Education Development Association

---

© 2025 Bharat Digital School. All Rights Reserved.
