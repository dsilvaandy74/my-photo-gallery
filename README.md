# Anand's Memories

A personal, password-protected photo and video gallery.

## Features

- Password protected (password: `dsilva123`)
- Clean, modern gallery interface
- Photos and Videos sections
- Responsive design
- Works offline (static HTML)

## Getting Started

1. Clone the repository
2. Open `index.html` in a browser
3. Enter the password when prompted: `dsilva123`

## Adding New Content

### Photos
1. Add your images to the `images/` folder
2. Update the `PHOTOS` array in `index.html` with the new file paths and captions

### Videos
1. Add your MP4 videos to the `videos/` folder
2. Update the `VIDEOS` array in `index.html`

> **Note:** Very large video files (>100MB) are currently excluded via `.gitignore`. For large videos, consider using Git LFS or hosting them externally (YouTube, Vimeo, etc.) and embedding them.

## Technology

- Pure HTML + Tailwind CSS (via CDN)
- Vanilla JavaScript
- No backend required

## Security Note

This is a **client-side** password protection only. The password is stored in the JavaScript. It is suitable for casual privacy but not for high-security use cases.

## License

Private project for personal use.

---
Built with ❤️ for Anand's personal memories.