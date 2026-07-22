# Bearded Eye Privacy Site

A static, mobile-friendly privacy site for iOS and Android app-store listings, covering
multiple Bearded Eye games.

## Files

- `index.html` — landing page, links to each game's privacy pages
- `privacy/index.html` — Baams Away Privacy Policy
- `privacy-choices/index.html` — Baams Away User Privacy Choices
- `iguaninja-and-pals/index.html` — Iguaninja and Pals landing page
- `iguaninja-and-pals/privacy/index.html` — Iguaninja and Pals Privacy Policy
- `iguaninja-and-pals/privacy-choices/index.html` — Iguaninja and Pals User Privacy Choices
- `styles.css` — shared styling

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `baams-away-privacy`.
2. Upload all files and folders from this package to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide a URL similar to:

   `https://YOUR-USERNAME.github.io/baams-away-privacy/`

Your final App Store URLs will be:

- Baams Away Privacy Policy: `https://YOUR-USERNAME.github.io/baams-away-privacy/privacy/`
- Baams Away Privacy Choices: `https://YOUR-USERNAME.github.io/baams-away-privacy/privacy-choices/`
- Iguaninja and Pals Privacy Policy: `https://YOUR-USERNAME.github.io/baams-away-privacy/iguaninja-and-pals/privacy/`
- Iguaninja and Pals Privacy Choices: `https://YOUR-USERNAME.github.io/baams-away-privacy/iguaninja-and-pals/privacy-choices/`

## Before publishing

Review the policy whenever you add analytics, ads, accounts, cloud saves, multiplayer,
voice chat, location services, or other third-party SDKs. The policy must match the app's
actual behavior and your App Store / Google Play privacy disclosures.

Iguaninja and Pals' policy is written generically for "third-party advertising networks"
since the specific ad SDK isn't finalized yet. Once you integrate one (e.g. AdMob, Unity
Ads, ironSource), update the Advertising section to name the network(s) and confirm the
ATT / Google Play Data Safety disclosures in App Store Connect and the Play Console match.
