# Accident Report User Journey - Interactive Demo

An interactive, single-page HTML demonstration of the user journey for an accident report website. Built for internal UX/strategy discussions and client presentations.

## Features

- **Interactive cards**: Hover (desktop) or tap (mobile) to reveal detailed explanations
- **Responsive design**: Works seamlessly on desktop and mobile devices
- **Zero dependencies**: Single HTML file using Tailwind CDN
- **7-step journey**: Complete flow from awareness to legal routing

## Quick Start

Simply open `index.html` in any modern web browser.

## Deployment Options

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository on GitHub**:
   - Go to https://github.com/new
   - Repository name: `accident-journey-demo` (or your preferred name)
   - Keep it Public
   - Don't initialize with README (we already have files)
   - Click "Create repository"

2. **Push your code**:
   ```bash
   # Already initialized! Just add the remote and push:
   git remote add origin https://github.com/YOUR_USERNAME/accident-journey-demo.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repo → Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select branch: `main` and folder: `/ (root)`
   - Click Save
   - Wait 1-2 minutes, then visit: `https://YOUR_USERNAME.github.io/accident-journey-demo/`

### Option 2: Vercel (Alternative)

1. **Push to GitHub** (follow steps 1-2 from Option 1)

2. **Deploy to Vercel**:
   - Go to https://vercel.com
   - Click "New Project"
   - Import your GitHub repository
   - No configuration needed - Vercel auto-detects static sites
   - Click "Deploy"
   - You'll get a URL like: `https://accident-journey-demo.vercel.app`

### Option 3: Direct File Sharing

Since this is a single HTML file with no dependencies (except Tailwind CDN):
- Upload directly to any web host
- Share via Dropbox/Google Drive and open in browser
- Use a simple HTTP server locally: `python -m http.server 8000`

## Technical Details

- **Framework**: Vanilla HTML + CSS
- **Styling**: Tailwind CSS via CDN
- **No build process**: Ready to deploy as-is
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## User Journey Steps

1. **Trigger & Awareness** - Post-accident search moment
2. **Landing / Hero Experience** - Clear value proposition
3. **Accident Search Wizard** - Guided data collection
4. **Incident Matching** - AI-powered matching
5. **Role & Contact Capture** - Lead qualification
6. **Report Status & Delivery** - Value delivery
7. **Legal Routing & Long-term Value** - Partner connections

## Customization

To customize the content:
1. Open `index.html` in any text editor
2. Modify the step titles, descriptions, or bullet points
3. Update colors by changing the Tailwind classes (e.g., `bg-blue-100` to `bg-purple-100`)
4. Add your company logo by inserting an `<img>` tag in the header

## Files

- `index.html` - The complete interactive demo
- `README.md` - This file
- `.git/` - Git repository (already initialized and committed)

## Next Steps

After deploying, you can:
- Share the URL with your team for feedback
- Use it in client presentations
- Build on it to create the actual wizard prototype
- Extract the design patterns for the production site

---

**Need help?** This is ready to push to GitHub right now. Just create a new repository and run the git commands above!