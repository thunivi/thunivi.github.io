# thunivi.github.io

Static site for Thunivi's public bio page and customer policy pages, published at <https://thunivi.in/>.

## Project structure

```text
.
├── index.html              # Root redirect to /bio
├── assets/
│   ├── analytics.js        # Shared Google Analytics bootstrap
│   └── styles.css          # Shared policy page styles
└── bio/
    ├── index.html          # Main bio and contact links page
    ├── shipping/index.html # Shipping & delivery policy
    ├── returns/index.html  # Returns, exchanges, and refunds policy
    └── *.svg / *.png       # Brand and social assets
```

## Local preview

This repository is a plain static website with no build step. To preview it locally:

1. Open a terminal in the repository root.
2. Start a simple static server:

   ```bash
   python3 -m http.server 8000
   ```

3. Open <http://localhost:8000/> in your browser.

## Editing guidelines

- Keep changes small and focused because the site is deployed directly from static files.
- Shared policy styling belongs in `assets/styles.css`.
- Shared Google Analytics bootstrapping belongs in `assets/analytics.js`.