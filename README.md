# Dr Indu Bala – academic website

A single-page academic site for GitHub Pages. No build step, no dependencies.

## Put it online

1. Sign in to GitHub and create a new **public** repository named exactly
   `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. Upload everything in this folder (`index.html`, `README.md`, `.nojekyll`, and the `images` folder)
   using **Add file → Upload files**, then **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

## Add your photo

Save a square photo as `images/profile.jpg` and upload it to the `images` folder.
Until then the site shows your initials instead.

## Update publications

Open `index.html`, find `const PUBS = [` and copy any line. Each entry looks like:

```js
{type:"journal", year:2026, authors:"A. Author, I. Bala", title:"Paper title",
 venue:"Journal name", details:"12(3), 45–67", doi:"10.xxxx/xxxxx"},
```

- `type` is one of `journal`, `conference`, `chapter`, `preprint`, `thesis`
- write your name as `I. Bala` so it is highlighted
- use `doi`, `arxiv` (just the number, e.g. `2505.15741`) or `url` for links

Everything else (filters, year grouping, counts) updates automatically.

## Other edits

Text for About, Research, Recognition, Teaching and Talks is plain HTML in `index.html`.
Change the "Last updated" date in the footer when you edit.
