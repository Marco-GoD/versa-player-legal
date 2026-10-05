# Versa Player Legal

Public legal site for Versa Player.

## Public routes

- `/` — Legal landing page
- `/privacy/` — Privacy Policy (Spanish)
- `/privacy/en.html` — Privacy Policy (English)
- `/terms/` — Terms of Use (Spanish)
- `/terms/en.html` — Terms of Use (English)
- `/third-party/` — Third-party services (Spanish)
- `/third-party/en.html` — Third-party services (English)

## Publish with GitHub Pages

In the repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**.
4. Save and wait for the Pages deployment.
5. Verify the public URLs before putting them into Versa Player or Google Play Console.

Expected base URL with the current repository name:

`https://marco-god.github.io/versa-player-legal/`

## Before Google Play production

- Prefer replacing the GitHub Issues contact with a dedicated public support/privacy email.
- Confirm that the public developer identity matches the identity used for Google Play distribution.
- Review the policy after the final AdMob/UMP/Billing production configuration is known.
- Keep the public policy consistent with the actual release build and Data Safety answers.
- Re-review if remote lyrics/artwork providers, analytics, accounts, cloud sync, or other data flows are added.

## Security

Do not commit API keys, signing keys, passwords, AdMob secrets, Play credentials or other private material to this public repository.
