# Shengcao Cao — personal website

A single-page personal site. Plain static HTML/CSS/JS — no build step.

```
index.html            # the whole page
assets/css/style.css  # styles (editorial / typographic theme)
assets/img/portrait.jpg
```

## Develop

Open `index.html` directly, or serve locally:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Edit content

Everything is in `index.html`, grouped by section (`hero`, `about`,
`experience`, `education`, `publications`). To add a publication, copy an
`<li class="pub">` block. Colors and fonts live in the `:root` token block
at the top of `assets/css/style.css`.
