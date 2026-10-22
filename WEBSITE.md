# Total Life Tracker Website

This repository contains the static website source for the Total Life Tracker iOS app, including privacy policy and support pages. The source files alone do not confirm that the site is deployed.

## Pages

- **index.html** - Landing page with app introduction and overview
- **privacy-policy.html** - Privacy policy for the iOS app
- **support.html** - Support page with FAQ and contact information

## Features

- Built with Bootstrap 5.3.0 CSS framework
- Fully responsive and mobile-friendly design
- Consistent navigation across all pages
- Professional and clean UI

## Hosting

These HTML files can be hosted on any static web hosting service such as:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Cloudflare Pages

## Local Testing

To test locally, simply open any HTML file in a web browser, or use a local web server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js (with http-server package)
npx http-server -p 8080
```

Then open `http://localhost:8080` in your browser.

## iOS App Integration

After deploying the site, replace `yourdomain.com` below with the confirmed hosting domain and verify both pages before using the URLs in your iOS app's configuration:
- Privacy Policy: `https://yourdomain.com/privacy-policy.html`
- Support: `https://yourdomain.com/support.html`

## Customization

All pages use Bootstrap CDN, so no build process is required. You can customize:
- Content in the HTML files
- Bootstrap theme by changing the CDN link
- Add custom CSS by creating a `style.css` file

## Support Contact

The support page contains an FAQ and displays `support@jcummings.net` as the contact address. Users contact support by emailing that address. There is no contact form or form-submission backend in this website source.
