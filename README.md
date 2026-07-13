# yasinmazloumi.com

Personal homepage of **Yasin Mazloumi** (also published as *Abbas Mazloumi*) —
Senior ML Research Engineer at Harvard's Kempner Institute.

A static, single-page site — plain HTML, CSS, and JavaScript, served directly by
**GitHub Pages** from `main`. No build step, no dependencies.

## Structure
- `index.html` — the entire site (inline CSS + JS, fully self-contained)
- `headshot.jpg` — profile photo
- `YasinMazloumi.pdf` — CV (linked from the page)
- `CNAME` — custom domain (yasinmazloumi.com)
- `.nojekyll` — serve the files as-is (static hosting)

## Local preview
Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080   # then visit http://localhost:8080
```
