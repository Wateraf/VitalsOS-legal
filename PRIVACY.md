# VitalsOS Privacy Policy

*Last updated: June 26, 2026*

VitalsOS ("the app") is a personal habit and mission tracker with gamification. This policy describes what data the app handles and how it is used.

**Developer:** Mizu Lab (see [SUPPORT.md](./SUPPORT.md) for contact).

## Summary

- **We do not sell your data** or use it for advertising.
- **We do not use third-party analytics or advertising trackers.**
- **Habit and game progress** is stored **on your iPhone only** using SwiftData. We do not run habit-data servers.
- **Backup:** You can export an encrypted backup file from **Manage → Data & Backup** and import it on another device. We do not receive that file.
- **No account required.** There is no Sign in with Apple in the current version.
- **VitalsOS Pro** subscriptions are billed by **Apple**; we use **RevenueCat** only to check whether your subscription or trial is active.
- **Not medical advice.** In-app "vitals" and traits are fictional game stats, not health or medical data from HealthKit or clinical sources.

## Minimum age

VitalsOS is rated **13+** on the App Store. The app is **not directed at children under 13**. We do not knowingly collect personal information from anyone under 13. If you believe a child under 13 has provided data through the app, contact us (see [SUPPORT.md](./SUPPORT.md)) and we will work with Apple to address it.

## Data the app handles

This section matches our [App Store privacy label](https://apps.apple.com). We collect the following **only to provide app functionality**, not for tracking across other companies’ apps or websites.

| Data type | Examples | When | Linked to you? |
|-----------|----------|------|----------------|
| **Name** | Display name you enter in onboarding | Stored on your device | Yes (your profile) |
| **Photos** | Profile avatar you pick; share images you save to Photos | Only if you use those features | Yes (your profile) |
| **Other user content** | Mission and habit logs, XP, levels, traits, game vitals, stats, titles, reminders settings, quit-challenge progress | Always on device | Yes (your profile) |
| **Purchases** | Whether VitalsOS Pro (trial, subscription, or lifetime) is active | When you use the paywall or Restore Purchases | Yes |

We **do not** collect: email or phone (the app does not read or store them), precise location, HealthKit or fitness API data, contacts, browsing history, advertising identifiers, or payment card numbers (Apple handles payment).

## On your device

The app stores data locally on your **iPhone** using **SwiftData**, including:

- Mission completions, time/unit logs, and templates you activate
- Character progress (XP, level, traits, in-game vitals, rebirth/capstone state)
- Optional profile photo
- Settings (theme, reminders, equipped titles/effects)
- Habit-break (quit challenge) progress and login-streak rewards

Progress saves automatically while you play. **Deleting VitalsOS from your iPhone removes this local data** unless you exported a backup first.

## Backup and moving devices

**Manage → Data & Backup** lets you:

- **Export backup** — creates an encrypted `.vitalsbackup` file you can save to Files, AirDrop, or another app you trust
- **Import backup** — restores progress from a file you previously exported

Backup files stay under **your control**. We do not upload them to our servers. Subscription status is **not** included in backups — use **Restore Purchases** after import.

You can wipe all game progress in **Manage → Data & Backup → Delete all saved progress** (subscription and app settings remain).

## VitalsOS Pro (subscriptions)

After onboarding, the app requires an active **VitalsOS Pro** entitlement (free trial on the annual plan where eligible, paid subscription, or lifetime purchase).

| Topic | Detail |
|-------|--------|
| **Billing** | **Apple App Store** — we never see your payment card |
| **Plans** | Monthly, yearly (7-day free trial for eligible new subscribers), or one-time lifetime |
| **RevenueCat** | Used on-device to validate entitlement status and restore purchases. RevenueCat may assign an anonymous app user ID for subscription management. See [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/) |
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
| **Apple** (App Store) | Payments | [Apple Privacy](https://www.apple.com/legal/privacy/) |
| **RevenueCat** | Subscription status and restore | [RevenueCat Privacy](https://www.revenuecat.com/privacy/) |

We do not embed social networks, ad networks, or crash/analytics SDKs in the current version.

## EU Digital Services Act (trader information)

If you download VitalsOS from an App Store in the **European Union**, Apple may display **trader contact details** (address, phone, email) that we provided for legal compliance. That information is shown on the product page for EU users and is separate from in-app habit data.

## Security and retention

- Local data uses iOS app sandbox protections.
- Exported backups are encrypted; keep backup files private like any personal document.
- We retain habit data only as long as you keep it in the app or in a backup file you control.
- Deleting the app removes local SwiftData unless you exported a copy first.

## Your choices

- Use the app without creating any online account.
- Export a backup before reinstalling or switching devices.
- Deny optional permissions (Photos, Notifications).
- Cancel subscriptions in Apple’s subscription settings.
- Request help or privacy questions via [SUPPORT.md](./SUPPORT.md).

## Changes

We may update this policy. The **last updated** date at the top will change; the current version is always in this repository.

## Contact

See [SUPPORT.md](./SUPPORT.md).
