# Tula Andrews - Author Website

A beautiful, responsive author website built with HTML, CSS, and JavaScript. No build tools required - just open the files in a browser!

## Features

- **Responsive Design** - Works beautifully on desktop, tablet, and mobile
- **Modern UI** - Clean, elegant design with warm earth tones
- **Smooth Animations** - Scroll animations and smooth navigation
- **Kindle Unlimited Integration** - Direct links to your Amazon author page
- **Sample Chapters Section** - Ready to add book excerpts
- **Blog Section** - Placeholder for future blog posts
- **Mobile Navigation** - Hamburger menu for mobile devices

## How to Use

### Quick Start
1. Open `index.html` in your web browser
2. The website will load immediately - no server needed!

### Customization

#### Add Your Author Photo
Replace the placeholder in the About section:
```html
<div class="placeholder-image">
    <span>Author Photo</span>
</div>
```
With:
```html
<img src="your-photo.jpg" alt="Tula Andrews" class="author-photo">
```

#### Add Book Covers
Replace the placeholder book covers:
```html
<div class="placeholder-cover">
    <span>Book Cover</span>
</div>
```
With:
```html
<img src="book-cover.jpg" alt="Book Title" class="book-cover-img">
```

Add this CSS to styles.css:
```css
.book-cover-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.author-photo {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 12px;
}
```

#### Update Book Information
Edit the book cards in the HTML to add:
- Your actual book titles
- Accurate descriptions
- Correct Amazon links
- Release status

#### Add Sample Chapters
1. Create sample chapter HTML files (e.g., `chapter1.html`)
2. Update the JavaScript in `script.js` to open modals with chapter content
3. Or link directly to the chapter files

#### Add Blog Posts
1. Create blog post HTML files (e.g., `blog-post-1.html`)
2. Update the blog cards with actual content
3. Add links to your blog posts

## Color Scheme

The website uses a warm, earthy color palette:
- Primary: `#8B4513` (Saddle Brown)
- Secondary: `#2C1810` (Dark Brown)
- Background: `#FAFAF5` (Warm White)
- Accent: `#F5F0EB` (Light Beige)

To customize colors, edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #8B4513;
    --primary-dark: #6B3410;
    --secondary-color: #2C1810;
    /* ... etc */
}
```

## Deployment

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the project folder
3. Your site will be live instantly

### Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

### Traditional Hosting
Upload all files to any web host - it's just static HTML/CSS/JS!

## File Structure

```
tula-andrews-author/
├── index.html      # Main page
├── styles.css      # All styling
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Browser Support

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Fonts Used

- **Playfair Display** - Headings (elegant serif)
- **Inter** - Body text (clean sans-serif)

Both are loaded from Google Fonts.

## Next Steps

1. Add your author photo
2. Add your actual book covers
3. Update book information with real data
4. Write and add sample chapters
5. Create blog posts
6. Deploy to your preferred hosting platform

## Support

If you need help customizing the website, feel free to ask!
