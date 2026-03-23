# Melbourne Gas & Air Conditioning Group
## Post-Quote Conversion Landing Page

A high-converting landing page designed to convert warm leads (post-quote) into confirmed installations. Built with vanilla HTML/CSS/JS — no frameworks, no dependencies, no build step required.

---

## 📁 File Structure

```
mgag-landing-page/
├── index.html     ← The landing page (upload this)
└── README.md      ← This file
```

---

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `mgag-landing-page`)
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Your page will be live at `https://yourusername.github.io/mgag-landing-page/`

---

## ✏️ Customisations Before Going Live

| What | How |
|------|-----|
| **Owner video** | Find `<!-- Replace with:` comment and swap in your `<iframe>` URL |
| **Team video** | Second video placeholder — same process |
| **Phone number** | Search `0397152504` — update in sticky bar, hero CTA, and final CTA |
| **ABN** | Replace `[Your ABN]` in the footer |
| **Email** | Replace `info@melbournegasgroup.com.au` in the final CTA if needed |
| **Google Reviews link** | Update the `href` on the `.google-badge` anchor |

---

## 🔧 Adding Your Video

Find this comment in `index.html`:

```html
<!-- Replace with: <iframe src="YOUR_VIDEO_URL" ... -->
```

Replace the `<div class="video-placeholder">` block with:

```html
<div style="border-radius:16px;overflow:hidden;border:2px solid rgba(26,117,187,0.3);">
  <iframe src="YOUR_VIDEO_URL"
    style="width:100%;aspect-ratio:9/16;border:0;display:block;"
    allow="autoplay; fullscreen"
    allowfullscreen>
  </iframe>
</div>
```

- **YouTube:** `https://www.youtube.com/embed/VIDEO_ID`
- **Vimeo:** `https://player.vimeo.com/video/VIDEO_ID`

---

## 🎨 Brand Colours

| Colour | Hex |
|--------|-----|
| Deep Navy | `#213150` |
| Brand Blue | `#1a75bb` |

---

*Melbourne Gas & Air Conditioning Group · melbournegasgroup.com.au*
