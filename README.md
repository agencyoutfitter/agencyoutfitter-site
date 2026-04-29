# Agency Outfitter

Tools and services for independent insurance agencies.

Static site (Hugo + PaperMod) deployed to Cloudflare Pages on push to `main`.

- Custom domain: `agencyoutfitter.com`
- CF Pages project: `agencyoutfitter-site`
- Built with Hugo `0.157.0` extended.

## Local dev

```bash
hugo server -D
```

## Deploy

Push to `main`. The GitHub Action handles build + deploy.
