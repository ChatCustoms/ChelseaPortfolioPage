# Chelsea Dawn Chatham | HR Professional Portfolio

A professional portfolio website for Chelsea Dawn Chatham — Human Resources expert, Marine Corps Veteran, and former Department of the Navy civilian employee. Built with HTML and CSS, featuring a beach sunset glassmorphism design.

## Features

- **Glassmorphism Design**: Transparent, frosted-glass UI elements over a beach sunset background
- **Multi-page Structure**: Home, About, Skills, Experience, and Contact pages
- **Responsive Layout**: Optimized for desktop, tablet, and mobile
- **Functional Contact Form**: Powered by Web3Forms (free tier, 250 submissions/month)
- **Downloadable Resume**: .docx resume available for download
- **Security Hardened**: CSP, HSTS, X-Frame-Options, and other security headers via Vercel
- **Bottom Navigation Bar**: Fixed, transparent navbar at the bottom of the viewport

## Pages

- `index.html` - Home page with hero section and career highlights
- `about.html` - Professional background, headshot, values, and stats
- `skills.html` - HR skills with proficiency bars across 4 categories
- `experience.html` - Work timeline, education, and certifications
- `contact.html` - Contact form, email, phone, LinkedIn, and location info

## Project Structure

```
portfolio-website/
├── index.html
├── about.html
├── skills.html
├── experience.html
├── contact.html
├── styles.css
├── vercel.json
├── .gitignore
├── assets/
│   ├── background_image.png
│   ├── Chelsea_headshot.jpg
│   ├── favicon.png
│   ├── EGA.png
│   └── 2026 Main Resume.pdf
└── README.md
```

## Deployment

Hosted on Vercel. Pushes to the `main` branch on GitHub trigger automatic deployments.

**Repository**: [github.com/ChatCustoms/ChelseaPortfolioPage](https://github.com/ChatCustoms/ChelseaPortfolioPage)

## Security

- Content Security Policy (CSP) restricting scripts and form actions
- HTTP Strict Transport Security (HSTS) enforcing HTTPS
- X-Frame-Options DENY to prevent clickjacking
- X-Content-Type-Options nosniff
- Referrer-Policy on all pages
- Permissions-Policy disabling camera, microphone, and geolocation
- Honeypot field for bot protection on the contact form

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
