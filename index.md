---
layout: default
title: Privacy Policy
---

# JustETA Privacy Policy

**Effective Date:** May 20, 2026

Kodeman Industries ("we", "us", "our") makes JustETA. We've designed JustETA so that we don't have to know anything about you for the app to be useful. This policy describes the limited data the app handles and what it does not, on both iOS and Android.

## What we don't collect

JustETA does not collect personal information. We don't have user accounts. We don't run servers that store your data. We don't share information with advertising networks. We don't sell anything about you.

In particular:

- **Your saved destinations, addresses, custom labels, and routes** are stored locally on your device. On iOS, they synchronize through your own iCloud account; on Android, they live in on-device storage (DataStore) and are not transmitted to us.
- **Your location** is used on your device only — to compute travel times — and is not transmitted to us. We use the most battery-friendly available APIs (Apple's CoreLocation significant-location-change monitoring on iOS, Android's passive/significant-change location providers on Android), running entirely on-device.
- **Advertising and tracking identifiers** (IDFA, IDFV-based fingerprints, Android Advertising ID, third-party SDKs that fingerprint or track) are not used.

## What the app sends to third parties

JustETA relies on a few first-party platform services to compute travel times and process purchases. These services receive only what they need to do their job; we do not see or store the results.

### Maps and routing

- **iOS** uses Apple's **MapKit** to compute travel times, search for places, and display maps. [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) applies to MapKit requests.
- **Android** uses **Google Maps SDK**, **Places API**, and **Routes API** for the same purpose. [Google's Privacy Policy](https://policies.google.com/privacy) applies to those requests. Each request includes the coordinates or place query needed to compute the result and is governed by Google's published privacy terms.

We do not see, store, or aggregate these requests.

### Cross-device sync

- **iOS:** Saved destinations and routes synchronize via **iCloud (CloudKit)**. Your data lives in your private CloudKit database, encrypted with your iCloud account credentials. We do not have access to it. [Apple's iCloud terms](https://www.apple.com/legal/internet-services/icloud/) apply.
- **Android:** Today, Android data is stored on-device only and does not sync to other devices. If a future version adds Google Drive or Firebase-based sync, this policy will be updated.

### Apple Watch / Wear OS

The paired-watch app receives a read-only payload (your saved destinations, ETAs, theme, and Pro status) from the phone over the platform's local-only data layer (WatchConnectivity on iOS, Wearable Data Layer on Android). The watch does not run network requests of its own; it never contacts our servers (we don't have any).

### In-app purchases

When you buy JustETA Pro, the platform processes the transaction:

- **iOS:** Apple processes the purchase via **StoreKit 2**. The app verifies the purchase on-device. We don't receive your name, email, or payment details. Apple's privacy policy applies.
- **Android:** Google processes the purchase via **Google Play Billing**. The app verifies the purchase on-device. We don't receive your name, email, or payment details. [Google Play's privacy disclosures](https://play.google.com/intl/en_us/about/play-terms/) apply.

### Anonymous usage telemetry (opt-out)

With your consent — controlled by **Settings → Privacy → Share Anonymous Analytics**, default on, and reversible at any time — JustETA sends anonymous usage signals to [TelemetryDeck](https://telemetrydeck.com), a privacy-friendly analytics provider based in Austria. These signals tell us things like "an app launch happened" or "the user added a destination" — but never include your destinations, addresses, location, identifiers, or any other personal data. TelemetryDeck does not receive your IP address. The same opt-out switch covers both iOS and Android.

When you turn analytics off, no telemetry is sent.

## Permissions we request

- **Location (When In Use)** — required to compute travel times from where you are. You can deny this and still use the app by entering custom origins per destination.
- **Notifications** — only requested if you opt in to a feature that needs them (e.g., a future departure-alert feature). Not required for core ETAs.
- **Network access (Android)** — required for the maps and routing requests described above.

We never request contacts, camera, microphone, photos, or other sensitive permissions.

## Children's privacy

JustETA is rated for general audiences and does not collect personal information from anyone, including children. JustETA is not directed at children under 13.

## Changes to this policy

We may update this policy from time to time. The "Effective Date" above will reflect the most recent change. Material changes will be announced in the app's release notes.

## Contact

Questions about this policy? Email us at [kodeman@kodemanindustries.com](mailto:kodeman@kodemanindustries.com).
