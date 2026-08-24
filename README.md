# Smart Clarity Landing Page

This repository contains the landing page for **Smart Clarity**, a lightweight browser extension that enhances the visual appearance of supported HTML5 videos.

## Features of this Landing Page
- Fully responsive design (Desktop & Mobile)
- Vanilla HTML, CSS, and JavaScript (No heavy frameworks or dependencies)
- Smooth animations and micro-interactions
- Built-in placeholder for the Microsoft Edge Add-ons Store link
- Accessible and semantic markup

## How to Run Locally

Since this landing page is built with static HTML, CSS, and JavaScript, you don't need any complex build tools to run it.

### Option 1: Direct File Opening
Simply double-click the `index.html` file to open it in your default web browser.

### Option 2: Using a Local Development Server (Recommended)
Using a local server ensures that all assets and relative paths resolve correctly.

If you have Node.js installed, you can use `serve`:
```bash
npx serve .
```
Or, if you use VS Code, install the **Live Server** extension and click "Go Live" at the bottom of the editor.

## Deployment

This website can be easily deployed to any static hosting provider. 

### Vercel / Netlify / Cloudflare Pages
1. Push this folder to a GitHub repository.
2. Log into your hosting provider (Vercel, Netlify, Cloudflare).
3. Create a new project and import the repository.
4. Leave the build command empty, and set the publish directory to the root `/` (or whichever folder contains `index.html`).

### GitHub Pages
1. Push to a repository.
2. Go to Repository Settings > Pages.
3. Select the `main` branch and save. Your site will be live in a few minutes.

## Important Note for Launch
Before officially launching the website, make sure to update the Edge Add-ons Store links!

Look for the following comment in `index.html`:
`<!-- Update the Edge Add-ons URL when available -->`
And update the `href="#"` to point to the official Smart Clarity store URL.
