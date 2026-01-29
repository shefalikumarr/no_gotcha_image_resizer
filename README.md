# Image Compressor

A free, simple image compressor that runs entirely in your browser. No server uploads, no ads, no tracking, no data collection.

## Why this exists

Most online image compression tools are:
- Full of ads
- Slow and bloated
- Upload your images to their servers
- Require sign-ups or payments

This tool is different. It's a single HTML file that compresses images using your browser's built-in capabilities. Your images never leave your computer.

## Features

- **100% client-side** - All processing happens in your browser
- **No data collection** - Nothing is uploaded, tracked, or stored
- **No ads** - Clean, simple interface
- **Bulk compression** - Process multiple images at once
- **Configurable** - Set target file size and quality
- **Open source** - MIT licensed, fork it, modify it, host it yourself

## Usage

### Online

Visit the hosted version at: `[your-url-here]`

### Local

1. Download or clone this repository
2. Open `index.html` in your browser

Or serve it locally:

```bash
# Python 3
python3 -m http.server 8000

# Then open http://localhost:8000
```

## How it works

1. Drop images onto the page or click to select files
2. Set your target file size (default: 10 MB) and quality (default: 0.85)
3. Images are compressed automatically using the HTML5 Canvas API
4. Click "Download All" to save compressed images

The tool converts images to JPEG format and iteratively reduces quality until the target file size is reached.

## Privacy

- Images are processed entirely in your browser using JavaScript
- No images or data are sent to any server
- No cookies, no analytics, no tracking
- The page works offline after initial load

## Browser Support

Works in all modern browsers:
- Chrome / Edge
- Firefox
- Safari

## Self-hosting

This is a single HTML file with no dependencies. To host it yourself:

1. Copy `index.html` to your web server
2. Update the `<link rel="canonical">` URL
3. Update the GitHub link in the footer
4. Done

Works great on GitHub Pages, Netlify, Vercel, or any static hosting.

## Contributing

Contributions are welcome. Please keep the tool simple and focused.

## License

MIT License - do whatever you want with it.
