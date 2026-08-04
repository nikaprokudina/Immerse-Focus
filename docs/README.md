# Immerse: Pomodoro Focus Timer Website

This folder contains the Immerse: Pomodoro Focus Timer website with Privacy Policy, Terms of Service, and Support pages.

## Files

- `index.html` - Home page
- `privacy.html` - Privacy Policy
- `terms.html` - Terms of Service
- `support.html` - Support page
- `sitemap.xml` - Sitemap for search engines
- `style.css` - Styles (Immerse: Pomodoro Focus Timer brand colors and design)

## How to publish with GitHub Pages

1. **Commit and push these files:**
   ```bash
   git add docs/
   git commit -m "Add Immerse: Pomodoro Focus Timer website"
   git push
   ```

2. **Enable GitHub Pages:**
   - Go to your GitHub repository: https://github.com/nikaprokudina/Immerse-Flow
   - Click **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select branch: **master** (or **main**)
   - Select folder: **/docs**
   - Click **Save**

3. **Your website will be live at:**
   ```
   https://nikaprokudina.github.io/Immerse-Flow/
   ```

4. **Update the app URLs:**
   - Privacy Policy: `https://nikaprokudina.github.io/Immerse-Flow/privacy.html`
   - Terms of Service: `https://nikaprokudina.github.io/Immerse-Flow/terms.html`
   - Support: `https://nikaprokudina.github.io/Immerse-Flow/support.html`

5. **Update SettingsView.swift** with the real URLs:
   ```swift
   // Replace placeholder URLs with:
   "https://nikaprokudina.github.io/Immerse-Flow/privacy.html"
   "https://nikaprokudina.github.io/Immerse-Flow/terms.html"
   ```

## Customization

- **Colors:** Edit `style.css` CSS variables at the top
- **Content:** Edit the HTML files
- **Publisher:** Currently set to "BUNKER GAMES" in the published HTML files

## Design

The website uses:
- Immerse: Pomodoro Focus Timer brand colors (Blush gradient, Purple, Orange accent)
- Nunito font (same as app)
- Responsive design for mobile
- Clean, modern layout similar to Crispshot example
