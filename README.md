# iOS Home Screen PWA

This is a Progressive Web App (PWA) that mimics the iOS home screen interface.

## Setup Instructions for GitHub Pages

1. Upload all these files to your GitHub repository:
   - `index.html` - The main HTML file
   - `sw.js` - Service Worker for offline functionality
   - `manifest.json` - Web App Manifest for PWA functionality
   - `apple-touch-icon.png` - App icon for iOS/Android (create a 192x192 or larger PNG image)

2. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Select the branch you want to deploy from (usually `main` or `master`)
   - Click Save

3. Visit your GitHub Pages URL (typically `https://username.github.io/repository-name`)

4. To install as a PWA:
   - On iOS: Open in Safari, tap the Share button, then "Add to Home Screen"
   - On Android: Open in Chrome, tap the menu, then "Install app"

## Troubleshooting

If the PWA functionality isn't working:

1. Make sure all files are in the root directory of your GitHub Pages site
2. Check browser console for any errors
3. Verify that the service worker is registered correctly
4. Make sure you're accessing the site over HTTPS
5. Clear browser cache and try again

For testing PWA install behavior, use Chrome's Developer Tools > Application tab.
