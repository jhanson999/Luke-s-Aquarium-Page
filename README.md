# Luke’s Aquarium — GitHub Pages website

This is a ready-to-upload **static website** for Luke’s Aquarium, an animated freshwater aquarium screensaver for Roku.

## IMPORTANT — do this before publishing

1. **Replace every instance of `SUPPORT_EMAIL_HERE`** in `index.html`, `privacy-policy.html`, and `terms-of-use.html` with an email address or a public support contact you control. It appears in visible text and in `mailto:` links. An email address is recommended for privacy requests. Avoid putting private contact information online unless you intend it to be public.
2. **Read and approve the legal language**, and update it if your app changes. It was drafted from a review of the Build 201 Roku source files, which did not include network calls, login features, analytics, or advertising. The draft is not legal advice.
3. Keep your statements accurate: if later versions of the screensaver add accounts, network services, ads, telemetry, purchases, etc., revise the policy and terms before publishing the update.
4. The website is informational only. Do not upload your Roku source, unsigned app builds, developer keys, private information, or signing credentials to this public Pages repository.

## Publish using GitHub Pages (free with a public repository)

1. Sign in to https://github.com and create a **public** repository named `lukes-aquarium` (or any name you choose).
2. Unzip the download and **upload the files and the `assets/` folder** to the repository root. `index.html` should be directly in the root—not inside an extra containing folder. (A ZIP uploaded as a single file will not automatically publish as a site.)
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then click **Save**.
5. Once GitHub Pages finishes publishing, visit the URLs below, replacing `YOUR_GITHUB_USERNAME` with your GitHub user or organization name. If you used a different repository name, change `lukes-aquarium` accordingly.

## URLs for the Roku Developer Dashboard

**Privacy policy URL**
`https://YOUR_GITHUB_USERNAME.github.io/lukes-aquarium/privacy.html`

(Also available at `/privacy-policy.html`.)

**Terms and conditions URL**
`https://YOUR_GITHUB_USERNAME.github.io/lukes-aquarium/terms.html`

(Also available at `/terms-of-use.html`.)

**Learn More URL / product website**
`https://YOUR_GITHUB_USERNAME.github.io/lukes-aquarium/`

The optional alias `/learn-more.html` redirects to the homepage for convenience.

## Files

- `index.html` — Learn More homepage, features, approved diver cover art
- `learn-more.html` — redirect alias for Learn More
- `privacy.html` — privacy policy (also `privacy-policy.html`)
- `terms.html` — terms of use (also `terms-of-use.html`)
- `assets/style.css` — responsive style, shared by all pages (root `style.css` copy also included)
- `assets/lukes-aquarium-cover.jpg` — selected promotional image
- `assets/favicon.png` — small site icon
- `.nojekyll` — tells Pages to serve static files without Jekyll processing

## About privacy claims

The packaged Build 201 screensaver's source (`roku_app/source/main.brs`, `roku_app/components/LivingTankScene.brs`, `roku_app/components/LivingTankScene.xml`) did not contain network transfer, tracking, advertising, or registry-based personal-data collection logic when reviewed on November 16, 2026. That does **not** establish anything about Roku's separate device telemetry or GitHub's web hosting data collection; those third parties have their own policies.

**Legal note:** These documents are templates to review, not a substitute for professional legal advice or Roku's requirements. You are responsible for making sure the final statements reflect your publishing entity, actual services, and applicable laws.
