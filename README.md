# Movemates Landing Page

A simple, modern landing page for the Movemates iOS app.

## Overview

This landing page showcases the Movemates app with:
- Hero section with app description
- Key features overview
- Movemates Premium features and benefits
- Download call-to-action
- Links to social media, privacy policy, and contact

## Files

- `index.html` - Main landing page
- `privacy.html` - Privacy Policy page
- `terms.html` - Terms of Service page
- `safety.html` - Safety Tips page
- `styles.css` - CSS styling with responsive design
- `README.md` - This file

## Customization

### Update Links

Replace the placeholder links in `index.html`, `privacy.html`, and `terms.html`:

1. **App Store Link**: Replace `#app-store-link` with your actual App Store URL (appears multiple times)
2. **X (Twitter)**: Replace `#x-link` with your X/Twitter profile URL (in footer of all pages)
3. **Contact Emails**: Update email addresses as needed:
   - `contact@movemates.app` - General contact
   - `privacy@movemates.app` - Privacy inquiries (in privacy.html)
   - `legal@movemates.app` - Legal/terms inquiries (in terms.html)
   - `safety@movemates.app` - Safety concerns (in safety.html)

### Update Legal Content

The privacy policy and terms of service pages contain **placeholder content**. You should:

1. **Review and customize** `privacy.html` with your actual privacy practices
2. **Review and customize** `terms.html` with your actual terms and conditions
3. **Add governing state** in the "Governing Law" section of terms.html (currently says "[Your State]")
4. **Consult a lawyer** before making these pages live, as they contain legally binding language

### Color Customization

Colors are defined as CSS variables in `styles.css` (lines 11-20):

```css
--primary-color: #007AFF;        /* Main brand color */
--secondary-color: #5856D6;      /* Accent color */
--premium-color: #FFD60A;        /* Premium badge color */
--text-dark: #1D1D1F;           /* Primary text */
--text-light: #86868B;          /* Secondary text */
--bg-light: #F5F5F7;            /* Light background */
```

### Content Updates

- Update feature descriptions in the Features section
- Modify Premium feature details if offerings change
- Update copyright year in footer

## Deployment

This is a static website that can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the files to your hosting provider.

## Features Highlighted

### Core Features
- Discover local runners with smart filtering
- Plan group runs (Moves) with location and RSVP
- Direct and group chat messaging
- Rich user profiles with running stats and goals
- Smart matching based on pace and preferences
- Support for runs, walks, and run/walk activities

### Premium Features
- **Travel Discovery Mode**: Find runners in other cities
- **Expanded Move Size**: More than 5 participants (Free: 5, Premium: Unlimited)
- **Additional Active Moves**: More than 3 at once (Free: 3, Premium: Unlimited)
- **Premium Badge**: Exclusive profile badge
- **Unlimited Chat History**: Beyond 30 days (Free: 30 days)
- **Expanded Profile Gallery**: Up to 8 photos (Free: 3, Premium: 8)

## Responsive Design

The landing page is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

Copyright © 2025 Movemates. All rights reserved.
