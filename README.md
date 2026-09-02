# Security Log

A running, public log of cybersecurity work — CTF writeups, home-lab notes, tool
experiments, cert study, vuln research, whatever I'm actually doing. The point
is a visible, dated trail of activity, not polished tutorials.

Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Writing a new post

1. Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`.
2. Start it with front matter:

   ```yaml
   ---
   layout: post
   title: "Short Title"
   date: 2026-09-02
   tags: [ctf, notes]
   ---
   ```

3. Write the post in Markdown below the front matter.
4. Commit and push to `main` — GitHub Pages rebuilds the site automatically.

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Enabling GitHub Pages (one-time, needs a repo admin)

Settings → Pages → Build and deployment → Source: **Deploy from a branch** →
Branch: `main` / `(root)`.
