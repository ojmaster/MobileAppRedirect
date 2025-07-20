# Mobile App Redirect Page

A simple webpage that automatically redirects users to the appropriate app store based on their device type.

## How it works

- **iOS devices** (iPhone, iPad, iPod) → Redirects to App Store
- **Android devices** → Redirects to Google Play Store  
- **All other devices** (Desktop, etc.) → Redirects to GitHub

## Setup Instructions

1. Clone the repository
2. Open `index.html` in a text editor
3. Replace the placeholder URLs in the JavaScript section:

```javascript
const APP_STORE_URL = 'https://apps.apple.com/app/your-app-id';  // Your iOS App Store link
const PLAY_STORE_URL = 'https://play.google.com/store/apps/details?id=your.package.name';  // Your Google Play Store link
const FALLBACK_URL = 'https://github.com/yourusername/yourrepo';  // Your Fallback link
```

4. Save the file
5. Upload to your web hosting service or GitHub Pages

## Features

- Automatic device detection
- 1.5-second loading screen with spinner
- Fallback manual link if automatic redirect fails
- Responsive design that works on all screen sizes
- Clean, modern UI with gradient background

## Testing

To test the redirect functionality:
- Use browser developer tools to simulate different devices
- Or test on actual iOS/Android devices
- Desktop browsers will redirect to the GitHub link

## Deployment

This is a static HTML file that can be hosted anywhere:
- GitHub Pages
- Netlify
- Vercel
- Any web hosting service

Simply upload the `index.html` file to your hosting provider.
