# Personal Academic Website

A single static page, so there's no build step and nothing to install.

## Files

- `index.html`: all the content. Every section has a `<!-- TODO -->` comment explaining what goes there.
- `style.css`: the styling. Change `--accent` at the top to change the link color.
- `Ahmet_Alperen_Gungor_CV.pdf`: the CV linked from the header. If you rename it, update the link in `index.html` too.
- `assets/`: put your photo (`photo.jpg`) here.

## Editing

1. Open `index.html` and replace everything in `[brackets]` plus the "Your Name" placeholders.
2. Replace `assets/profile-placeholder.svg` with your photo and update the `src` of the `<img>` tag.
3. Delete any sections you don't need (News and Experience are optional).
4. Preview it by double-clicking `index.html` to open it in your browser.

## Publishing on GitHub Pages (free)

1. Create a GitHub repository named exactly `YOUR_USERNAME.github.io`.
2. Upload these files to it (drag and drop on github.com works, or use git):
   ```
   git init
   git add .
   git commit -m "Initial website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set Source to "Deploy from a branch", and pick `main` / `(root)`.
4. After about a minute, the site is live at `https://YOUR_USERNAME.github.io`.

To update the site later, edit the files and push again.
