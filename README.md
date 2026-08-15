# Eli Zuerlein — Personal Website

Personal academic website built with [Hugo](https://gohugo.io/) and the
[HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) template.

## Editing content

- Bio / CV data: `data/authors/me.yaml`
- Homepage layout & sections: `content/_index.md`
- Site name, description, theme colors: `config/_default/params.yaml`
- Blog posts: `content/blog/`
- Publications: `content/publications/`
- Projects: `content/projects/`
- Talks/events: `content/events/`

All content is placeholder text right now — search for `[` brackets and
"placeholder" in `data/authors/me.yaml` and `content/_index.md` to find what
needs editing.

## Local development

Requires [Hugo Extended](https://gohugo.io/installation/), [Go](https://go.dev/dl/)
(for Hugo Modules), and [Node.js](https://nodejs.org/) (for Tailwind CSS).

```bash
npm install
hugo server
```

Site will be available at `http://localhost:1313/Eli-Website/`.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the
site and deploys it to GitHub Pages automatically. Enable GitHub Pages for
this repo under **Settings → Pages → Source: GitHub Actions**.

## License

Site content is personal to Eli Zuerlein. The underlying Hugo theme
(HugoBlox Academic CV) is MIT licensed — see [LICENSE.md](LICENSE.md).
