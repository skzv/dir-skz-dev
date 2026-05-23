# dir-skz-dev

Short-URL redirect: https://dir.skz.dev → https://directory.skz.dev

Served by GitHub Pages from `main`. Single static HTML page that fires
a meta refresh + `location.replace` (preserves query+hash, doesn't
trap the back button), with `<link rel="canonical">` and
`<meta name="robots" content="noindex">` so search engines treat
`directory.skz.dev` as the canonical URL.
