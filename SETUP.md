# Quick Setup Guide

## 🚀 Getting Started

1. **Open the file**: Simply open `index.html` in your browser
2. **Customize**: Edit contact information and portfolio projects
3. **Deploy**: Upload to GitHub Pages, Netlify, or Vercel

## 📝 What to Customize

### 1. Contact Information (Line ~350-400)

Replace these placeholders:
- `https://t.me/your_telegram` → Your Telegram username
- `https://www.fiverr.com/your_profile` → Your Fiverr profile URL
- `your.email@example.com` → Your email address

### 2. Portfolio Projects (Line ~250-350)

Update the three portfolio cards:
- **Crypto Alert Bot**: Already linked to your GitHub repo
- **AI Chat Bot**: Update GitHub link and description
- **Lead Bot**: Update GitHub link and description

### 3. Statistics (Line ~80-95)

Update the numbers:
- `50+` → Your actual number of bots
- `100%` → Your satisfaction rate
- `24/7` → Your availability

### 4. GitHub Links

Replace `https://github.com/Fsab228` with your actual GitHub username where needed.

## 🎨 Design Customization

### Change Colors

The page uses a blue/purple gradient theme. To change:

1. **Main gradient** (Hero section): 
   - Find `from-blue-600 to-purple-600`
   - Change to your preferred colors

2. **Accent color**:
   - Find `text-blue-400` and `bg-blue-500`
   - Replace with your color

### Add Screenshots

Replace the icon placeholders in portfolio cards with actual screenshots:

```html
<div class="h-48 bg-gradient-to-br from-blue-600 to-purple-600">
    <img src="screenshot.png" alt="Bot Screenshot" class="w-full h-full object-cover">
</div>
```

## 📱 Testing

1. Open `index.html` in Chrome/Firefox
2. Test mobile view (F12 → Toggle device toolbar)
3. Check all links work
4. Verify animations are smooth

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create repo: `portfolio-landing`
2. Upload `index.html`
3. Settings → Pages → Select main branch
4. Your site: `https://username.github.io/portfolio-landing`

### Netlify (Free)
1. Go to netlify.com
2. Drag & drop `portfolio` folder
3. Done! Get instant URL

### Vercel (Free)
```bash
npm i -g vercel
cd portfolio
vercel
```

## ✅ Checklist Before Going Live

- [ ] Updated all contact information
- [ ] Added real GitHub links
- [ ] Replaced placeholder text
- [ ] Tested on mobile devices
- [ ] Checked all links work
- [ ] Verified animations
- [ ] Added screenshots (optional)

## 🎯 SEO Tips

1. Update `<meta name="description">` with your actual description
2. Add Open Graph tags for social sharing
3. Consider adding a favicon
4. Add structured data (JSON-LD) for better search results

## 📞 Support

If you need help customizing, check the code comments or modify the Tailwind classes directly.

---

**Ready to launch!** 🚀

