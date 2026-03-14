# App Icons

This directory contains the icons needed for the PWA.

## Icon Generation

To generate PNG icons from the SVG source, run:

```bash
npm install sharp
node generate-icons.js
```

This will generate all required icon sizes automatically.

## Manual Generation

If you prefer to generate icons manually, you'll need the following sizes:

### Standard Icons
- icon-72x72.png
- icon-96x96.png
- icon-128x128.png
- icon-144x144.png
- icon-152x152.png
- icon-192x192.png
- icon-384x384.png
- icon-512x512.png

### Maskable Icons (for adaptive icons on Android)
- icon-maskable-192x192.png
- icon-maskable-512x512.png

### Apple Touch Icon
- apple-touch-icon.png (180x180)

### Screenshots (optional)
- screenshot-1.png (540x720) - Mobile view
- screenshot-2.png (1280x720) - Desktop view

## Online Tools

You can use these online tools to generate icons:
- [PWA Asset Generator](https://www.pwa-asset-generator.com)
- [Icon Generator](https://icon-generator.com)
- [Favicon Generator](https://www.favicon-generator.org)

Use the SVG from `public/icon.svg` as the source.
