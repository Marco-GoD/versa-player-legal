# Versa Player Legal

Public legal site for Versa Player.

## Public routes

- `/` — Legal landing page
- `/privacy/es.html` — Privacy Policy (Spanish)
- `/privacy/en.html` — Privacy Policy (English)
- `/terms/es.html` — Terms of Use (Spanish)
- `/terms/en.html` — Terms of Use (English)
- `/third-party/index.html` — Third-party services (Spanish)
- `/third-party/en.html` — Third-party services (English)

## GitHub Pages

Publish from:

- Branch: `main`
- Folder: `/(root)`

Expected public base URL:

`https://marco-god.github.io/versa-player-legal/`

In GitHub open **Settings → Pages → Build and deployment → Deploy from a branch**, choose **main** and **/(root)**, then save.

## Current status

The legal pages reflect the current Versa Player model:

- local-first media processing;
- manual/local lyrics and artwork;
- assisted web search without automatic scraping;
- Google Play Billing for Versa Premium;
- Google Mobile Ads / UMP for the free edition where applicable;
- internet radio;
- Android/device voice services;
- no first-party account system or first-party analytics platform.

## Required before Google Play production

1. Publish a dedicated support/privacy email and place it in:
   - Privacy Policy ES/EN;
   - Terms ES/EN where appropriate;
   - Google Play developer/contact fields.
2. Confirm that the public developer identity matches the identity used for Google Play distribution.
3. Review the policy against the final production configuration of AdMob, UMP and Billing.
4. Complete Google Play Data Safety and other declarations using the final release build.
5. Keep these pages synchronized with future changes to data flows or third-party services.

GitHub Issues is a **public** support channel. Users should not be asked to publish sensitive personal information there.

## Re-review required if Versa Player later adds

- remote licensed lyrics/artwork providers;
- analytics or crash-reporting services;
- Versa accounts or cloud sync;
- a backend receiving user data;
- new advertising or payment providers;
- materially different permissions or data uses.

## Security

Do not commit API keys, signing keys, passwords, AdMob secrets, Play credentials or other private material to this public repository.
