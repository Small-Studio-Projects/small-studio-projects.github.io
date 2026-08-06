# Small Studio Projects — Website

The official website for Small Studio Projects, hosted on **GitHub Pages** (free tier, $0.0 budget).

## Live URLs

- `https://small-studio-projects.github.io` — primary (GitHub Pages)
- `https://smallstudio.is-a.dev` — branded subdomain (PR [#46404](https://github.com/is-a-dev/register/pull/46404) pending)

## Stack

| Layer | Choice | Cost |
|-------|--------|------|
| Hosting | GitHub Pages | $0 |
| Brand domain | is-a.dev subdomain | $0 |
| Design system | Vercel-style (Geist, shadow-borders) | $0 |
| CI | GitHub Actions (on push) | $0 |
| Analytics | *(none yet — privacy-first)* | $0 |

## Local dev

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Structure

```
index.html    # single-page landing (hero, workflow, projects, principles, CTA)
```

## Roadmap

- [ ] is-a.dev PR merged → `smallstudio.is-a.dev` live
- [ ] Docs section (Obsidian vault → static)
- [ ] Buy `smallstudio.dev` at-cost when budget allows (zero-migration: add custom domain)
