# Looped Creative Studio

A brand-new standalone one-page website for **Looped Creative Studio**, a premium creative and digital studio focused on strategy, design, websites, content, SEO, AI integration, automation, and digital systems.

## Project structure

```text
.
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

## How to preview with Live Server

1. Open this folder in VS Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. Preview and test at desktop, laptop, tablet, and mobile widths.

You can also preview with any static server, for example:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173` in a browser.

## Where to replace images

The current site uses polished CSS visual compositions and clearly labeled visual placeholders instead of blank rectangles. Replace these with final brand photography or project imagery in:

```text
assets/images/
```

Suggested future files:

- `studio-workspace.jpg` for the hero workspace visual
- `founder-portrait.jpg` or `studio-interior.jpg` for the About section
- `project-now-elevate.jpg`
- `project-coolvu-savannah-hilton-head.jpg`
- `project-black-ink-solutions.jpg`
- `project-velvet-wreckage.jpg`
- `project-broken-memoirs.jpg`
- `project-looped-creative-studio.jpg`

After adding images, update the relevant visual blocks in `index.html` and style them in `css/styles.css`.

## Where to update contact links

Update the footer placeholders in `index.html`:

- Email placeholder: `placeholder@example.com — update before launch`
- Instagram placeholder: `@placeholder — update before launch`

If social icons are added later, place icon assets in:

```text
assets/icons/
```

## How to connect the inquiry form

The inquiry form is front-end only for now.

### Netlify Forms

To connect with Netlify Forms later:

1. Add `data-netlify="true"` to the `<form>` element.
2. Add a hidden form-name field.
3. Set a real form name, for example `name="project-inquiry"`.
4. Deploy the static site to Netlify.

Example:

```html
<form class="inquiry-form" name="project-inquiry" method="post" data-netlify="true">
  <input type="hidden" name="form-name" value="project-inquiry" />
</form>
```

### Formspree

To connect with Formspree later:

1. Create a Formspree form endpoint.
2. Replace the form `action="#"` with the Formspree endpoint URL.
3. Keep `method="post"`.
4. Test submissions before launch.

Example:

```html
<form class="inquiry-form" action="https://formspree.io/f/YOUR_FORM_ID" method="post">
```

## How to deploy later

This is a static website and can be deployed to:

- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages
- Any static hosting provider

General deployment steps:

1. Commit the project to a Git repository.
2. Connect the repository to the hosting provider.
3. Use the repository root as the publish directory.
4. No build command is required.
5. Add final contact links and production imagery before launch.

## Notes

- The homepage is the only HTML page intentionally created for this version.
- The site includes smooth scrolling, reveal animations, subtle shimmer accents, a loading transition, accessible navigation, visible focus states, responsive layouts, and reduced-motion support.
- No testimonials, statistics, awards, or unsupported claims have been added.
