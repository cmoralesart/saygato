# SayGato website (GitHub Pages draft)

**This site is not published.** Carlos Morales approved preparing a free GitHub Pages site, and nothing goes live until he has seen a preview and said yes.

Planned public URL, after approval:

`https://cmoralesart.github.io/saygato/`

The site should live in a separate **public** repository named `saygato` under the `cmoralesart` account, so the private `SayGatoApp` code repository stays private.

## What’s here

Static HTML and CSS only. No trackers, no analytics, no external fonts, and no CDNs. Brand colors come from the app theme. The icon is Churro’s face from the app icon.

| Path | Page |
|---|---|
| `index.html` | About (English) |
| `es/index.html` | Acerca de (es-MX) |
| `privacy.html` | Privacy policy (English) |
| `es/privacy.html` | Política de privacidad (es-MX) |
| `support.html` | Support (English) |
| `es/support.html` | Ayuda (es-MX) |
| `404.html` | Simple not-found page |
| `css/styles.css` | Shared styles |
| `img/` | Icon and favicons |
| `.nojekyll` | Lets GitHub Pages serve the site as-is |

Full-page preview screenshots are in `/workspace/saygato-site-preview/` (not part of the site itself).

## Placeholders to replace before going live

Search the site for these exact strings:

- **`DATE_TBD`** — effective date of the privacy policy, on `privacy.html` and `es/privacy.html`.

The contact email is already set to `saygatoapp@gmail.com` on every language page.

Also before going live:

1. Remove the preview banner (the `.preview-banner` bar) from every page.
2. Remove `<meta name="robots" content="noindex, nofollow">` from every page.

## Android backup wording

Carlos decided backup OFF for v8.8 (`android.allowBackup=false`); the privacy and support pages say so. On Android, progress stays on the device and is not copied to a Google account. The pages also keep a neutral line for iPhone and iPad: the owner’s own iCloud or computer backup may include the app’s data, and we can’t see those backups.

## How to publish later (do not do this until Carlos says yes)

1. Create a new public repository named `saygato` under `cmoralesart` (do not put this in the private SayGatoApp repo).
2. Push these files to the default branch, with the site at the repository root.
3. In the repository settings, enable GitHub Pages from that branch, serving from `/` (root). The site will appear at `https://cmoralesart.github.io/saygato/`.
4. Replace the placeholders and remove the preview banner and noindex tags first, or immediately after, so testers never see them.

Links in the pages are relative, so they work both at the site root and under the `/saygato/` path.
