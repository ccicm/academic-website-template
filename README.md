# Academic Website Template

A free, professional academic website built with Quarto and hosted on GitHub Pages. No coding experience required.

**[→ Full setup guide with screenshots](https://connorconkeymorrison.com/pages/template)**

---

## What you get

- A clean, responsive personal academic website
- Pages for Home, Research & Publications, Education & Experience, and Contact
- Automatic deployment — push a change, site updates within 2 minutes
- Free hosting via GitHub Pages
- Optional custom domain (e.g. `yourname.com`)

---

## Quick start

**Step 1 — Get the template**

Click the green **Use this template** button at the top of this page, then **Create a new repository**. Name it whatever you like.

**Step 2 — Enable GitHub Pages**

In your new repo, go to **Settings → Pages → Source** and select **Deploy from a branch → main → / (root) → Save**.

Your site will be live at `https://yourgithubusername.github.io/your-repo-name` within a few minutes.

**Step 3 — Edit your content**

Clone or download the repo, edit the `.qmd` files with your own details, then push. The site updates automatically.

> See the [full setup guide](https://connorconkeymorrison.com/pages/template) for step-by-step instructions with screenshots, including how to install the tools, edit each page, and set up a custom domain.

---

## Files to edit

| File | What it controls |
|---|---|
| `index.qmd` | Home page — your name, bio, photo, tags |
| `pages/research.qmd` | Research focus, PhD status, publications |
| `pages/history.qmd` | Education, roles, memberships, skills |
| `pages/contact.qmd` | Email and CV link |
| `_quarto.yml` | Site title, navbar links |
| `styles.css` | Colours and fonts — edit `--navy` and `--accent` at the top |
| `images/profile.jpg` | Replace with your own photo |

---

## Changing colours

Open `styles.css` and change the two variables at the top:

```css
--navy: #1a2e4a;    /* headings, buttons */
--accent: #c8922a;  /* highlights, year labels */
```

Any hex colour works.

---

## Built with

- [Quarto](https://quarto.org)
- [GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Pages](https://pages.github.com)
- [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)

---

*Template by [Connor Conkey-Morrison](https://connorconkeymorrison.com)*
