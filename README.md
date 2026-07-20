# Looped Design Studio

A standalone one-page website for **Looped Design Studio**, a funky comic-book-inspired creative studio experience for branding, websites, graphic design, content, strategy, AI systems, and creative technology.

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
│   ├── icons/
│   ├── textures/
│   └── comic-elements/
└── README.md
```

## How to preview

Run a static server from the repository root:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173` in a browser and test desktop, laptop, tablet, and mobile widths.

## Where to add future comic artwork

The current site uses CSS-generated comic compositions and clearly labeled placeholders. Replace or extend artwork in these folders:

- `assets/images/hero-infinity.placeholder` — future hero infinity illustration or animation reference.
- `assets/images/founder-image.placeholder` — real founder image for the About section.
- `assets/textures/halftone-texture.placeholder` — custom halftone or paper texture.
- `assets/comic-elements/comic-burst.placeholder` — reusable burst artwork.
- `assets/comic-elements/speech-bubbles.placeholder` — custom speech bubble artwork.
- `assets/icons/service-icons.placeholder` — service icon set.
- `assets/comic-elements/motion-lines.placeholder` — motion-line overlays.
- `assets/comic-elements/ink-splatter.placeholder` — ink and grain accents.
- `assets/comic-elements/doodle-pack.placeholder` — hand-drawn doodles and stickers.

After adding production artwork, update the related sections in `index.html` and `css/styles.css`.

## Where to update contact links

Update the footer placeholders in `index.html`:

- Email placeholder: `hello@yourdomain.com`
- Instagram placeholder: `@loopeddesignstudio`

## Inquiry form

The inquiry form includes client-side validation and Netlify Forms-ready markup:

- `name="project-inquiry"`
- `method="POST"`
- `data-netlify="true"`
- hidden `form-name` field
- honeypot field

It intentionally does not claim a custom backend. If deploying somewhere other than Netlify, connect the form to the chosen form handling service before launch.

## Notes

- The homepage is the only HTML page for this version.
- The site includes smooth anchor scrolling, reveal animations, loading animation, animated infinity motifs, service accordion cards, mobile navigation, accessible focus states, responsive layouts, and reduced-motion support.
- No unsupported claims, reviews, client names, unrelated brands, portfolio pieces, or fake statistics have been added.
