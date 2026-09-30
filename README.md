# Samuel Agbokpo | Senior DevOps Engineer

Personal portfolio for Senior DevOps Engineer Samuel Agbokpo, built as a responsive, static GitHub Pages site.

The portfolio uses the professional profile and skills recorded here previously. Project and article lists start empty so that only real work and published writing are shown. LinkedIn and email remain clearly marked for your preferred URLs.

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

Update LinkedIn and Email in the `contacts` list in `content.js`. For email, use a `mailto:` URL such as `mailto:name@example.com`.

## Publish

This site uses plain HTML, CSS, and JavaScript and has no build step. GitHub Pages serves the root of the `main` branch at `https://revival-drive.github.io/` once Pages is enabled in **Settings → Pages**.
