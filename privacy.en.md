# Privacy Policy — Renewly

_Last updated: April 23, 2026_

Renewly ("the app") is a local-first subscription reminder utility developed by Roy Liu. This policy explains exactly what the app does — and, more importantly, what it does **not** do — with your data.

## 1. What we collect

**Nothing.** The app does not collect, transmit, or share any personal or usage data. It has no analytics, no telemetry, no crash reporting sent to us, no advertising SDK, and no third-party trackers.

## 2. Where your data lives

All data you enter (subscription names, amounts, due dates, notes, etc.) is stored **locally on your device** using Apple's SwiftData framework. The app uses an App Group container (`group.com.yirenliu.Renewly.shared`) so the Home Screen widget and the main app can share the same local database. Nothing is uploaded to any server.

## 3. Network access

By default the app makes **no network requests** and works fully offline.

One optional exception: if you turn on the "Use live exchange rates" switch under Settings → Exchange rates, the app will query `open.er-api.com` once every 24 hours for current currency rates, used to convert subscriptions in different currencies into a common summary currency. This request contains **only a public rate lookup for a base currency** — none of your data (subscription names, amounts, device identifiers, etc.) is transmitted. The fetched rates are cached locally for offline use. You can turn this switch off at any time, and the app returns to being fully offline.

## 4. Notifications

The app schedules **local** notifications on your device for upcoming renewals. These notifications are generated and delivered entirely by iOS. No notification content is sent through any external push service.

## 5. Data export & import

You can export your data to a JSON file and import it back. This is strictly a user-initiated operation. The exported file is saved wherever you choose (Files, AirDrop, iCloud Drive, etc.) and we have no access to it.

## 6. Children's privacy

The app is not directed to children under 13 and does not knowingly collect any information from anyone, including children.

## 7. Changes to this policy

If this policy changes, the updated version will be published at the same URL and the "Last updated" date will be revised.

## 8. Contact

Email: ralstonish@gmail.com
