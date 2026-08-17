<<<<<<< HEAD
# personal-website
=======
# Tin Nilar Hlaing — Personal Website

A static portfolio site showcasing engineering skills, experience, and contact info. Hosted for free on [GitHub Pages](https://pages.github.com/).

**Live URL (after setup):** `https://<your-github-username>.github.io`

## What's included

- Responsive single-page site (HTML, CSS, JS — no build step)
- Sections: About, Skills, Experience, Education, Contact
- Content sourced from resume

## Deploy to GitHub Pages (free)

### 1. Create the GitHub repository

On GitHub, create a **public** repository named exactly:

```text
<your-github-username>.github.io
```

For example, if your GitHub username is `tinnilarhlaing`, the repo must be `tinnilarhlaing.github.io`.

> **Note:** This folder is named `tinnilarhlaing.github.io` based on your LinkedIn handle. Rename the folder if your GitHub username is different.

### 2. Push this project

From this directory:

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin git@github.com:<your-github-username>/<your-github-username>.github.io.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Open the repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Choose branch **main**, folder **/ (root)**
4. Click **Save**

Your site will be live in 1–2 minutes at `https://<your-github-username>.github.io`.

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
python3 -m http.server 8080
```

Then visit [http://localhost:8080](http://localhost:8080).

## Customize

| File | What to edit |
|------|----------------|
| `index.html` | Copy, experience bullets, links |
| `css/style.css` | Colors, fonts, layout |
| `js/main.js` | Mobile nav behavior |

## Optional: custom domain

1. Buy a domain (e.g. from Namecheap, Google Domains)
2. Add a `CNAME` file with your domain (e.g. `tinnilarhlaing.com`)
3. Configure DNS with your registrar (GitHub docs: [Managing a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site))

## License

Personal portfolio — use and modify freely.
>>>>>>> df34dca (initial personal website)
