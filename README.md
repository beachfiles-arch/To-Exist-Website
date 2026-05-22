# To Exist / Existir

A beautiful bilingual website for the book "To Exist" by Maria del Rocio Medina Anguiano.

## 📚 About the Book

"To Exist" is a powerful guide to living with autoimmune disease and finding resilience, healing, and happiness. Available in both English and Spanish.

- **ISBN:** 9798375452036
- **Author:** Maria del Rocio Medina Anguiano
- **Buy on Amazon:**
  - [English Version](https://www.amazon.com/dp/B0BTD2ZPPP)
  - [Spanish Version](https://www.amazon.com/dp/B0BW2QM7PR)

## 🌐 Website Features

- **Bilingual Design:** English and Spanish versions with easy language switching
- **Responsive Layout:** Works perfectly on desktop, tablet, and mobile
- **Professional Design:** Clean, elegant styling reflecting the book's message
- **Contact Form:** Integrated contact form for reader inquiries
- **Book Information:** Comprehensive sections with book details, author bio, and purchase links

## 📁 Project Structure

```
to-exist-website/
├── index.html              # Language selector (home page)
├── en/
│   └── index.html         # English version
├── es/
│   └── index.html         # Spanish version
├── css/
│   └── style.css          # Main stylesheet (shared)
├── images/
│   ├── toexist.png        # English book cover
│   ├── existir.png        # Spanish book cover
│   ├── englishback.png    # English back cover
│   ├── espanolback.png    # Spanish back cover
│   └── Authorheadshot.png # Author photo
├── README.md              # This file
└── .gitignore             # Git ignore rules
```

## 🚀 Getting Started

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/to-exist-website.git
   cd to-exist-website
   ```

2. **Open locally:**
   - Simply open `index.html` in your web browser
   - Or use a local server: `python -m http.server 8000` (Python 3)

3. **View the site:**
   - Navigate to `http://localhost:8000`

### GitHub Pages Deployment

1. **Create a GitHub repository** named `to-exist-website` (or your preferred name)

2. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: To Exist website"
   git branch -M main
   git remote add origin https://github.com/yourusername/to-exist-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and save
   - Your site will be live at: `https://yourusername.github.io/to-exist-website/`

4. **Custom Domain (Optional):**
   - If you have a custom domain, add it in the GitHub Pages settings
   - Create a `CNAME` file in the root with your domain name

## ✉️ Contact Form Setup

The contact form uses **Formspree** to handle email submissions. 

### To Set Up Email:

1. **Create a Formspree account:**
   - Go to [formspree.io](https://formspree.io)
   - Sign up with your email (rflamingocancun@gmail.com)

2. **Create a form:**
   - Create a new form and get your form endpoint
   - It will look like: `https://formspree.io/f/XXXXXXXXX`

3. **Update the form action:**
   - Edit both `en/index.html` and `es/index.html`
   - Replace the `action` attribute in the form tag with your Formspree URL:
   ```html
   <form class="contact-form" action="https://formspree.io/f/YOUR_ID" method="POST">
   ```

4. **Test the form:**
   - Submit a test message to verify it works
   - Emails will arrive at rflamingocancun@gmail.com

## 🎨 Customization

### Colors
Edit `css/style.css` to change the color scheme:
- Primary color: `#1a3a52` (deep blue)
- Secondary color: `#0d1f2d` (darker blue)

### Content
- English content: Edit `en/index.html`
- Spanish content: Edit `es/index.html`
- Both share the same stylesheet: `css/style.css`

### Images
- Replace images in the `images/` folder
- Update image filenames in the HTML if needed

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

All content © 2026 Maria del Rocio Medina Anguiano. All rights reserved.

## 🤝 Support

For questions about the website, contact: rflamingocancun@gmail.com

---

**Website built with HTML5, CSS3, and Formspree**
