# Deploy coronagards.com (GitHub Pages)

1) Create a new GitHub repo (any name) and upload all files from this zip to the repo root.
2) In repo **Settings → Pages**, choose Source: **Deploy from a branch**, Branch: **main** (or default), Folder: **/**. Save.
3) Confirm the site publishes (temporary *.github.io preview will appear).
4) In **Settings → Pages**, set **Custom domain** to `coronagards.com`. The included **CNAME** file helps.
5) Update DNS at GoDaddy to point your domain to GitHub Pages (see below).

## GoDaddy DNS for GitHub Pages
- A (apex @): 185.199.108.153
- A (apex @): 185.199.109.153
- A (apex @): 185.199.110.153
- A (apex @): 185.199.111.153
- CNAME (www): your **GitHub username** + `.github.io` (e.g., `dean.github.io`)

After DNS propagates (usually minutes), visit: https://coronagards.com/

