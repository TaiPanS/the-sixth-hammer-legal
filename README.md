# Marble Run — Legal Pages

Static legal pages for the Android game **Marble Run** by **The Sixth Hammer**
(published by Voodoo). Built as plain, mobile-responsive HTML so they can be
hosted for free and linked from the Google Play Store listing and from
within the game.

## Pages

| File                     | Purpose                                  |
| ------------------------ | ---------------------------------------- |
| `index.html`             | Landing page linking to all legal pages  |
| `privacy-policy.html`    | Privacy Policy                           |
| `terms-of-service.html`  | Terms of Service                         |
| `data-deletion.html`     | Data deletion request instructions       |
| `style.css`              | Shared styles for every page             |

Contact for all pages: **contact@thesixthhammer.com**

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute, the pages are live at:
   - `https://<user>.github.io/<repo>/`
   - `https://<user>.github.io/<repo>/privacy-policy.html`
   - `https://<user>.github.io/<repo>/terms-of-service.html`
   - `https://<user>.github.io/<repo>/data-deletion.html`

Use these URLs in the Google Play Console (Privacy Policy field and the Data
safety form) and inside the game.

## Notes

- The "Effective date" on each page is set to **25 June 2026**. Update it
  whenever you change the content.
- The third-party advertising/analytics partners listed in the Privacy Policy
  (Voodoo, Google, AppLovin, Unity/ironSource) are typical of Voodoo's
  mediation stack. Confirm the actual SDKs shipped in the build and adjust the
  list if needed.
- The Terms of Service "Governing law" clause is written generically. If The
  Sixth Hammer wants to name a specific country/state, edit section 13 of
  `terms-of-service.html`.
