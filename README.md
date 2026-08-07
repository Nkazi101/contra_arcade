# Neon Jungle

A single-file Phaser 3 run-and-gun arcade campaign inspired by classic Contra.

The campaign has four procedural sections: Jungle Assault, Waterfall Ruins, Snow Base, and Alien Core. Terrain palettes, silhouettes, platform tinting, ambient particles, and section banners change as the commando advances.

## Run locally

Open `index.html` directly in a browser, or serve this folder with any static web server:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Deploy

Upload this folder to any static host such as GitHub Pages, Netlify, Vercel, Cloudflare Pages, or an ordinary web server. There is no build step, package install, bundler, database, or asset directory. The only network dependency is the Phaser 3 CDN script declared in `index.html`.

## Controls

- Left/Right arrows or A/D: move
- Up arrow: jump and aim up while firing
- Down arrow: crouch and aim down while firing
- Space, F, or J: fire
- R: restart after win or game over
