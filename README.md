# Mahila Grameena Vidyabhivrudhi Samsthe (MGVS) Website

A clean, mobile-first website for the Mahila Grameena Vidyabhivrudhi Samsthe NGO.

## 📁 Project Structure

```
/
├── index.html          # Home Page
├── gallery.html        # Gallery Page
├── contact.html        # Contact Page
├── css/
│   └── styles.css      # Main stylesheet
└── assets/
    ├── images/         # Place your images here
    └── icons/          # Icons
```

## 🚀 How to Host on GitHub Pages

1. **Upload to GitHub**:
   - Create a new repository on GitHub (e.g., `mgvs-website`).
   - Upload all files in this folder to the repository.

2. **Enable GitHub Pages**:
   - Go to the repository **Settings**.
   - Click on the **Pages** section (sidebar).
   - Under **Build and deployment**, select **Source** as `Deploy from a branch`.
   - Select `main` (or `master`) branch and `/ (root)` folder.
   - Click **Save**.

3. **Visit your site**:
   - After a minute, your site will be live at `https://<your-username>.github.io/mgvs-website/`.

## 🖼️ Updating Images

The website uses placeholders. To add real images:

1. Place your photo (e.g., `event.jpg`) in the `assets/images/` folder.
2. Open the HTML file (e.g., `gallery.html`).
3. Find the placeholder `div` (e.g., `<div class="gallery-img-placeholder">`).
4. Replace it with an image tag:
   ```html
   <img src="assets/images/event.jpg" alt="Description of event">
   ```

## 🎨 Customizing Colors

To change the color theme, edit `css/styles.css` and update the variables at the top:

```css
:root {
    --color-primary: #630F0F;   /* Change this hex code */
    --color-secondary: #F4B41A;
    ...
}
```
