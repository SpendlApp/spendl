# Spendl Website

Single-page site for App Store Connect (Support URL, Privacy Policy URL, Marketing URL).

## Before publishing

1. **Review** the Privacy Policy and Terms for accuracy.

## Preview locally

Open `index.html` in a browser, or run:

```bash
cd website
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deploy (GitHub Pages)

1. Push the `website/` folder to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to deploy from the `/website` folder (or move `index.html` to repo root)
4. Your URL will be `https://<username>.github.io/<repo>/`

Use that URL in App Store Connect for:
- **Privacy Policy URL**
- **Support URL**
- **Marketing URL** (optional)

## App Store Connect URLs

Once hosted, use the same base URL for all three fields, or link directly to sections:

| Field | URL |
|-------|-----|
| Privacy Policy | `https://yoursite.com/#privacy` |
| Support | `https://yoursite.com/#contact` |
| Marketing | `https://yoursite.com/` |
