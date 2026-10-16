# Gard PPC Analytics — Public website

Static public information site for the Google Cloud OAuth branding of the internal Gard PPC Analytics tool.

**Intended GitHub repository:** `ppcbiforcebynotification/ppcbiforcebynotification.github.io` (public)

**Published homepage:** https://ppcbiforcebynotification.github.io/

**Privacy policy:** https://ppcbiforcebynotification.github.io/privacy.html

This repository must contain **public information only**. Do not add production application code, access tokens, client/CRM records, cloud keys, logs, private URLs or Google Ads credentials.

Publishing:
1. Create the public repository with the exact name `ppcbiforcebynotification.github.io` under `ppcbiforcebynotification`.
2. Add `index.html`, `privacy.html`, `style.css` and `.nojekyll` in the root of its `main` branch.
3. In **Settings → Pages** set **Deploy from a branch → main → / (root)** and save.
4. Confirm that both website pages load over HTTPS.
5. Review the privacy policy for correctness before using the published URL in OAuth Branding. In Search Console, request URL-prefix site verification for `https://ppcbiforcebynotification.github.io/` and use the verification file or HTML meta tag it provides. Do not invent a verification token.
6. Test whether Google Auth Platform accepts `github.io` as an Authorized Domain. It may refuse a shared-host domain even when the page is verified in Search Console. If rejected, use the same static site with a separately controlled custom domain.

Publishing here does not itself prove domain ownership, successful OAuth brand verification, or Google Ads API Basic Access.
