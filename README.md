# CL3 GitHub Blog Starter

This starter is for a GitHub Pages + Jekyll blog.

## Quick start
1. Create a new GitHub repository.
   - Personal site: `YOUR_USERNAME.github.io`
   - Project site: any repo name, e.g. `cl3-blog`
2. Upload all files from this folder to the repo root.
3. In GitHub:
   - Go to **Settings → Pages**
   - Set **Build and deployment** to **GitHub Actions**
4. Push to `main`.
5. Wait for the Pages workflow to finish.

## Edit these placeholders first
- `_config.yml`
  - `title`
  - `description`
  - `url`
  - `baseurl`
  - `author`
- `about.md`
- `index.md`
- `_posts/2026-03-14-cl3-weekly-devlog.md`

## URL rules
- If repo name is `YOUR_USERNAME.github.io`
  - `url: https://YOUR_USERNAME.github.io`
  - `baseurl: ""`
- If repo name is `cl3-blog`
  - `url: https://YOUR_USERNAME.github.io`
  - `baseurl: "/cl3-blog"`
