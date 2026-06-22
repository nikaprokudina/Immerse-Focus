# Immerse Flow Website

This folder contains the Immerse Flow website with Privacy Policy, Terms of Service, and Support pages.

## Files

- `index.html` - Home page
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `support.html` - Support & FAQ
- `style.css` - Styles (Immerse Flow brand colors and design)

## How to publish with GitHub Pages

1. **Commit and push these files:**
   ```bash
   git add docs/
   git commit -m "Add Immerse Flow website (Privacy, Terms, Support)"
   git push
   ```

2. **Enable GitHub Pages:**
   - Go to your GitHub repository: https://github.com/nikaprokudina/Focus-Timer
   - Click **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select branch: **master** (or **main**)
   - Select folder: **/docs**
   - Click **Save**

3. **Your website will be live at:**
   ```
   https://nikaprokudina.github.io/Focus-Timer/
   ```

4. **Update the app URLs:**
   - Privacy Policy: `https://nikaprokudina.github.io/Focus-Timer/privacy.html`
   - Terms of Service: `https://nikaprokudina.github.io/Focus-Timer/terms.html`
   - Support: `https://nikaprokudina.github.io/Focus-Timer/support.html`

5. **Update SettingsView.swift** with the real URLs:
   ```swift
   // Replace placeholder URLs with:
   "https://nikaprokudina.github.io/Focus-Timer/privacy.html"
   "https://nikaprokudina.github.io/Focus-Timer/terms.html"
   ```

## Customization

- **Colors:** Edit `style.css` CSS variables at the top
- **Content:** Edit the HTML files
- **Company name:** Currently set to "FREESAIL INC" - update in all HTML files if needed

## Design

The website uses:
- Immerse Flow brand colors (Blush gradient, Purple, Orange accent)
- Nunito font (same as app)
- Responsive design for mobile
- Clean, modern layout similar to Crispshot example
