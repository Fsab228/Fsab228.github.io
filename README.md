# Portfolio Landing Page

A modern, responsive portfolio landing page for a Bot Developer & Automation Specialist.

## Features

- **Hero Section**: Eye-catching introduction with gradient text and call-to-action buttons
- **Services Section**: Three service cards (AI Bots, Crypto Bots, Automation) with hover effects
- **Portfolio Grid**: Showcase of 3 featured bots with GitHub links
- **Contact Section**: Links to Telegram, Fiverr, and Email
- **Modern Design**: Dark theme with gradient accents and smooth animations
- **Mobile Responsive**: Fully responsive design for all screen sizes
- **Fast Loading**: Uses CDN for Tailwind CSS and Font Awesome

## Technologies

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts (Inter)

## Customization

### Update Contact Information

Edit the contact section in `index.html`:

```html
<!-- Telegram -->
<a href="https://t.me/your_telegram" target="_blank">
    ...
    <p class="text-slate-400 text-sm">@your_telegram</p>
</a>

<!-- Fiverr -->
<a href="https://www.fiverr.com/your_profile" target="_blank">
    ...
</a>

<!-- Email -->
<a href="mailto:your.email@example.com">
    ...
    <p class="text-slate-400 text-sm">your.email@example.com</p>
</a>
```

### Update Portfolio Projects

Modify the portfolio section to add your own projects:

```html
<div class="card-hover bg-slate-800/50 rounded-xl overflow-hidden">
    <div class="h-48 bg-gradient-to-br from-blue-600 to-purple-600">
        <!-- Add screenshot or icon -->
    </div>
    <div class="p-6">
        <h3 class="text-xl font-bold">Your Bot Name</h3>
        <p class="text-slate-400 mb-4">Description...</p>
        <a href="https://github.com/your-username/repo" target="_blank">
            View on GitHub
        </a>
    </div>
</div>
```

### Change Colors

The page uses a dark theme with blue/purple gradients. To change colors, modify the gradient classes:

- `from-blue-600 to-purple-600` - Main gradient
- `text-blue-400` - Accent color
- `bg-slate-800` - Card backgrounds

## Deployment

### Option 1: GitHub Pages

1. Create a new repository
2. Upload the `index.html` file
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify

1. Drag and drop the `portfolio` folder to Netlify
2. Your site will be live instantly

### Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the portfolio directory
3. Follow the prompts

## Performance

- Uses CDN for fast loading
- Minimal JavaScript for smooth animations
- Optimized CSS with Tailwind
- Lazy loading ready

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Free to use and modify for personal or commercial projects.

