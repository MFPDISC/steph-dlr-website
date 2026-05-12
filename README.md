# Steph DLR — MMA Coach Website

Clean, professional single-page website for Steph DLR. Built for GitHub Pages hosting with WhatsApp checkout.

---

## Project Structure

```
steph-dlr-website/
├── index.html        ← Main website (single file, everything included)
├── images/           ← Drop photos here (see below)
│   ├── hero-bg.jpg
│   ├── about-photo.jpg
│   └── products/
│       ├── tee.jpg
│       ├── shorts.jpg
│       ├── program-1.jpg
│       └── program-2.jpg
└── README.md
```

---

## Before Going Live — Checklist

### 1. WhatsApp Number
Search for `27000000000` in `index.html` and replace with Steph's real number.
Format: country code + number, no `+` or spaces.
Example: `27821234567`

### 2. YouTube Channel URL
Search for `https://youtube.com/@StephDLR` and replace with the real channel link.

### 3. Stats (Hero Section)
Update the three stats in the hero:
- `10+` Years Coaching
- `500+` Athletes Trained
- `3` Disciplines

### 4. Products
Update names, descriptions, and prices in the Shop section.
Current placeholders:
- DLR Signature Tee — R350
- DLR Training Shorts — R480
- MMA Foundations Program — R250
- Advanced Striking Bible — R380

### 5. Add Photos
Replace the grey placeholder boxes with real images.
In `index.html`, find `.about-frame` and `.product-img` divs and replace with:

```html
<img src="images/about-photo.jpg" alt="Steph DLR" style="width:100%; height:100%; object-fit:cover;">
```

---

## Deploying to GitHub Pages

1. Create a new GitHub repo (e.g. `stephdlr-website`)
2. Upload this entire folder contents to the repo root
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)`
5. Save — your site will be live at `https://yourusername.github.io/stephdlr-website`

---

## Customising in Windsurf

All styles are in the `<style>` block at the top of `index.html`.

Key CSS variables (easy to change colours):
```css
--red: #c8382a;       /* Main accent colour */
--black: #0a0a0a;     /* Background */
--white: #f5f2ed;     /* Text colour */
--muted: #8a8680;     /* Secondary text */
--whatsapp: #25D366;  /* WhatsApp button */
```

Sections are clearly commented:
- `<!-- NAV -->`
- `<!-- HERO -->`
- `<!-- ABOUT -->`
- `<!-- YOUTUBE -->`
- `<!-- PRODUCTS -->`
- `<!-- CONTACT -->`
- `<!-- FOOTER -->`
