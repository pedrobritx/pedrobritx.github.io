# pedrobritx.github.io

This repository serves the GitHub Pages user site for [`britx.studio`](https://britx.studio/).

The root domain is reserved for the personal portfolio hub. Experimental project repositories without a custom domain of their own are served by GitHub Pages as first-level paths, for example:

- `https://britx.studio/<repo>/`

When a project graduates to production it moves to its own subdomain, such as `https://<name>.britx.studio/`, usually hosted on Vercel.

The `CNAME` file intentionally contains only `britx.studio`; do not assign the apex custom domain to individual project repositories.

The former `britx.me` domain is redirected to `britx.studio` by the `britx-studio` project on Vercel.
