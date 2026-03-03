# 🔍 Media Finder

Upload a photo and discover related content across the web using AI.

**[Live Demo →](https://yourusername.github.io/media-finder)**

## Features

- 📷 **Camera capture** or **file upload**
- 🤖 **AI-powered image analysis** (Hugging Face BLIP model)
- 🎬 **YouTube videos** related to your image
- 📰 **Web articles** from Google, Wikipedia, Reddit
- 🖼️ **Images** from Unsplash, Pexels, Pinterest
- 🚀 **100% client-side** - no server required
- 🔒 **Privacy-first** - no data stored

## Deploy to GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/media-finder`

## How It Works

1. You upload or take a photo
2. The image is sent to Hugging Face's free BLIP model for captioning
3. The AI describes what it sees in the image
4. That description is used to find related content across the web
5. Results include YouTube videos, articles, and images

## Tech Stack

- Pure HTML/CSS/JavaScript (no build step)
- [Hugging Face Inference API](https://huggingface.co/inference-api) for image captioning
- [Unsplash](https://unsplash.com) for related images

## Local Development

Just open `index.html` in a browser. No server needed!

For camera access, you'll need to serve it over HTTPS or localhost:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

Then open http://localhost:8000

## License

MIT - do whatever you want with it.
