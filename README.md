# Dream Convention 2026

University pitch competition website for Dream Convention — a one-night event bringing together students from the University of St. Thomas and the University of Minnesota to pitch to real founders.

## Stack

Plain HTML, CSS, and JavaScript. No build step, no dependencies.

## Project structure

```
DreamConvention/
├── public/               ← served by Vercel
│   ├── index.html        ← main site
│   ├── butterfly.html    ← animation dev sandbox
│   ├── styles.css        ← all styles
│   ├── favicon.svg       ← shooting star favicon
│   └── assets/
│       ├── hero-dream.png
│       ├── speaker-maritza.png
│       ├── speaker-jonathan.png
│       ├── speaker-cole.png
│       └── speaker-caroline.png
├── vercel.json           ← points Vercel at /public
├── .gitignore
└── README.md
```

## Deploying to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import the GitHub repo
4. Vercel auto-detects the config — click **Deploy**

No build settings need to be changed; `vercel.json` handles everything.
