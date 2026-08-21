# ayomide-agbaje.github.io

One-page personal site: `index.html` plus a `_config.yml` so GitHub Pages treats it as a Jekyll site (this lets you later add pages, a blog, or a theme without restructuring).

## Deploy in 5 minutes

1. Create a new GitHub repo named exactly `<your-username>.github.io` (this naming is what makes GitHub Pages serve it at the root domain instead of a `/repo-name` path).
2. Push these two files (`index.html`, `_config.yml`) to the repo's `main` branch.
3. In the repo, go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
4. Wait 1-2 minutes, then visit `https://<your-username>.github.io`.

## Editing later

- All content lives in `index.html` — edit the text between the `<h2>` sections directly, no build step required for plain HTML.
- To add more pages (e.g. `/writing`, `/cv`), create additional `.html` or `.md` files in the same repo; Jekyll will pick them up automatically because of `_config.yml`.
- To add a custom domain, create a `CNAME` file in the repo root containing just your domain, then point a DNS `A`/`CNAME` record at GitHub's Pages IPs per GitHub's docs.

## What's on the page right now

Ventures (Clisense, HealthDrive, Afresearch Ventures), the peer-reviewed IJISRT paper, Google Scholar/Academia.edu/Muck Rack/Medium, and the personal social links already on file. Update contact email, add a CV download link, or add a photo whenever ready — none of that was invented here, only what's already verified is included.
