# ASeek & Transio GitHub Pages

Static site served from the `main` branch at <https://cnwxzhaoyang.github.io/>.

| Product | English | 中文 | Support | Privacy |
| --- | --- | --- | --- | --- |
| ASeek | `/ASeek/` | `/ASeek/zh/` | `/ASeek/support/` | `/ASeek/privacy/` |
| Transio | `/Transio/` | `/Transio/zh/` | `/Transio/support/` | `/Transio/privacy/` |

Each product also has `/zh/support/` and `/zh/privacy/` pages. The root `/` and `/zh/` are product hubs. Existing ASeek `/support/`, `/privacy/`, `/zh/support/`, and `/zh/privacy/` pages remain available for App Store metadata and external bookmarks; do not remove them without coordinating the store links.

## Transio App Store fields

- Support URL: `https://cnwxzhaoyang.github.io/Transio/support/`
- Privacy Policy URL: `https://cnwxzhaoyang.github.io/Transio/privacy/`
- In-app build environment: export `VITE_SUPPORT_URL` and `VITE_PRIVACY_POLICY_URL` with those same values before running the Transio App Store build script.

## Publishing

GitHub Pages is configured for this repository's `main` branch. Review local changes, commit, and push to `origin/main`; then verify the public URLs without signing in. The site is plain HTML/CSS and requires no build step.

The Transio privacy page describes local configuration, user-selected servers, failure logs, and voluntary support email. Recheck the text whenever the shipping application's data flow, payment implementation, or support process changes.
