# Goblin Tax: Rage Run — release kit v0.4

## What this is
A static HTML5 browser-game release candidate. It can be hosted on a static HTTPS host and is designed for touch and keyboard controls. It is **not yet a signed Android app**, and it does not take real payments or serve ads.

## Test locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. Basic gameplay works as a local file; install/offline features require HTTPS hosting.
3. Test on a real Android phone: start a run, jump, panic slam, collide, restart, buy coin upgrades, refresh, and check that progress persists.
4. Test daily challenge around local midnight and test Share Score on your phone.

## Free browser publishing (suggested route)
1. Create a GitHub account if needed and a public repository named `goblin-tax-rage`.
2. Upload the contents of this folder to the repository root (the `index.html`, `manifest.json`, `sw.js`, this README, and privacy policy).
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site. Use the exact HTTPS URL shown in Pages settings; do not guess the URL.
5. Test the published URL on mobile. For public launch, publish a real contact email and a privacy policy page, and ensure the host provides HTTPS.

You can also use another static HTTPS host. Keep all three app files together in the same directory.

## Android / Google Play route
This HTML project must be wrapped in an Android project (for example, using Capacitor), tested on devices, and built as a signed Android App Bundle (`.aab`) before Play Console upload. This ZIP does not contain that signed bundle. Play Console currently lists a US$25 one-time developer registration fee; new personal accounts also have testing requirements before production access. See official links below.

## Monetisation status
- Current shop and rewarded-ad button are **demo only**.
- No payment provider, Google Play Billing, AdMob SDK, ad units, or backend is connected.
- Do not advertise demo buttons as real paid features and do not charge users for them.
- For Android digital goods, use Google Play Billing where required. For ads, create and verify an AdMob app after a public supported-store listing and comply with consent/privacy requirements. Never click your own live ads; use test ads during development.
- Start with an optional cosmetic purchase and a clearly labelled rewarded ad; avoid pay-to-win or misleading purchase flows.

## Store listing draft
**App name:** Goblin Tax: Rage Run

**Short description:** Dodge tax bills, collect coins, and survive the goblin's terrible day.

**Full description:**
The tax office has found you. Run, jump, dodge flying paperwork, collect coins, and see how long you can survive in this silly little rage runner. Upgrade your questionable boots, grab a debt helmet, and try the daily tax audit. Easy to learn, very easy to mess up.

Features:
- Quick endless-runner rounds
- Touch and keyboard controls
- Coins and local upgrades
- Daily score challenge
- Shareable score results

This release is a free prototype. Store listing, screenshots, app icon, privacy disclosures, age/content rating, data safety answers, and final Android testing must be completed before submission. Do not claim features that are not in the published build.

## Pre-launch checklist
- [ ] Replace the privacy policy contact placeholder with a monitored email.
- [ ] Confirm game name and check trademark/store-name conflicts.
- [ ] Test on at least one real Android phone and multiple screen sizes.
- [ ] Check no gameplay buttons are blocked by browser UI.
- [ ] Verify local saves and clear-data reset behaviour.
- [ ] Publish the privacy policy at a stable public URL.
- [ ] Create original store screenshots and an app icon.
- [ ] Complete Play Console identity, app content, target audience, data safety, and content rating forms accurately.
- [ ] If using a new personal Play developer account, recruit testers and meet the required closed-test period before applying for production access.
- [ ] Add real monetisation only after platform approval and policy checks.

## Official references
- Play Console registration: https://support.google.com/googleplay/android-developer/answer/6112435
- Personal-account testing: https://support.google.com/googleplay/android-developer/answer/14151465
- AdMob app readiness: https://support.google.com/admob/answer/10564477
- Play service fees: https://support.google.com/googleplay/android-developer/answer/11131145
