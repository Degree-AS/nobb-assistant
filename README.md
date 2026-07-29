# NOBB Import Assistant

One-off HTML/CSS/JS demo/prototype, generated locally (often with the help of
ChatGPT/Claude) and published as a static site via GitHub Pages.

This repository contains **only this one demo**. Each demo gets its own repo —
copy this same README template into every new one.

## Repository structure

```
nobb-assistant/
├── index.html      <- the demo file (HTML/CSS/JS in one file or split up)
└── README.md
```

GitHub Pages automatically looks for an `index.html` file in the repo root as
the site's entry point — that's why the demo file must be named that.

## How to clone and edit — pick the option that fits you

### Option A — GitHub Desktop (simple app, no command line)

Good if you want a local copy of the files but don't want to use the terminal.

1. Install GitHub Desktop (https://desktop.github.com/) and sign in.
2. **File → Clone repository**, pick `nobb-assistant`, choose a folder on your
   computer.
3. Edit `index.html` locally in your editor / AI tool of choice.
4. Preview locally: just double-click `index.html` to open it in a browser.
5. Back in GitHub Desktop, you'll see the changed file listed. Write a short
   summary, click **"Commit to main"**, then click **"Push origin"**.

### Option B — Edit and commit via an IDE (e.g. VS Code)

1. Install VS Code (https://code.visualstudio.com/) (or another IDE with
   built-in Git support).
2. Clone the repo: **Source Control panel → Clone Repository**, paste
   `https://github.com/Degree-AS/nobb-assistant.git`, pick a folder.
3. Edit `index.html` in the editor (AI tools/extensions can edit it directly
   too).
4. Preview: right-click `index.html` → "Open with Live Server" (requires the
   free "Live Server" extension), or just double-click the file to open it in
   a browser.
5. In the **Source Control panel**: review the changed file, type a short
   commit message, click the checkmark (**Commit**), then click **Sync
   Changes** (or **Push**).

### Option C — Git command line

```bash
git clone https://github.com/Degree-AS/nobb-assistant.git
cd nobb-assistant
```

Edit `index.html` in your editor / AI tool of choice, preview locally.

When changes are made, commit and publish:

```bash
git add .
git commit -m "Short description of the change"
git push
```

Whichever option you use, once changes are pushed to the `main` branch,
GitHub Pages automatically rebuilds the site (usually within ~1 minute, no
extra action needed).

## Where to find the live URL

```
https://degree-as.github.io/nobb-assistant/
```

## GitHub Pages setup (one-time, when creating the repo)

**Settings → Pages → Build and deployment → Source: Deploy from a branch →
Branch: `main`, folder: `/ (root)`**

## Notes

- This repo is for a simple demo/prototype — no CI/CD, PR review, staging
  model, etc.
- If a demo later grows into something bigger, that's the point to consider a
  more elaborate process (Actions, PR previews, etc.) — not before.
