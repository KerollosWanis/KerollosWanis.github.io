# Kerollos Wanis — Personal Website

Built with [Quarto](https://quarto.org). Clean, minimal academic site with About, Publications, CV, and Contact pages.

---

## Getting Started

### 1. Install Quarto

Download from https://quarto.org/docs/get-started/ and install for your OS.

### 2. Preview the site locally

Open a terminal in this folder and run:

```bash
quarto add schochastics/academicons
quarto preview
```

This opens a live preview in your browser. Changes to `.qmd` files update automatically.

### 3. Fill in your content

Edit these files — all placeholders are in `[brackets]`:

| File | What to edit |
|---|---|
| `index.qmd` | Bio, current position, news items |
| `publications.qmd` | Your papers, grouped by year |
| `cv.qmd` | Education, positions, grants, etc. |
| `contact.qmd` | Email and office address |
| `_quarto.yml` | GitHub/LinkedIn URLs, site title |

### 4. Add your photo

Replace `assets/profile.jpg` with your own headshot (any `.jpg` or `.png`).
Update the filename in `index.qmd` if you use a different name.

### 5. Add your CV PDF

Put your CV PDF at `assets/wanis_cv.pdf`.
The download button on the CV page will automatically link to it.

### 6. Build the site

```bash
quarto render
```

This generates the site into the `docs/` folder.

### 7. Publish on GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages → Source: **Deploy from branch** → Branch: `main` → Folder: `/docs`
3. Your site will be live at `https://yourusername.github.io/repo-name`

---

## Customizing the look

- Colors and fonts: edit `assets/custom.scss`
- Spacing and details: edit `assets/custom.css`
- To change the theme entirely, edit the `theme:` line in `_quarto.yml` — options at https://quarto.org/docs/output-formats/html-themes.html

## Adding a Google Scholar link

In `publications.qmd` and `cv.qmd`, replace `YOURID` in the Google Scholar URL with your actual Scholar user ID (visible in your Scholar profile URL).

---

## Questions?

Quarto docs: https://quarto.org/docs/websites/
