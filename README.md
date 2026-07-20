# Racheal A. — Igbo Language Tutor Portfolio

A single-page portfolio site built to showcase Igbo language tutoring experience: bio, teaching approach, student testimonials, and rating history (4.6 → 4.9).

## What's in this repo

- `index.html` — the entire site (HTML, CSS, and JS in one file, no build step required)

## Before you publish: 2 things to edit

Open `index.html`, search for these two lines near the bottom (in the `<footer>` section), and swap in your real links:

```html
<a class="btn btn-primary" href="https://learn.lingawa.com" target="_blank" rel="noopener">Book a lesson on Lingawa</a>
<a class="btn btn-secondary" href="mailto:youremail@example.com">Email me</a>
```

Replace `https://learn.lingawa.com` with your actual Lingawa tutor profile URL, and `youremail@example.com` with your real email address.

## How to publish this on GitHub Pages (free hosting)

### 1. Create the repository
1. Go to [github.com](https://github.com) and log in (or create a free account).
2. Click the **+** icon top-right → **New repository**.
3. Name it `yourusername.github.io` — replacing `yourusername` with your actual GitHub username, exactly. This special name gives you a live site at `https://yourusername.github.io` automatically.
   - Alternative: you can name it anything (e.g. `igbo-tutor-portfolio`) — it'll just live at `https://yourusername.github.io/igbo-tutor-portfolio` instead.
4. Set it to **Public**.
5. Check **Add a README file** (or skip if uploading this one).
6. Click **Create repository**.

### 2. Upload the file
1. On your new repo's page, click **Add file → Upload files**.
2. Drag in `index.html` from this folder (and `README.md` if you want it in the repo).
3. Scroll down, add a commit message like "Add portfolio site", and click **Commit changes**.

### 3. Turn on GitHub Pages
1. In your repo, go to **Settings** (top tab bar).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment → Source**, select **Deploy from a branch**.
4. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
5. Wait 1–2 minutes. Refresh the Pages settings screen — you'll see a green banner with your live URL:
   - `https://yourusername.github.io` (if you used the special repo name), or
   - `https://yourusername.github.io/igbo-tutor-portfolio` (if you used a custom name)

### 4. Use it in your application
Copy that URL and paste it wherever the application asks for a portfolio link.

## Making future edits

Any time you want to update testimonials, stats, or copy:
1. Go to the repo on GitHub, click on `index.html`.
2. Click the pencil (✏️) icon to edit directly in the browser.
3. Make your changes, scroll down, and click **Commit changes**.
4. The live site updates automatically within a minute — no extra steps needed.

## Notes

- No installation, build tools, or Node/npm required — this is a static HTML file.
- Works on GitHub Pages exactly as-is.
- If you'd rather add more testimonials later, copy one `<div class="t-card">...</div>` block in the Reviews section and edit the quote, name, and star count.
