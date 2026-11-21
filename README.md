# O/L Library

A multilingual (English, Sinhala and Tamil) resource directory for Sri Lankan G.C.E. O/L students.

## Current build
- Responsive homepage and mobile navigation
- English / Sinhala / Tamil interface switcher
- Search and filters for subject, resource type, year and medium
- Subject directory
- Direct PDF link support
- Apokolips-inspired visual language: dark black/navy panels, blue/cyan accents, animated rain texture, hero entrance, glowing ambient aura, scroll reveal cards, hover lift, button sheen and scroll progress indicator
- Respects `prefers-reduced-motion`

## Add resources
Open `index.html` and find:

```js
const resources=[];
```

Add verified records, for example:

```js
const resources = [
  {
    title: "G.C.E. O/L Mathematics — 2024",
    subject: "Mathematics",
    type: "Past Paper",
    year: 2024,
    medium: "Sinhala",
    description: "Official examination question paper.",
    file: "assets/pdfs/mathematics-2024-sinhala.pdf"
  }
];
```

Create the `assets/pdfs/` folder and add the PDF using GitHub. Supported types include Past Paper, Model Paper, Provincial Paper, Zonal Paper, School Term Test, Study Notes, Short Notes, Marking Scheme and Syllabus.

Only host files that are official, openly licensed, or that you have permission to redistribute. Keep source and attribution information for each resource.

## GitHub Pages
1. Open repository **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Choose `main` and `/(root)`, then Save.
4. GitHub Pages will publish the site at the repository's Pages URL.

The initial version is a static frontend. No real PDF archive has been populated yet.
