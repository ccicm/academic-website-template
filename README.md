# Academic Website Template

A free, professional academic website built with Quarto and hosted on GitHub Pages. No coding experience required.

**[→ Full setup guide](https://www.connorconkeymorrison.com/template)**

---

## What you get

- A clean, responsive personal academic website
- Pages for Home, Research & Publications, Education & Experience, Projects, and Contact
- **Live publications** — syncs automatically from your ORCID profile with journal favicons, APA 7 citations, and RIS downloads
- **Reading list** — a curated list of papers pulled from a simple JSON file, shown on the home and research pages
- **Contact form** — powered by Web3Forms, no backend required
- Automatic deployment — push a change, site updates within 2 minutes
- Free hosting via GitHub Pages
- Optional custom domain (e.g. `yourname.com`)

---

## Quick start

**Step 1 — Get the template**

Click the green **Use this template** button at the top of this page, then **Create a new repository**. Name it whatever you like. Make sure it's set to **Public**.

**Step 2 — Enable GitHub Pages**

In your new repo, go to **Settings → Pages → Build and deployment → Source** and select **GitHub Actions → Save**.

Your site will be live at `https://yourgithubusername.github.io/your-repo-name` within a few minutes.

**Step 3 — Edit your content**

Clone or download the repo, edit the `.qmd` files with your own details, then push. The site updates automatically.

> See the [full setup guide](https://www.connorconkeymorrison.com/template) for step-by-step instructions on connecting your ORCID, setting up the contact form, and configuring a custom domain.

---

## Files to edit

| File | What it controls |
|---|---|
| `index.qmd` | Home page — name, bio, photo, tags, stats strip |
| `pages/research.qmd` | Research focus, PhD status, publications (ORCID), reading list |
| `pages/history.qmd` | Education, roles, memberships, skills |
| `pages/projects.qmd` | Optional projects page — remove from `_quarto.yml` if not needed |
| `pages/contact.qmd` | Contact form — replace `YOUR-ACCESS-KEY` with your Web3Forms key |
| `data/reading.json` | Reading list entries — DOIs + notes |
| `_quarto.yml` | Site title, navbar links, LinkedIn URL |
| `styles.css` | Colours and fonts — edit `--navy` and `--accent` at the top |
| `images/profile.jpg` | Replace with your own photo |

---

## Connecting your ORCID

Open `pages/research.qmd` and update these two lines near the bottom:

```js
const ORCID_ID    = 'YOUR-ORCID-ID';     // e.g. '0000-0000-0000-0000'
const SCHOLAR_URL = 'https://scholar.google.com/citations?user=YOURID';
```

Make sure your ORCID profile is set to public. Publications update automatically on every page load — no manual list to maintain.

---

## Setting up the contact form

1. Get a free access key at [web3forms.com](https://web3forms.com)
2. Open `pages/contact.qmd` and replace `YOUR-ACCESS-KEY`:

```html
<input type="hidden" name="access_key" value="YOUR-ACCESS-KEY">
```

---

## Changing colours

Open `styles.css` and edit the two variables at the top:

```css
--navy:   #1a2e4a;   /* headings, buttons, navbar */
--accent: #c8922a;   /* highlights, labels, hover states */
```

Any hex colour works. Some examples:

| Palette | `--navy` | `--accent` |
|---|---|---|
| Navy & amber (default) | `#1a2e4a` | `#c8922a` |
| Deep green & terracotta | `#1e3a2a` | `#c05a4a` |
| Slate & teal | `#1a2a3a` | `#2a8a7a` |
| Plum & coral | `#3a1a3a` | `#c8522a` |

---

## Built with

- [Quarto](https://quarto.org)
- [GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Pages](https://pages.github.com)
- [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)
- [Web3Forms](https://web3forms.com) (contact form)

---

*Template by [Connor Conkey-Morrison](https://connorconkeymorrison.com)*
