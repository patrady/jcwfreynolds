# J.C. & W.F. Reynolds Oil Producers

A static website for J.C. & W.F. Reynolds Oil Producers, a Texas oil company founded during the Burkburnett oil boom of 1918.

**Live at [www.jcwfreynolds.com](https://www.jcwfreynolds.com)**

## Project Structure

```
├── index.html      # Single-page HTML
├── styles.css      # All styling with responsive breakpoints
├── favicon.svg     # Oil droplet favicon
└── assets/
    └── images/
        └── burkburnett.jpg   # Hero background image
```

## Development

No build process required. Open `index.html` in a browser or use any local server:

```bash
python3 -m http.server 8000
# or
npx serve .
```

## Design

- **Colors**: Dark navy (#1a1a2e) and gold (#d4a84b)
- **Typography**: Playfair Display (headings), Source Sans Pro (body)
- **Responsive**: Breakpoints at 768px and 480px
