# metalcyanide.github.io

Personal academic website — Hugo + [Blowfish](https://blowfish.page) theme,
deployed to GitHub Pages via Actions on every push to `main`.

## Contract (app-prototype)

- **One user, one problem:** a public academic presence — publications,
  project pages linked to papers, blog — replacing "my CV PDF is my website."
- **Success criteria:** clean `hugo` build; deploys on push; every
  publication row has a working paper link; every project page links at
  least one paper (repos say "coming soon" until public); adding a post or
  publication is a one-file edit; sane on mobile.
- **Kill criterion:** not updated at least once per quarter by mid-2027 →
  archive the repo and go back to the CV PDF.

## Editing

- **Publication:** add one entry to `data/publications.yaml` (newest first).
- **Blog post:** add `content/blog/<slug>/index.md` with title/date/tags.
- **Project:** add `content/projects/<slug>/index.md`; link it from the
  matching `project:` field in `publications.yaml`.
- **CV:** replace `static/cv.pdf`.
- **Code links:** when a repo goes public, replace the "coming soon" line in
  the project page and add `code:` to its `publications.yaml` entries.

## Self-check (run before push)

```bash
hugo --gc --minify          # must exit 0, zero WARN
grep -c 'title:' data/publications.yaml   # expect 7 (or current count)
hugo server                 # eyeball / on phone width; Ctrl-C to stop
```

## Local dev

```bash
git clone --recurse-submodules git@github.com:metalcyanide/metalcyanide.github.io
hugo server   # needs hugo extended (binary in ~/.local/bin on the lab box)
```
