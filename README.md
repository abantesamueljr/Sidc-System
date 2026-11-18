# SIDC Cooperative System (GitHub Pages demo)

Static, browser-only version. **Data is saved in each person's own browser (localStorage). It is not shared between users or devices and is lost if browser data is cleared.**

## Publish on GitHub Pages
1. Create a GitHub account, then **New repository** (name e.g. `sidc-system`).
2. **Add file → Upload files**, drag in `index.html`, `.nojekyll` and `README.md`, then **Commit**.
3. Repository **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
4. Wait about 1–2 minutes. The site appears at `https://<your-username>.github.io/sidc-system/`.

## Read before use
- **Public repo = public source code.** The demo login (`admin` / `sidc2026`) is visible to anyone who views the page source, so it is **not real security**. Free Pages normally needs a public repo; private-repo Pages needs a paid GitHub plan (check GitHub's current pricing).
- **Do not enter real member data or real money records** here.
- It cannot support multiple staff sharing one ledger. For that you need a real backend (the Laravel package) or a hosted database service.
- No backups: use browser export/print for records until a backend is added.
