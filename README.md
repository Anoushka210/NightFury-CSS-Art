# NightFury-CSS-Art 🐉

A pure **HTML + CSS** recreation of **Toothless**, the Night Fury from *How to Train Your Dragon*.

No `<img>` tags. No `<svg>`. No `<canvas>`. Every shape — the head, jade-green eyes, ears, wings, scaled body, legs, and the red prosthetic tail fin — is built from plain `div`/`span` elements styled with `border-radius`, `clip-path`, `box-shadow`, gradients, and `transform`.

## ✨ Features

- Detailed head: forehead bumps, rounded cheeks, layered ears, brows, snout with nostrils, a smiling mouth with small teeth, jaw and chin
- Huge emerald-green eyes with radial-gradient shading, a vertical slit pupil, dual highlights, and separate top/bottom eyelids
- Muscular torso with chest/belly/neck volume and a fake scale texture built entirely from repeating radial gradients (no images)
- Two-layer bat-style wings, each with a shoulder joint, upper arm, four tapering "finger" bones, and a scalloped membrane
- Long segmented tail ending in the natural fin plus the iconic red prosthetic fin (with ribs and strap)
- Four legs (larger hind legs, smaller front legs) each with thigh, shin, foot and individual claws
- Glowing cyan-blue spine plates down the back with a pulsing glow
- Subtle blue rim-lighting simulating moonlight from the upper left
- **Animations:** idle breathing, ear twitch, blinking, tail sway, floating bob, eye-glow pulse, and a wing flap triggered on hover
- Cinematic night-sky background: gradient sky, glowing cratered moon, 35 twinkling stars, drifting mist layers, and floating light particles — all pure CSS, no images

## 📁 Project structure

```
NightFury-CSS-Art/
│
├── index.html
├── style.css
└── README.md
```

## ▶️ Run locally

Just open `index.html` in any browser — no build step, no dependencies.

## 🚀 Deploy on GitHub Pages

1. Create a new GitHub repository, e.g. `NightFury-CSS-Art`.
2. Push these files to the repo:
   ```bash
   git init
   git add index.html style.css README.md
   git commit -m "Toothless pure CSS art"
   git branch -M main
   git remote add origin https://github.com/<your-username>/NightFury-CSS-Art.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then **Save**.
6. After a minute, your site will be live at:
   ```
   https://<your-username>.github.io/NightFury-CSS-Art/
   ```
