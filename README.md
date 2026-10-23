# pontusnyman.se

Personal site for Pontus Nyman, an Apple platforms developer. It's plain static HTML/CSS with no build step.

- `index.html`: landing page (hero, apps, about, contact)
- `privacy.html`: privacy policy (use as the **Privacy Policy URL** in App Store Connect)
- `support.html`: support page (use as the **Support URL** in App Store Connect)

## Run locally

    python3 -m http.server 8000

## Adding a published app

In `index.html`, copy an `<article class="app-card">`, put an `<img>` of the app icon inside `.app-icon`,
and replace the "Coming soon" badge with:

    <a class="badge badge-live" href="https://apps.apple.com/app/idXXXXXXXXX">View on the App Store</a>
# MinHemsida
