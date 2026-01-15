# Professional Portfolio Website

A modern, responsive single-page portfolio website showcasing Oyetola Joseph Oyeyemi's professional profile as a System Analyst.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Smooth scrolling between sections with active link highlighting
- **Modern UI**: Clean, professional design with a blue color scheme
- **Mobile Menu**: Hamburger menu for mobile devices
- **Print-Friendly**: Optimized styles for printing/PDF export

## File Structure

```
/
├── index.html          # Main HTML structure
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
3. That's it! No build process or dependencies required

### Using a Local Server (Recommended)

For the best experience, use a local web server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push all files to the repository
3. Go to Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a random URL
3. You can customize the domain name in settings

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

### Other Hosting Options

Any static hosting service will work:
- AWS S3 + CloudFront
- Google Cloud Storage
- Azure Static Web Apps
- Any web hosting provider that supports static files

## Customization

### Colors

Edit the CSS custom properties in `styles/main.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --primary-dark: #1e40af;       /* Darker blue for hover states */
    --secondary-color: #64748b;    /* Secondary gray color */
    --text-color: #1e293b;         /* Main text color */
    --bg-color: #ffffff;            /* Background color */
    --bg-light: #f8fafc;           /* Light background for sections */
}
```

### Content

Edit `index.html` to update:
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

## License

This project is open source and available for personal use.

## Contact

Oyetola Joseph Oyeyemi
- Email: oyetola.joseph@yahoo.com
- Phone: 240-486-6704
- LinkedIn: [Profile](https://www.linkedin.com/in/oyetola-j-oyeyemi-55a682228)
