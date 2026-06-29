# garypezza.github.io

This repository is now a **redirector**. The site moved to
[garypezza.com](https://garypezza.com) (hosted on Cloudflare Pages); the
canonical source lives in the `garypezza.com` repo.

Every page here forwards to the matching path on garypezza.com, so old links
(including App Store privacy/support URLs) keep working:

- `garypezza.github.io/` → `garypezza.com/`
- `garypezza.github.io/nearing/privacy` → `garypezza.com/nearing/privacy`
- `garypezza.github.io/license-quest/privacy` → `garypezza.com/license-quest/privacy`
- any other path → same path on garypezza.com (via `404.html`)

Each stub uses a path-preserving JS redirect plus a `<meta http-equiv="refresh">`
fallback and a `<link rel="canonical">`. Do not add content here; update
garypezza.com instead.
