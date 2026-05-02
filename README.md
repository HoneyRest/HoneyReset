# Honey Reset

**Honey Reset** is a private, single-page companion for life transitions—gentle structure and reflection with **no backend, no login, and no database**.

## Contents of this folder

| File | Purpose |
|------|---------|
| `index.html` | The full app. |
| `honey-icon.png` | Bookmark / home-screen icon. |
| `buyer-setup-guide.md` | Setup, privacy, backup, troubleshooting. |

## Static hosting (GitHub Pages)

1. Create a **new GitHub repository** for Honey Reset.
2. Upload **all files** from this folder to the **repository root**.
3. **Settings → Pages → Deploy from a branch** → branch **main**, folder **`/ (root)`**.
4. Use the published URL (for example `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`).

### Local preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/`.

## Privacy & data

This is a **private web app. No login, no subscription.** Your entries save **locally in your browser** on the device you use.

**If you clear browser data or switch devices, export a backup first.**

## Icon

Replace **honey-icon.png** with your own square PNG (512×512 or larger recommended). Keep the filename or update the `<link>` tags in **index.html**.
