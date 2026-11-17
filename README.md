# Pixel Lite Technology website

A responsive, static business website for Pixel Lite Technology, built with plain HTML, CSS and a custom SVG logo. It has no paid themes, frameworks or build step.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Publish free with Google Firebase Hosting

Firebase Hosting is Google's static website hosting service. Its Spark plan has a no-cost allowance; Google may change plan limits, so check the current Firebase pricing page before publishing. A Google account and a Firebase project are needed. This repository does not include credentials or a Firebase project ID, so the owner must complete deployment from their own account.

1. Create a Firebase project at https://console.firebase.google.com/ and enable **Hosting**. No billing account is needed for the Spark plan.
2. Install the Firebase CLI: `npm install -g firebase-tools`
3. From this repository folder, sign in: `firebase login`
4. Connect this folder to your Firebase project: `firebase use --add` (select the project you created).
5. Deploy: `firebase deploy --only hosting`
6. Firebase will provide a public `web.app` URL. Add a custom domain later if desired; domain registration may cost money.

The `firebase.json` file configures this repository root as the static site directory.

## Business details on the site

- Phone: +91 63643 13258
- Email: pixellitetechnology@gmail.com
- Address: 81/1 Yellappa Garden, 3rd Cross, Banagirinagar, Banashankari 3rd Stage, Bengaluru – 560085

Check the contact details and service descriptions before publishing. The website intentionally describes services generally and does not promise specific repair capabilities or product stock.
