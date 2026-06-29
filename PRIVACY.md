# VitalsOS Privacy Policy

*Last updated: June 29, 2026*

VitalsOS ("the app") is a personal habit and mission tracker with gamification. This policy describes what data the app handles and how it is used.

**Developer:** Mizu Lab (see [SUPPORT.md](./SUPPORT.md) for contact).

## Summary

- **We do not sell your data** or use it for advertising.
- **We do not use third-party analytics or advertising trackers.**
- **Habit and game progress** is stored on your device. If you choose **Sign in with Apple** and **iCloud**, progress can sync to your **private** iCloud database (CloudKit) — we do not run our own habit-data servers.
- **VitalsOS Pro** subscriptions are billed by **Apple**; we use **RevenueCat** only to check whether your subscription or trial is active.
- **Not medical advice.** In-app "vitals" and traits are fictional game stats, not health or medical data from HealthKit or clinical sources.

## Minimum age

VitalsOS is rated **16+** on the App Store. The app is **not directed at children under 16**. We do not knowingly collect personal information from anyone under 16. If you believe a child under 16 has provided data through the app, contact us (see [SUPPORT.md](./SUPPORT.md)) and we will work with Apple to address it.

## Data the app handles

This section matches our [App Store privacy label](https://apps.apple.com). We collect the following **only to provide app functionality**, not for tracking across other companies’ apps or websites.

| Data type | Examples | When | Linked to you? |
|-----------|----------|------|----------------|
| **Name** | Display name you enter in onboarding; optional name from Sign in with Apple (first sign-in only) | Always on device; synced if iCloud is on | Yes, when you sign in |
| **Photos** | Profile avatar you pick; share images you save to Photos | Only if you use those features | Yes, when synced via iCloud |
| **Other user content** | Mission and habit logs, XP, levels, traits, game vitals, stats, titles, reminders settings, quit-challenge progress | Always on device; synced if iCloud is on | Yes, when you sign in |
| **User ID** | Sign in with Apple user identifier (stored to link your account and purchases) | Only if you sign in with Apple | Yes |
| **Purchases** | Whether VitalsOS Pro (trial, subscription, or lifetime) is active | When you use the paywall or Restore Purchases | Yes |

We **do not** collect: email or phone (the app does not read or store them), precise location, HealthKit or fitness API data, contacts, browsing history, advertising identifiers, or payment card numbers (Apple handles payment).

## On your device

The app stores data locally on your iPhone or iPad using **SwiftData**, including:

- Mission completions, time/unit logs, and templates you activate
- Character progress (XP, level, traits, in-game vitals, rebirth/capstone state)
- Optional profile photo
- Settings (theme, reminders, equipped titles/effects)
- Habit-break (quit challenge) progress and login-streak rewards

If you **do not** sign in with Apple or enable iCloud for the app, this data remains on that device unless you use an **Apple device backup** (iCloud or computer backup).

## Optional: Sign in with Apple and iCloud sync

You can use VitalsOS without signing in. If you choose **Sign in with Apple** and your device has **iCloud** available, app progress is stored in your **private CloudKit container** (`iCloud.mizulab.VitalsOS`) so the same data can appear on your other devices signed into the same Apple ID.

- Sync is handled by **Apple’s iCloud/CloudKit**; we do not operate separate sync servers.
- We receive a **stable Apple user identifier** to link purchases (via RevenueCat) and your profile — not your Apple ID password.
- Apple may provide your **name once** on first Sign in with Apple if you allow it and your display name is empty.
- You can wipe game progress in **Manage** (optionally including iCloud copies when signed in). Sign-in, theme, reminders, and subscription status are not removed by a progress wipe.

## VitalsOS Pro (subscriptions)

After onboarding, the app requires an active **VitalsOS Pro** entitlement (free trial on the annual plan where eligible, paid subscription, or lifetime purchase).

| Topic | Detail |
|-------|--------|
| **Billing** | **Apple App Store** — we never see your payment card |
| **Plans** | Monthly, yearly (7-day free trial for eligible new subscribers), or one-time lifetime |
| **RevenueCat** | Used on-device to validate entitlement status and restore purchases. See [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/) |
| **Manage / cancel** | iOS **Settings → Apple ID → Subscriptions**, or the link in the app paywall / **Manage → Subscription** |

## Permissions

| Permission | Why | Required? |
|------------|-----|-----------|
| **Photos (read)** | Choose a profile photo on the Character tab | No |
| **Photos (add)** | Save Character or Stats share images to your library | No |
| **Notifications** | Local reminders you set in **Manage → Reminders** | No |

Denying Photos or Notifications does not block subscription or basic app use after you have access; reminders and custom avatar simply won’t work.

## Third-party services

| Service | Role | Privacy |
|---------|------|---------|
| **Apple** (App Store, Sign in with Apple, iCloud, CloudKit) | Payments, identity, optional sync | [Apple Privacy](https://www.apple.com/legal/privacy/) |
| **RevenueCat** | Subscription status and restore | [RevenueCat Privacy](https://www.revenuecat.com/privacy/) |

We do not embed social networks, ad networks, or crash/analytics SDKs in the current version.

## EU Digital Services Act (trader information)

If you download VitalsOS from an App Store in the **European Union**, Apple may display **trader contact details** (address, phone, email) that we provided for legal compliance. That information is shown on the product page for EU users and is separate from in-app habit data.

## Security and retention

- Data in iCloud uses Apple’s encryption and access controls for your Apple ID.
- We retain habit data only as long as you keep it in the app or your iCloud account; you can delete progress from the app.
- If you delete the app without wiping progress, local data is removed with the app; iCloud data may remain until you delete it or wipe progress while signed in.

## Your choices

- Use the app without Sign in with Apple (single-device, local data).
- Deny optional permissions (Photos, Notifications).
- Cancel subscriptions in Apple’s subscription settings.
- Request help or privacy questions via [SUPPORT.md](./SUPPORT.md).

## Changes

We may update this policy. The **last updated** date at the top will change; the current version is always in this repository.

## Contact

See [SUPPORT.md](./SUPPORT.md).
