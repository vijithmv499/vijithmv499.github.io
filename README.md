# vijithmv499.github.io

Personal site for Vijith M.V. — senior consultant, Bengaluru.

## Files

- `index.html` — live site (Direction C · "Statement Ink")
- `editorial.html` — alternate (Direction A · serif editorial)
- `engineer.html` — alternate (Direction B · engineer's notebook)
- `assets/portrait.jpg` — hero portrait

Each page is fully self-contained (inline CSS, Google Fonts loaded over CDN, no build step). Light / dark toggle is in the top-right of every variant.

## Deploy

Drop these four files (plus the `assets/` folder) at the root of `vijithmv499/vijithmv499.github.io` and push to `master`. GitHub Pages will pick them up within a minute.

```bash
# from the repo root, after replacing files:
git add .
git commit -m "Redesign: senior consultant site (Statement Ink)"
git push origin master
```

The previous `css/`, `styles.css`, and `js/` folders can be deleted — nothing in the new site references them.

## TODO before going fully live

- Drop your résumé PDF at `assets/resume.pdf` and replace the `onclick="alert(...)"` handlers on the "Download résumé" buttons with `href="assets/resume.pdf" download`.
- Replace the three "Coming soon / Draft" writing entries with real posts (or remove the Writing section if you'd rather wait).
- (Optional) Add a favicon at `/favicon.ico`.
