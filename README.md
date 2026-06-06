# Palash & Oishe — Hindu Wedding Story Website

A complete static wedding memory website using the uploaded photos and videos.

## What is included

- `index.html` — main website
- `css/style.css` — fully responsive, rebuilt UI/CSS
- `js/script.js` — gallery filters, lightbox, videos, guestbook, private album unlock
- `assets/images/` — optimized wedding images
- `assets/videos/` — wedding videos and hero background video
- `assets/posters/` — video preview images

## Hero video note

The hero background video is now **real full-screen crop** using `object-fit: cover`; no left/right blur background has been used.

## How to preview

Open `index.html` in a browser.

## Private album password

Default password: `15122025`

You can change it in `js/script.js` by searching for:

```js
if (password !== '15122025')
```

## Deployment

This is a static website. You can upload it to Vercel, Netlify, GitHub Pages, or any cPanel hosting.

## Guestbook note

The guestbook stores wishes in the visitor's browser using localStorage. For real public messages, connect it later to Firebase, Google Sheets, or a backend.
