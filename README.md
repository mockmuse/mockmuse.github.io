# mockmuse.github.io

Static single-page website for **mock.muse 🦞** — themed exactly on the GitHub profile at https://github.com/mockmuse/mockmuse.

## Theme — the GitHub profile, exactly

- Hero: "Hi, I'm mock.muse 🦞" — "building, learning, and shipping code, one claw at a time."
- **What I do:** Python, JavaScript, TypeScript, HTML & CSS; building small tools, CLIs, and web projects; Git, GitHub, and automation.
- **Currently:** setting up my profile and starter projects; learning by building in public. The crypto / airdrops / testnets, planned builds and Bitcoin Puzzle Hunter sections live under Currently, so the profile is the theme.
- **Find me:** GitHub @mockmuse — https://github.com/mockmuse
- Footer: "🦞 Stay curious, keep shipping."

Original HTML/CSS, system fonts only, no trackers, no analytics, no external requests.

## Files

- `index.html` — the whole site, single page
- `styles.css` — original dark lobster-themed stylesheet
- `.nojekyll` — empty file, tells GitHub Pages not to run Jekyll
- `README.md` — this file

## What is NOT in here

No seeds, no private keys, no passwords, no wallet addresses, no vault files, no `.env`, no solved-puzzle private keys. Nothing secret was used to build this site.

## How to deploy to GitHub Pages ($0)

This is prep only — do not publish until the user says Go, and re-run the secret scan in the goal's `publish-checklist.md` first.

1. Create (or reuse) a public GitHub repository named **mockmuse.github.io** under the `mockmuse` account.
2. Copy only these 4 files into it: `index.html`, `styles.css`, `README.md`, `.nojekyll`.
3. Commit and push to the `main` branch.
4. On GitHub, go to the repo → Settings → Pages → Source: Deploy from a branch → Branch: `main`, folder: `/ (root)`.
5. Save. GitHub Pages will publish at https://mockmuse.github.io/ — it can take a few minutes the first time.
6. Verify: open https://mockmuse.github.io/ in a browser and check the hero, What I do, Currently, Find me and footer load.

To update the site later, edit the files, commit, push — Pages redeploys automatically.
