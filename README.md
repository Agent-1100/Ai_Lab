# AI Research Lab Website (Multi-Page Version)

This version converts the original single-file site into multiple HTML pages.

## Structure
- `index.html` — landing page
- `members.html` — member directory
- `member-*.html` — separate profile page for each member
- `achievements.html` — publications and achievements archive
- `about.html` — lab/site overview
- `assets/style.css` — shared styles
- `assets/script.js` — shared mobile menu, theme toggle, and slideshow behavior

## How to publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload the full contents of this folder to the repository root.
3. Make sure `index.html` stays in the root folder.
4. Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, choose `Deploy from a branch`.
6. Select the `main` branch and `/root` folder.
7. Save, then wait for GitHub to publish the site.

## Git commands
```bash
git init
git add .
git commit -m "Add multi-page AI research lab website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## How to customize
- Replace placeholder images with your real lab photos.
- Update member pages with real names, bios, emails, and publications.
- Replace sample DOI links with your actual papers.
- Add more pages later using the same shared header and footer layout.
