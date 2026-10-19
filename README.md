# Tejasvi Vasant Hegde — Portfolio

Static site: `index.html` + `resume.pdf`. No build step.

## Deploy on Vercel
**Option A — GitHub (recommended, auto-redeploys on every push)**
1. Create a new GitHub repo (e.g. `portfolio`) and upload these files to it.
2. Go to vercel.com → Add New → Project → import the repo.
3. Framework preset: **Other**. Leave build command and output directory empty. Click Deploy.

**Option B — CLI**
```
npm i -g vercel
cd portfolio
vercel --prod
```

## Editing
- Links (LinkedIn, GitHub, project repos): the `LINKS` object at the top of the `<script>` in `index.html`.
- Résumé: replace `resume.pdf` with a file of the same name.
- Colours: the `:root` variables at the top of the `<style>` block.
