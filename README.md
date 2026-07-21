# quiet-harbor-8f3a

Single-file dashboard for Joanna's leave. Data lives in Supabase (project life-os); this page is just the face. The obscure repo name is intentional — it keeps the URL effectively private on a free public repo.

## Publish on GitHub Pages (one time, ~3 min)

1. Go to github.com/new → repo name **`quiet-harbor-8f3a`** → Public → Create.
2. On the new repo page: click **"uploading an existing file"** → drag `index.html` (and this README) → Commit.
3. Repo → **Settings → Pages** → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Wait ~1 minute. Dashboard is live at: `https://<your-username>.github.io/quiet-harbor-8f3a/`
5. On your phone: open that URL in Safari → Share → Add to Home Screen.

## Terminal alternative

From this folder:
```
git init && git add -A && git commit -m "dashboard"
gh repo create quiet-harbor-8f3a --public --source=. --push
```
Then do step 3 above to enable Pages.

## Updating later

Replace `index.html` with a new version. Data changes never require this — only design/feature changes do.
