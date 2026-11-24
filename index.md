# Privacy Policy — GeoNotes

**Last updated:** 24 November 2026

GeoNotes is an Android app that attaches notes to places and reminds you when you arrive at or
leave them. This policy explains what the app does with your data. GeoNotes has no accounts and
no server of its own: your notes and places stay on your device. The app is free and shows ads
from Google AdMob, which is the one part of it that collects data, as described below.

## What GeoNotes stores on your device

Everything below is written to a private file inside the app's own sandbox on your device. It is
never uploaded to us; we operate no servers.

| Data | Why | Where it lives |
| --- | --- | --- |
| Notes — title, text, category, place name, latitude, longitude, radius, arrive/leave trigger, whether it has fired | So the app can show your notes and remind you at the right place | On your device only |
| Category names you create | To group notes | On your device only |
| App settings — theme, dynamic colour, default radius and trigger, snooze length, units | To restore your preferences | On your device only |
| Cached map tiles | So the map loads quickly and works with a poor connection | App cache on your device |

Uninstalling the app deletes all of it. You can delete individual notes at any time.

## How GeoNotes uses your location

- **Reminders (background location).** When a note has a place, GeoNotes registers a *geofence*
  — a circle around that place — with Google Play services on your device. Android then tells
  GeoNotes when you enter or leave the circle, even while the app is closed, which is why the app
  asks for "Allow all the time" location access. The check happens on your device; GeoNotes does
  not record, store or transmit your location history or your current position.
- **The map.** The Map tab uses your current location to show where you are relative to your
  notes. That reading is used to draw the screen and is not saved or sent anywhere by GeoNotes.

You can turn location access off at any time in Android's settings. Notes keep working as plain
notes; place reminders stop firing.

## Notifications and your home screen

Reminders appear as Android notifications, and the optional home-screen widget shows your notes.
Their text is therefore visible to anyone looking at your phone, including on the lock screen if
your device shows notification content there. Nothing is transmitted either way.

## Advertising (Google AdMob)

GeoNotes shows banner ads served by **Google AdMob**. To serve and measure ads, the Google Mobile
Ads SDK collects and sends to Google information such as:

- your device's **advertising ID** and other device identifiers,
- your **IP address**, from which an approximate (city-level) location can be derived,
- device and app information (model, OS version, language, app version),
- ad interactions (ads shown and tapped) and diagnostic data such as crash logs from the SDK.

GeoNotes does **not** pass your notes, your places, or your device's precise location to AdMob.
Google may use this data to show personalised ads, where the law allows and you have consented.
How Google uses it is described in
[How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)
and in [Google's Privacy Policy](https://policies.google.com/privacy).

You can reset or delete your advertising ID, or opt out of personalised ads, in
*Android Settings → Google → Ads* (or *Settings → Privacy → Ads* on some devices).

## Other network requests

### Map tiles

The map is drawn from [OpenFreeMap](https://openfreemap.org/) tiles, built from
[OpenStreetMap](https://www.openstreetmap.org/) data, downloaded as you pan and zoom. Like any
map, this means the tile server sees your device's IP address and which part of the world you are
viewing — which, when the map is centred on you, is the area around you. No account, identifier
or coordinate of yours is attached to those requests.

### Google Maps links

If you paste a Google Maps link to set a note's place, GeoNotes may follow that link's redirects,
and look up the place it points to on `maps.google.com`, in order to read its coordinates. This
sends the link you pasted to Google, exactly as opening it in a browser would; Google's handling of
that request is covered by [Google's Privacy Policy](https://policies.google.com/privacy).

No other network request is made by GeoNotes itself.

## Sharing and selling

We do not sell your data and do not share it with anyone. The only third parties that receive data
are the ones named above (Google AdMob, the map tile server, and Google Maps when you paste a link),
and only the data described there.

## Backups

Your notes are **excluded from Android cloud backup**, so your places are not copied to Google
Drive. They are included in direct device-to-device transfer, so they survive moving to a new
phone without passing through any server.

## Permissions

| Permission | Why it is needed |
| --- | --- |
| `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` | To know when you cross a note's place, and to show your position on the map. |
| `ACCESS_BACKGROUND_LOCATION` | So reminders fire while the app is closed. Without it, place reminders cannot work. |
| `POST_NOTIFICATIONS` | To show reminders on Android 13 and newer. |
| `RECEIVE_BOOT_COMPLETED` | To re-register your place reminders after the phone restarts or the app updates. |
| `INTERNET` / `ACCESS_NETWORK_STATE` | To download map tiles and ads, and to read pasted Google Maps links. |
| `AD_ID` (added by the AdMob SDK) | Lets the ads SDK read the advertising ID, as described above. |

## Children

GeoNotes is not directed at children under 13, and we do not knowingly collect personal
information from children.

## Your choices

- Delete notes in the app, or uninstall it to delete everything it stored.
- Revoke location or notification access in Android settings at any time.
- Reset your advertising ID or opt out of personalised ads in Android settings.

## Changes to this policy

If this policy changes, the "Last updated" date above changes with it, and the new version
replaces this one at the same URL.

## Contact

Questions about this policy: `android8giga@gmail.com`
