# Isambert Leunga Noukwe: academic website

Static site for GitHub Pages. No build step, no framework.

## Publish it (one time)

1. On GitHub, create a **public** repository named exactly `Isambert.github.io`
   (no README, no .gitignore, no license: leave it empty).
2. On the new repo page, click **uploading an existing file** and drag in the
   *contents* of this folder (index.html, research.html, teaching.html, cv.html,
   style.css, .nojekyll, assets/, papers/). Commit.
3. Go to **Settings > Pages**. Under "Build and deployment", choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute or two the site is live at https://isambert.github.io

## Things to add

- `assets/photo.jpg`: square portrait, at least 300x300 px. Without it the photo is simply hidden.
- `assets/cv.pdf`: your academic CV (see the privacy note below).
- `papers/`: paper PDFs. Then in `research.html`, replace each Google Drive link with
  `papers/filename.pdf` so the links never depend on Drive sharing settings.

## Editing later

Open any .html file on GitHub, click the pencil icon, edit, commit. The site updates
within a minute. To add a paper, copy an existing `<li>...</li>` block in `research.html`.
To change colors or fonts, edit the variables at the top of `style.css`.

## Privacy note about the CV

Do not publish the SSHRC / Canadian Common CV export. It contains your date of birth,
mobile number, personal email, and the names of students you supervise. Use an academic
CV that lists only what you want public.

## Custom domain (optional)

Add a file named `CNAME` containing your domain, and set the DNS records GitHub lists
under Settings > Pages.
