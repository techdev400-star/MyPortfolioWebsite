# Professional Portfolio Website

A modern, responsive portfolio website showcasing professional profile as a System Analyst. Built with vanilla HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Smooth scrolling between sections with active link highlighting
- **Modern UI**: Clean, professional design with a blue color scheme
- **Mobile Menu**: Hamburger menu for mobile devices
- **Multi-page**: Home page with portfolio sections and dedicated About page
- **Print-Friendly**: Optimized styles for printing/PDF export

## File Structure

```
/
├── index.html          # Main HTML structure
├── about.html          # About/Cover letter page
├── styles/
│   └── main.css        # All styling (responsive design, animations)
├── scripts/
│   └── main.js         # Smooth scrolling, mobile menu toggle
└── README.md           # This file
```

## Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser

**Using a Local Server (Recommended):**

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx http-server

# PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Deployment

### Deploy to GitHub

1. Create a new repository on GitHub
2. Initialize git in your project directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
   git push -u origin main
   ```

### Host with Netlify

#### Method 1: Connect to GitHub (Recommended)

1. Go to [Netlify](https://app.netlify.com) and sign in
2. Click "Add new site" → "Import an existing project"
3. Connect to GitHub and select your repository
4. Configure build settings:
   - **Branch to deploy**: `main`
   - **Build command**: (leave empty)
   - **Publish directory**: `/` or `.` (leave empty)
5. Click "Deploy site"
6. Your site will be live at `https://your-site-name.netlify.app`

#### Method 2: Drag and Drop

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop your project folder
3. Your site is live instantly

### Custom Domain (Optional)

1. In Netlify: Site settings → Domain management → Add custom domain
2. Follow Netlify's DNS configuration instructions
3. SSL certificate is automatically provisioned

## Customization

### Colors

Edit CSS custom properties in `styles/main.css`:

```css
:root {
    --primary-color: #2563eb;
    --primary-dark: #1e40af;
    --secondary-color: #64748b;
    --text-color: #1e293b;
    --bg-color: #ffffff;
    --bg-light: #f8fafc;
}
```

### Content

Edit `index.html` and `about.html` to update:
- Personal information
- Experience details
- Skills
- Education
- Certifications
- Contact information

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- Vanilla JavaScript
- No dependencies or build tools required

## License

This project is open source and available for personal use.


