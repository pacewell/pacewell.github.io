# pacewell.dev

Landing page for **[Pace](https://chromewebstore.google.com/detail/acgkenbhfmpcoelnfihoaicgnepneplj)** — a calm, open-source pomodoro focus timer for Chrome.

Static single-page site served via GitHub Pages at <https://pacewell.dev>.
The extension source lives at
[pacewell/pace-extension](https://github.com/pacewell/pace-extension).

## Deploy

- GitHub Pages, source = `main` / root.
- `CNAME` binds the custom domain `pacewell.dev`.
- DNS (apex): `ALIAS pacewell.dev → pacewell.github.io`, or A records to
  `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.

Edit `index.html` (self-contained: inline CSS, embedded lotus mark) and push.
