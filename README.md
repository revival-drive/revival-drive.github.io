# Samuel Alabi | Senior DevOps Engineer

Personal portfolio for Samuel Alabi, a Senior DevOps Engineer with 6+ years of experience across cloud infrastructure, fintech and payment systems, Kubernetes, and CI/CD.

The site is static HTML, CSS, and JavaScript with no build step. Resume-based experience, skills, qualifications, and reported outcomes are summarized on the page. Public project and article lists start empty until links are added. Contact details are listed in `content.js`, including the phone number and email from the resume. The home page features the supplied portrait image at `assets/samuel-alabi.jpg`.

## Add projects

Edit `content.js` and add an entry to `projects`:

```js
{ title: "Project name", category: "PLATFORM ENGINEERING", summary: "What it does and the result.", stack: ["Kubernetes", "Terraform"], url: "https://github.com/revival-drive/project" }
```

## Add articles

Add an entry to `articles`:

```js
{ title: "Article title", summary: "A short description.", date: "SEP 2026", category: "CLOUD", url: "https://example.com/article" }
```

## Add contact links

Update LinkedIn, Phone, and Email in the `contacts` list in `content.js`. Use `tel:` for the phone URL and `mailto:` for the email URL.

## Publish

This site has no build step. GitHub Pages can serve the root of the `main` branch at `https://revival-drive.github.io/` when Pages is enabled in **Settings → Pages**.
