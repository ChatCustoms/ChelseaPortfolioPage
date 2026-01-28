# Portfolio Website for Jane Doe

A modern, colorful, multi-page portfolio website built with HTML, CSS, and vanilla JavaScript. Perfect for showcasing skills, experience, and professional background to potential employers.

## Features

- **Creative & Colorful Design**: Vibrant gradient colors and smooth animations
- **Multi-page Structure**: Separate pages for Home, About, Skills, Experience, and Contact
- **Responsive Layout**: Works beautifully on desktop, tablet, and mobile devices
- **Downloadable Resume**: PDF resume available for download
- **Professional Sections**:
  - Hero section with call-to-action buttons
  - About page with values and statistics
  - Skills page with visual progress bars and badges
  - Experience page with timeline and education section
  - Contact page with form and social media links

## Pages

- `index.html` - Home page with hero section and highlights
- `about.html` - About me, background, and values
- `skills.html` - Technical skills with proficiency levels
- `experience.html` - Work history, timeline, and education
- `contact.html` - Contact form and social media links
- `styles.css` - All styling with colorful gradients and animations
- `assets/resume.pdf` - Downloadable resume

## Customizing the Content

To personalize this portfolio:

1. **Replace Placeholder Content**:
   - Search for "Jane Doe" and replace with the actual name
   - Update email, phone, and location in contact.html
   - Modify social media links in contact.html

2. **Update Skills**:
   - Edit skills.html to add/remove technical skills
   - Adjust skill levels and progress bar percentages

3. **Add Work Experience**:
   - Update experience.html with real job history
   - Modify dates, company names, and achievements

4. **Customize Colors**:
   - Edit CSS variables in styles.css (lines 10-18)
   - Modify gradient colors to match preferred brand colors

5. **Replace Resume**:
   - Replace assets/resume.pdf with an actual resume PDF
   - Or create one by printing the provided HTML resume to PDF

## Deploying to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Navigate to the project directory:
   ```bash
   cd portfolio-website
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts to complete deployment

### Option 2: Deploy via Vercel Dashboard

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)

2. Go to [vercel.com](https://vercel.com) and sign in

3. Click "Add New Project"

4. Import your repository

5. Vercel will automatically detect the configuration and deploy

### Option 3: Deploy via Drag & Drop

1. Go to [vercel.com](https://vercel.com) and sign in

2. Drag and drop the `portfolio-website` folder directly onto the Vercel dashboard

3. Vercel will deploy your site instantly

## Project Structure

```
portfolio-website/
├── index.html           # Home page
├── about.html          # About page
├── skills.html         # Skills page
├── experience.html     # Experience page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── vercel.json         # Vercel configuration
├── assets/
│   └── resume.pdf      # Downloadable resume
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This template is free to use for personal and commercial projects.

## Contact Form Note

The contact form is currently a front-end only form. To make it functional, you'll need to integrate with a backend service or use one of these options:

- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [Web3Forms](https://web3forms.com/)

Simply update the `action` attribute in the form tag in contact.html with your chosen service.

---

Made with creativity and care! Good luck with your job search! 🚀
