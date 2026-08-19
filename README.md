# Emily Frisbie Portfolio Website

A clean, responsive portfolio website showcasing your data science work, capstone project, and professional background.

## File Structure

```
/
├── index.html          # Homepage (bio, about, skills)
├── resume.html         # Resume page (education, experience, skills)
├── projects.html       # Projects overview page
├── moodvie.html        # Moodvie capstone project page
├── styles.css          # Color scheme & responsive design
├── logo_final.png      # Your branding logo (upload this)
├── README.md           # This file
└── resume.pdf          # Your PDF resume (optional)
```

## Color Palette (From Your Logo)

- **Dark Teal**: `#4A5D5C` (Primary, headings, accents)
- **Burgundy**: `#7D555F` (Secondary, highlights, hover effects)
- **Light Tan**: `#B8B8A6`
- **Sage Green**: `#B7C1B4` (Soft accents)
- **Muted Green**: `#6F7B70` (Meta text, secondary info)
- **Cream Background**: `#F5F3EF`

## Quick Start

### 1. Local Testing
1. Download all files to a folder on your computer
2. Make sure `logo_final.png` is in the same directory as the HTML files
3. Open `index.html` in your browser
4. Click through the navigation to test all pages

### 2. Customize Content

**Homepage (index.html)**
- [ ] Update your name and tagline
- [ ] Replace placeholder text with your bio
- [ ] Add your GitHub/LinkedIn URLs in the footer

**Resume (resume.html)**
- [ ] Add your education details (school, dates, graduation year)
- [ ] Add your work experience (dates, achievements)
- [ ] Update technical skills list
- [ ] Replace `placeholder-image.png` with your professional headshot
- [ ] Add/update `resume.pdf` link if you have one

**Projects (projects.html)**
- [ ] Update GitHub links for your projects
- [ ] Add project descriptions
- [ ] Update categories as needed

**Moodvie (moodvie.html)**
- [ ] Update the deployment link from `https://moodvie.io` to your actual deployed URL
- [ ] Adjust technical details if your stack differs
- [ ] Update timeline (currently says "Coming soon")

### 3. Deploy to GitHub Pages

1. Create a new GitHub repository named `emilydoesdata.github.io`
2. Push all files to that repository
3. Your site will be live at `https://emilydoesdata.github.io`

**To use a custom domain (emilydoesdata.com):**
1. Update your domain's DNS settings to point to GitHub Pages
2. Add a `CNAME` file to your repo with your domain name
3. Enable custom domain in GitHub Pages settings

See GitHub Pages documentation for full instructions.

### 4. Link to Moodvie

Once you deploy Moodvie to Streamlit Cloud:
1. Get your public URL (e.g., `https://moodvie.streamlit.app`)
2. Update the button in `moodvie.html` to point to that URL
3. Remove the "Coming soon" message

## Customization Tips

### Add More Projects
Copy the `project-card` div in `projects.html` and update the content:
```html
<div class="project-card">
  <h3>Your Project Name</h3>
  <p>Brief description...</p>
  <a href="link-to-project" class="btn btn-secondary">View →</a>
</div>
```

### Adjust Colors
If you want to use different colors, edit `:root` in `styles.css`:
```css
:root {
  --dark-teal: #YOUR-COLOR;
  --burgundy: #YOUR-COLOR;
  /* etc. */
}
```

### Add Your Headshot
1. Save your professional photo as `headshot.png` in the same folder
2. Update `resume.html`:
```html
<img src="headshot.png" alt="Professional Headshot" class="header-image">
```

## Responsive Design

The site is fully responsive and tested on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (480px - 767px)

No additional configuration needed—just works!

## Browser Compatibility

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Next Steps

1. **Immediate**: Fill in your bio, resume, and project details
2. **Short-term**: Deploy to GitHub Pages or your hosting service
3. **Medium-term**: Connect to your custom domain
4. **Deployment**: Link to live Moodvie app when ready

## Questions?

Refer to the comments in `styles.css` for styling adjustments.
For deployment questions, check GitHub Pages, Streamlit Cloud, or your hosting provider's docs.

---

**Last Updated**: August 18, 2026  
**Status**: Ready for customization and deployment
