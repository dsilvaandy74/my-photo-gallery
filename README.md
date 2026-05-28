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

## Development & Build

### Prerequisites
- Node.js 18+ (https://nodejs.org)

### Install dependencies
```bash
npm install
```

### Development (with hot reload)
```bash
npm run dev
```

### Production Build
```bash
npm run build
```
This generates an optimized `dist/output.css` file.

## Deployment

### Quick Deploy (Recommended for beginners)

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the entire `photo-gallery` folder (or zip it first).
3. Your site will be live in seconds with a random URL.
4. You can later connect a custom domain.

### Deploy with Git (Recommended long-term)

1. Push this folder to a GitHub repository.
2. On Netlify:
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub repo
   - Deploy settings:
     - Build command: (leave empty)
     - Publish directory: `.` (or leave as default)
3. Your site will auto-deploy on every push.

### GitHub Pages (Free alternative)

1. Push to GitHub.
2. Go to repo Settings → Pages.
3. Source: Deploy from a branch → Branch: `main` / Root.
4. Your site will be available at `https://<username>.github.io/<repo-name>`

## License

Private project for personal use.

---
Built with ❤️ for Anand's personal memories.