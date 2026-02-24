# Personal Portfolio Website

A clean, modern, and responsive personal portfolio website showcasing my skills as a Full-Stack Developer and Content Writer.

## 🚀 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Modern UI** - Clean dark theme with smooth animations
- **Fast Loading** - Pure HTML, CSS, and JavaScript (no frameworks)
- **SEO Friendly** - Semantic HTML and meta tags
- **Accessible** - WCAG compliant
- **GitHub Pages Ready** - Easy deployment

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, CSS Variables)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles
├── script.js           # JavaScript functionality
├── resume.pdf          # Your resume (add this)
└── README.md           # This file
```

## 🎨 Sections

1. **Hero** - Introduction with call-to-action buttons
2. **About** - Personal bio and stats
3. **Skills** - Technical and content writing skills
4. **Projects** - Portfolio projects with links
5. **Contact** - Contact methods and resume download
6. **Footer** - Social links and copyright

## ⚙️ Setup & Customization

### 1. Clone or Download

```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

### 2. Customize Content

Edit `index.html` and replace:

- `YourName` - Your actual name
- `your.email@example.com` - Your email
- `@yourusername` - Your social media handles
- Project descriptions and links
- About section text
- Skills (add/remove as needed)

### 3. Add Your Resume

- Create a PDF of your resume
- Save it as `resume.pdf` in the project root
- Or update the link in the Contact section

### 4. Replace Placeholder Images

- Take screenshots of your projects
- Replace placeholder image URLs in the Projects section
- Recommended size: 600x400px

### 5. Test Locally

Simply open `index.html` in your browser:

```bash
# On Mac/Linux
open index.html

# On Windows
start index.html
```

Or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have it)
npx serve
```

Then visit `http://localhost:8000`

## 🌐 Deployment to GitHub Pages

### Method 1: Via Repository Settings

1. Create a new repository on GitHub
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Source: Deploy from branch → `main` → `/root`
5. Save and wait a few minutes
6. Your site will be live at `https://yourusername.github.io/portfolio/`

### Method 2: Using a Custom Domain (Optional)

1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In repository settings → Pages → Custom domain
3. Enter your domain
4. Update DNS settings with your domain provider:
   ```
   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```

## 🎯 Customization Tips

### Colors

Change colors in `style.css` (look for `:root` variables):

```css
:root {
    --bg-primary: #0f172a;      /* Main background */
    --accent: #38bdf8;          /* Accent color */
    --text-primary: #e5e7eb;    /* Main text */
}
```

### Fonts

Replace Inter font in `index.html` `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;600;700&display=swap" rel="stylesheet">
```

Then update in `style.css`:

```css
font-family: 'YourFont', sans-serif;
```

### Animations

Disable typewriter effect by removing this from `script.js`:

```javascript
// Remove the typewriter section (lines ~60-75)
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

## 📧 Contact

If you have questions or want to connect:

- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)

---

**Built with ❤️ using HTML, CSS, and JavaScript**
