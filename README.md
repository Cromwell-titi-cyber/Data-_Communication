# Data Communication Assignment

This repository contains a modern, responsive personal academic website for the course assignment.

Files:
- `index.html` — semantic markup and content
- `styles.css` — styling and responsive layout
- `script.js` — interactive features (smooth scroll, theme toggle, typing effect)
- `images/profile-placeholder.jpg` — placeholder profile image (replace with your photo)

Live preview:
- You can host this site on GitHub Pages after pushing the repository.

How to upload and publish on GitHub (local machine):

1. Initialize a git repository and commit files

```bash
cd "c:/Users/ellas/Desktop/Data"
git init
git add .
git commit -m "Add Data Communication Assignment site"
```

2. Create the repository on GitHub named `data-communication-assignment` (use the web UI)

3. Add remote and push

```bash
git remote add origin https://github.com/<your-github-username>/data-communication-assignment.git
git branch -M main
git push -u origin main
```

4. Enable GitHub Pages
- Go to the repository on GitHub → Settings → Pages
- Under 'Source' choose `main` branch and `/ (root)` folder, save
- The site will be published at `https://<your-github-username>.github.io/data-communication-assignment/`

Notes:
- Replace placeholder links in `index.html` with your actual GitHub repo URL and Turnitin URL.
- If `git` is not available on your machine, install Git: https://git-scm.com/

Optional improvements / bonus features:
- Replace `images/profile-placeholder.jpg` with your circular photo
- Add more videos and Expand the timeline
- Configure GitHub Actions for CI or automatic deploys

If you want, I can try to create the GitHub repo and push for you, but I need credentials or access token — otherwise follow the steps above locally.
