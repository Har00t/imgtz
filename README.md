# Puppeteer HTML-to-Image API v3

Reliable HTML to Image conversion for Railway.

## Deploy to Railway

1. Upload these 3 files to GitHub (no package-lock.json needed)
2. Deploy from GitHub on Railway
3. Generate domain
4. Test endpoint

## API

**POST /screenshot**
```json
{
  "html": "<!DOCTYPE html>...",
  "width": 1080,
  "height": 1080,
  "format": "png"
}
```

Returns:
```json
{
  "success": true,
  "image": "data:image/png;base64,...",
  "base64": "..."
}
```
