# Mufuki Website

This is a static website designed for free hosting on GitHub Pages.

## Files
- `index.html` — website content
- `styles.css` — design and responsive layout
- `script.js` — menu, animations and footer year

## Preview on your computer
Open `index.html` in a browser.

## Publish with GitHub Pages
1. Create a free GitHub account.
2. Create a new public repository named `mufuki-website`.
3. Upload all three website files.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the `main` branch and `/root`, then save.
7. GitHub will show your free website address.

## Before publishing
1. Replace the portfolio placeholders with your own images.
2. Replace social media `href="#"` links.
3. Create a free Formspree form and replace `YOUR_FORM_ID` in `index.html`.
4. Confirm the email address and all text.
5. Connect `mufuki.com` after the GitHub Pages site is working.

## Adding an image
Create an `images` folder, add a file such as `march-for-jesus.jpg`, then replace a placeholder div:

```html
<div class="project-image placeholder-one"></div>
```

with:

```html
<img class="project-image" src="images/march-for-jesus.jpg" alt="March for Jesus Ottawa">
```
