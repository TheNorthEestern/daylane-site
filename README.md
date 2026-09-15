# lane.systems

Daylane's homepage and privacy policy. Plain HTML and one stylesheet — no build
step, no JavaScript, no third-party requests of any kind. `.nojekyll` tells
GitHub Pages to serve the files exactly as they are.

**This repository is a copy. Do not edit it here.** The source of truth is the
`site/` directory of the Daylane server repository, where the policy sits beside
the code whose behaviour it describes — so that a change to what the server does
and a change to what this page claims can be reviewed as one diff. Edit there,
then sync the directory across.

```
index.html          the homepage
privacy/index.html  served at /privacy
style.css           referenced root-relative, so it resolves from both
CNAME               lane.systems
```
