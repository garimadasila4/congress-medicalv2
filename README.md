# Congress Design — Research Intelligence

Static app for congress abstracts and research intelligence (dark/light theme, responsive).

## Design files

- **Root:** `index.html`, `congress-design-luxury.html` — main site (oneLabel colors, no gradients).
- **congress-medicalv2/:** Design variant with `congress-design-luxury.html`, `theme-colors.css`, and `index.html` (external theme file).

## Run locally

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy to GitHub and make the site live

### 1. Create a new repository on GitHub

- Go to [github.com/new](https://github.com/new).
- **Repository name:** e.g. `congress-design` (or any name you like).
- Set visibility to **Public**.
- Do **not** add a README, .gitignore, or license (this repo already has them).
- Click **Create repository**.

### 2. Add remote and push

From the project root (replace `YOUR_USERNAME` and `REPO_NAME` with your GitHub username and repo name):

```bash
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git push -u origin main
```

If prompted for credentials, use a [Personal Access Token](https://github.com/settings/tokens) (GitHub no longer accepts account passwords for HTTPS).

### 3. Turn on GitHub Pages (GitHub Actions)

- In your repo on GitHub go to **Settings → Pages**.
- Under **Build and deployment**:
  - **Source:** **GitHub Actions**
- Save. No need to pick a branch.

The first push to `main` (or a manual run of the “Deploy to GitHub Pages” workflow) will deploy the site. After it finishes, the site will be at:

**https://YOUR_USERNAME.github.io/REPO_NAME/**

Later pushes to `main` will redeploy automatically.
