# Homelab Rclone — GitHub Pages site

This public repository contains only the informational website and privacy policy for a personal rclone + Google Drive backup utility. Do not add homelab configuration, logs, backup files, OAuth credentials, tokens, or private data.

## Before publishing

1. Replace `REPLACE_WITH_CONTACT_EMAIL` in `privacy.html` with the same support email entered in Google Auth Platform.
2. In repository Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
3. Wait until GitHub Pages publishes the site. The temporary URL will be `https://ToralionPL.github.io/homelab-rclone-site/`.
4. Add the chosen custom domain in Settings → Pages and follow the exact DNS instructions shown by GitHub. Do not change other DNS records.
5. Verify the custom domain in GitHub and Google Search Console before entering it as an Authorized Domain in Google Auth Platform.

## Pages

- Home: `/`
- Privacy policy: `/privacy.html`

The text describes the intended setup: rclone runs on the owner's server, backup archives are transferred directly to the owner's Google Drive, and this website does not receive backup contents or OAuth tokens. Review the text if the implementation changes.