# Muhammed Mujthaba KK — Portfolio

Personal portfolio site (Flutter Developer).

## Live site (GitHub Pages)

After publishing, your site will be available at:

**https://mujthabakk.github.io/portfolio/**

## Deploy to GitHub Pages

### 1. Create a new repository on GitHub

- Name: `portfolio` (or any name you prefer)
- Public repository
- Do **not** add a README, .gitignore, or license (this folder already has files)

### 2. Push this project

```bash
cd /Users/netcom/Desktop/portfolio
git init
git add .
git commit -m "Add portfolio site for GitHub Pages"
git branch -M main
git remote add origin https://github.com/mujthabakk/portfolio.git
git push -u origin main
```

Replace `mujthabakk/portfolio` with your GitHub username and repo name if different.

### 3. Enable GitHub Pages

1. Open your repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment** → **Source**, choose **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Click **Save**

After 1–2 minutes, visit **https://YOUR_USERNAME.github.io/portfolio/**

### Custom domain (optional)

To use `mujthabakk.dev`:

1. Add a file named `CNAME` in the repo root containing: `mujthabakk.dev`
2. In GitHub Pages settings, set the custom domain
3. Add DNS records at your domain provider (GitHub shows the required A/CNAME records)
