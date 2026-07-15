# Fatima Naeem — Portfolio

A single-page, no-build static site. Deploy in under 2 minutes.

## Deploy to Vercel (easiest — no account setup beyond signing in)
1. Go to https://vercel.com/new
2. Choose "Deploy" > drag-and-drop this whole `fatima-portfolio` folder onto the page
   (or click "Browse" and select the folder)
3. Vercel auto-detects it as a static site — click **Deploy**
4. You'll get a live URL like `fatima-naeem.vercel.app` in ~30 seconds

## Alternative: Vercel CLI
```
npm i -g vercel
cd fatima-portfolio
vercel
```
Follow the prompts (press Enter to accept defaults) and it will give you a live link.

## Alternative: GitHub + Vercel (best if you want a custom domain later)
1. Create a new GitHub repo, push this folder's contents to it
2. On vercel.com, "Add New Project" → import that repo → Deploy

## Editing
- All content lives in `index.html` (structure + copy), styles are in the `<style>` block, and the reel cards / ticker text are generated in the `<script>` block near the bottom.
- To swap your photo, replace `assets/fatima.jpeg` (keep the same filename, or update the `src` in the `.hero-photo img` tag).
- To point reel cards at different links, edit the `reels` array in the script.
