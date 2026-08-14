# mordecai174.github.io
My personal website

## Local development

The site is static (`index.html`), so any static file server works. To preview locally:

```
python3 -m http.server 4173
```

Then open http://localhost:4173. Opening `index.html` directly via `file://` won't load images, since relative asset paths don't resolve without an HTTP server.
