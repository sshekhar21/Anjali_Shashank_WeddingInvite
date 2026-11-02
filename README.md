# Anjali & Shashank — Wedding Invitation Website

A mobile-first, GitHub Pages-ready wedding invitation inspired by the visual flow of the reference template, with original custom artwork and Anjali & Shashank's event details.

## Included

- Full-screen illustrated envelope intro with a clickable golden-seal hotspot and skip control
- Watercolour palace hero with animated petals and elegant typography
- Ornamental invitation card
- Three wedding event cards
- Interactive photo gallery with temporary placeholders
- RSVP form (email handoff; configure recipient before publishing)
- Live countdown to 26 November 2026 (IST)
- Interactive wish-lantern release animation
- Responsive mobile layout and reduced-motion support

## Personalisation

### Replace gallery placeholders

Add your photographs to `assets/photos/` (for example `couple-1.jpg`, `couple-2.jpg`, etc.). Then update the gallery markup in `index.html` to use `<img>` elements and set their `src` paths. The current gallery is intentionally using temporary decorative placeholders.

### Configure RSVP

Open `script.js` and replace:

```js
const RSVP_EMAIL='YOUR_EMAIL@example.com';
```

with the email address that should receive RSVP messages. The form opens the visitor's email app using a pre-filled message. For automatic online collection without requiring the visitor's email app, connect a Google Form or another form endpoint.

### Add music (optional)

Only use music you have permission to publish. Add an MP3 as `assets/ambient.mp3`, then replace the explanatory sound-toggle handler in `script.js` with an audio player. No music file is bundled in this project.

### Add venue and timings

The ceremony timings and venue were not provided, so the project deliberately says that details will be shared soon. Update the event copy in `index.html` once those details are final.

## Publish on GitHub Pages (free)

1. Create a new **public** repository on GitHub.
2. Upload the contents of this folder (the `index.html` file must be at the repository root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

No build step, framework, package manager, or server is required.

## Asset note

The envelope and palace illustrations in `assets/images/` are newly generated artwork for this project. The website uses its own HTML, CSS, and JavaScript rather than copying the reference site's source code. Google Fonts are loaded from Google Fonts; the site otherwise uses local project assets.
