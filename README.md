# Just Us landing page

Minimal one-page landing page for the Just Us iOS app.

Production: `https://just-us-landing-seven.vercel.app`

## Run locally

```sh
npm install
npm run dev
```

## Download URL and badge

The App Store badge uses the `DOWNLOAD_URL` constant near the bottom of `index.html`.
Replace the placeholder App Store URL with the real App Store or TestFlight URL when it is available.

The page uses Apple's hosted "Download on the App Store" badge artwork rather than a custom button.

## Partner invite links

Partner shares use `https://just-us-landing-seven.vercel.app/join?code=ABC123`. The Apple association file in `public/.well-known/` opens installed builds directly in Just Us. The `/join` fallback keeps the invite code visible and offers a custom-scheme button when the app needs to be opened manually.
