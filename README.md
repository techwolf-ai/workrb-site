# workrb-site

Static site for [WorkRB](https://github.com/techwolf-ai/workrb), served at
[techwolf-ai.github.io/workrb-site](https://techwolf-ai.github.io/workrb-site).

Deployed to GitHub Pages from the repo root by `.github/workflows/deploy.yml`
on push to `main`.

## Local preview

No build step. Serve the repo root with any static file server:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
