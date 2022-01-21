# Webflow Git

This repository uses a webflow webhook triggered by publish to call a cloudflare worker that rewrites that webhook to a github action webhook trigger that scrapes the newly published site into this repository. 

Benefits:
- Version control for webflow
- Backups of webflow automatically
- Better than 'export' in webflow as this also pulls any CMS pages

From here the code can be taken anywhere including using
- Github actions as CI
- Netlify triggers to deploy a JAMSTACK site
- Etc
