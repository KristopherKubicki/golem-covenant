# GitHub Pages setup

This repository is ready for GitHub Pages with the custom domain `golem.md`.

## Files that matter

- `CNAME`: declares `golem.md` for GitHub Pages.
- `index.html`: public landing page.
- `golem.md`: covenant/spec root.
- `golem.yml`: minimum machine-readable enforcement manifest.
- `soul.md`: lowercase public soul template.
- `.nojekyll`: keeps GitHub Pages from treating underscore or dot-like paths as Jekyll internals.

## GitHub repository settings

After pushing the repo:

1. Open repository settings.
2. Go to Pages.
3. Set Source to `Deploy from a branch`.
4. Select branch `main`, folder `/`.
5. Save.
6. Confirm the custom domain is `golem.md`.
7. Enable HTTPS after DNS resolves.

## DNS records for apex domain

For GitHub Pages apex domains, set these `A` records:

```text
golem.md.  A  185.199.108.153
golem.md.  A  185.199.109.153
golem.md.  A  185.199.110.153
golem.md.  A  185.199.111.153
```

Optional IPv6:

```text
golem.md.  AAAA  2606:50c0:8000::153
golem.md.  AAAA  2606:50c0:8001::153
golem.md.  AAAA  2606:50c0:8002::153
golem.md.  AAAA  2606:50c0:8003::153
```

For `www`:

```text
www.golem.md.  CNAME  kristopherkubicki.github.io.
```

GitHub Pages serves the apex domain from the repository's `CNAME` file; the
`www` record is optional, but useful if you want `www.golem.md` to resolve too.

## Redirect to a GitHub repository

If the desired behavior is a hard redirect to a GitHub repository rather than
serving this landing page, use Cloudflare, Netlify, or another edge host to issue
a 301/302 redirect. GitHub Pages is better for serving the public covenant page
and linking to the GitHub repository.
