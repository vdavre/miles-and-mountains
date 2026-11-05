# Miles & Mountains

A responsive motorcycle travel journal built with React + Vite. Adventure-earthy visual direction: olive, forest green, warm stone, parchment and muted ochre.

## Run locally
1. Install Node.js LTS: https://nodejs.org/
2. Open this folder in VS Code.
3. Run `npm install`, then `npm run dev`.
4. Open the local URL Vite prints (usually http://localhost:5173).

## Replace photo placeholders
The site works without photos. If an image is missing, a styled placeholder appears automatically.
Add your own photos using these exact paths:
- `public/images/rides/ride-01.jpg`
- `public/images/rides/ride-02.jpg`
- `public/images/rides/ride-03.jpg`
- `public/images/gallery-01.jpg`
- `public/images/gallery-02.jpg`
- `public/images/gallery-03.jpg`
- `public/images/gallery-04.jpg`

Use landscape JPG/WEBP images around 1600px wide. Keep filenames exact or update paths in `src/main.jsx`.

## Personalise
In `src/main.jsx`, update ride stories, distances, dates, destination descriptions, current bike, home base, and the placeholder contact email `hello@milesandmountains.example`.

## Build
Run `npm run build`; production output is `dist`.

## Deploy to Vercel
Create a separate GitHub repository called `miles-and-mountains`, upload this project (not `node_modules` or `dist`), import it in Vercel, choose Vite, build command `npm run build`, output directory `dist`, then deploy.
