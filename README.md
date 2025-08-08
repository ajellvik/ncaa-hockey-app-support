# NCAA Hockey App - Support Website

This is the support website for the NCAA Hockey App, built to be hosted on GitHub Pages.

## Setup Instructions

Follow these steps to create the GitHub repository and enable GitHub Pages:

### 1. Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the "+" icon in the top right and select "New repository"
3. Set the repository name to: `ncaa-hockey-app-support`
4. Make it **Public** (required for free GitHub Pages)
5. Don't initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### 2. Push Your Local Repository

After creating the repository on GitHub, run these commands in your terminal:

```bash
# Add the GitHub repository as remote origin
git remote add origin https://github.com/ajellvik/ncaa-hockey-app-support.git

# Push your code to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 4. Your Support URL

Once GitHub Pages is enabled, your support website will be available at:

**https://ajellvik.github.io/ncaa-hockey-app-support/**

It may take a few minutes for the site to be available after enabling Pages.

## Features

This support website includes:
- Comprehensive FAQ section
- Contact information
- Bug reporting links
- App information
- Privacy details
- Responsive design that works on all devices
- Professional styling with your app's branding

## Updating the Website

To make changes to the website:

1. Edit the HTML or CSS files locally
2. Commit your changes: `git add . && git commit -m "Update website"`
3. Push to GitHub: `git push origin main`
4. Changes will automatically deploy to GitHub Pages

## Files

- `index.html` - Main website content
- `styles.css` - Styling and responsive design
- `README.md` - This file with setup instructions
