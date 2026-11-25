# dir-skz-dev

Short-URL redirect: https://dir.skz.dev → https://directory.skz.dev

Served by GitHub Pages from `main`. Static `index.html` and `404.html` fire
a `0`-second meta refresh + `location.replace` (preserves query+hash, doesn't
trap the back button), declare `<link rel="canonical" href="https://directory.skz.dev/">`
without a conflicting `noindex` directive so search engines consolidate signals
cleanly, and mirror `directory.skz.dev`'s Open Graph / Twitter Card metadata
for link unfurlers.
