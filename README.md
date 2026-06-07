# Parag Patil — Portfolio

A cinematic single-page portfolio inspired by the video_portfolio reference design.

## 📁 File Structure

```
parag_portfolio/
├── index.html          ← The entire portfolio (HTML + CSS + JS in one file)
├── README.md           ← This file
└── assets/             ← Put your images & video here
    ├── author.jpeg     ← Your profile photo (for the ID badge)
    └── hero.mp4        ← Your intro/reel video (for the hero background)
```

## 🚀 How to Use

1. **Open locally**: Just double-click `index.html` in your browser — no build step needed.

2. **Add your video**:
   - Copy your `.mp4` video into the `assets/` folder
   - Open `index.html` and find this line:
     ```html
     <source src="YOUR_VIDEO_FILE.mp4" type="video/mp4"/>
     ```
   - Change it to:
     ```html
     <source src="assets/hero.mp4" type="video/mp4"/>
     ```

3. **Add your photo** (for the ID badge):
   - Copy `author.jpeg` into the `assets/` folder
   - In `index.html`, find the `<div class="badge-img">👤</div>` line and replace it with:
     ```html
     <img src="assets/author.jpeg" style="width:100%;aspect-ratio:3/4;border-radius:0.8rem;object-fit:cover"/>
     ```

## 🌐 Deploy to Vercel (Free)

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"**
3. Upload this folder or push it to a GitHub repo and import it
4. Vercel will deploy it automatically — no configuration needed

## ✏️ Customisation Tips

- **Colors**: Search for `#ff2a2a` to change the red accent color throughout
- **Name/Logo**: Search for `parag` to update the brand name in navbar & footer
- **Projects**: Each project card is a `<div class="project-card">` block — copy/paste to add more
- **Contact email**: Search for `pparag096@gmail.com` to update
- **Phone**: Search for `84327 36469` to update
