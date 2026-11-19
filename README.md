# perfectintegers.com

Source code for the public website at [perfectintegers.com](https://perfectintegers.com/).

The site is static HTML and CSS, published with GitHub Pages. It does not use WordPress or server-side code.

## Local development

Run any local static server from the repository root, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The private source repository is mirrored to the public `perfectintegers-pages` deployment repository. GitHub Pages publishes that repository's `main` branch with the custom domain from `CNAME`.

Keep hosting credentials, DNS backups, and environment-specific configuration outside the public deployment repository.
