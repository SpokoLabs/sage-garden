---
title: Sage Garden — Privacy Policy
---

# Privacy Policy for Sage Garden

**Last updated: 10 November 2026**

Sage Garden ("the app") is a personal garden-tracking app developed by Spoko Labs. This page explains what data the app collects, why, where it's stored, and who it's shared with.

## Data the app collects

**Garden and plant data.** Plant names and details, notes, care schedules and history (watering, fertilising, pruning, feeding), garden zones, your garden's name, and where plants sit on your map. This is stored on your device, and is also synced to the app's cloud backend (Google Firebase) so your gardens stay in sync across your devices and with anyone you choose to share a garden with.

**Garden map and layout.** If you upload a plan or drawing of your garden, a downscaled copy of that image — together with the irrigation lines, sun zones and irrigation zone names you draw on it — is synced to the app's cloud backend, so it can be shown to people you share the garden with, including in the web view, which can also print garden reports.

**Photos.** Photos you attach to plants are stored on your device by default, or in a Dropbox folder you choose if you connect Dropbox. A small, low-resolution thumbnail of each plant's main photo is synced to the app's cloud backend with the plant, so it can be shown on your other devices and to people you share the garden with. For extra, growth timeline and progress photos you've uploaded to Dropbox, the photo's Dropbox link — with its date, label and the plant or zone it belongs to — is also synced, so those photos can be viewed on your other devices (including the web view and car app) and by people you share the garden with. Full-size photos are never uploaded to Sage Garden's backend.

**Location.** If you set a garden address, the address and its coordinates are stored with the garden and synced to the app's cloud backend (so everyone sharing the garden sees it in the right place). Address searches are sent to Google's Places/Geocoding APIs to turn them into coordinates. The garden's coordinates are sent to Open-Meteo to fetch the weather forecast for weather-aware reminders and frost and heat warnings. The app doesn't ask for location permission or use your device's own location.

**Identifiers.** The app generates a random install ID (not tied to your name, email or Google account), and signs in anonymously to Firebase, which assigns a random user ID. These identify your device to the app's backend for syncing, garden sharing, Sage assistant usage limits and promo codes. The app does not ask for or collect your name, email address or phone number. If you share a garden, the device name you choose (for example "Dan's phone") is shown to the garden's other members.

**AI assistant and identification.** If you use Sage (the in-app AI assistant), your typed questions are sent to Anthropic to generate a response. To save repeat calls, Sage's answer to a general question is kept on the app's backend for up to 90 days and reused when anyone asks exactly the same question; only a one-way fingerprint of the question is kept with it, never the question itself or anything identifying you. Questions that look personal (for example containing a name, address, email, phone number or link) or are long are never kept. If you use Sage's plant suggestions, the plant's scientific name is sent. If you identify a plant from a photo, that photo is sent to Pl@ntNet. If you report a Sage answer, your question, Sage's answer, the reason you chose and any detail you add are stored on the app's backend so the developer can review them; they are deleted with the rest of your data (see below).

**Smart-irrigation credentials.** If you connect a Tuya or Rachio irrigation account, the credentials you enter are stored on your device only, and used to talk directly to that vendor's cloud from your device. They are never sent to Sage Garden's backend or included in backups.

**Web view (sagegarden.web.app).** Someone without the Android app can view a garden shared with them on the Sage Garden web page. Joining sends the invite code and the name they type to the app's backend so the garden's owner can approve them; the owner sees that name. Their browser then keeps a random ID and an access token for the garden in its own storage (no cookies, no tracking), and uses them to read the garden from the app's backend. The web page can view a garden; if the owner gives them edit access, it can also record care, snooze tasks, edit a plant's main details, and note pests and harvests, the same changes the app makes. On an iPhone, "Add to your Home Screen" asks the backend for a one-time code (valid for 10 minutes) so the Home Screen copy can take over the same access; the code is deleted once used. If they turn on the daily reminder on the web page, the browser's push subscription (an address at their browser's own push service, such as Apple's), the reminder time and their time zone are stored so the backend can send one notification a day when something is due; turning the reminder off, or leaving every garden, deletes them. Clearing the browser's site data removes the ID and token; the owner can remove their access at any time.

## Who your data is shared with

- **Google Firebase / Google Cloud** — hosts the app's backend: garden sync and sharing, change notifications between devices, AI request relaying, usage limits and promo codes.
- **People you share a garden with** — see that garden's plants (with thumbnails), care history, name, address and zones, the owner's garden map with its irrigation lines and sun zones, and the device names of its members.
- **Anthropic** (Claude AI) — your Sage chat messages, and plant scientific names for suggestions. See [Anthropic's privacy policy](https://www.anthropic.com/legal/privacy).
- **Pl@ntNet** — a plant photo, when you identify a plant. See [Pl@ntNet's privacy policy](https://identify.plantnet.org/data-privacy).
- **Google Maps / Places** — address search text and map coordinates, for maps and address lookup.
- **Open-Meteo** — your garden's coordinates, for weather, frost and heat forecasts. See [Open-Meteo's terms](https://open-meteo.com/en/terms).
- **Dropbox** — only if you connect it: the photos you choose to store there, under your own Dropbox account.
- **Tuya / Rachio** — only if you connect one: your device talks directly to that vendor's cloud, to read watering history.

All data is sent over encrypted connections (HTTPS). The app has no advertising or analytics/tracking SDKs, and your data is never sold.

## Data retention and deletion

Data on your device is deleted when you uninstall the app, except photos in your own Dropbox and any backup or export you saved to a folder of your choice, which you control.

Garden data synced to the app's backend is kept while the garden exists, so it stays in sync and can be shared. Deleting a plant removes it from the backend; deleting a garden you own (Settings → This garden) removes it and all its data from the backend for everyone.

**Deleting all your data.** In the app, Settings → Backup & data → "Delete all my data" deletes every garden you own from the backend (for everyone you share it with), removes you from gardens shared with you, deletes your device records, Sage usage record and any Sage reports, and then clears everything on your phone. If you no longer have the app installed, email us with your Install ID (Settings → About), if you have it, and we'll delete your data.

## Children's privacy

Sage Garden is not directed at children under 13, and does not knowingly collect data from them.

## Changes to this policy

If this policy changes, the "Last updated" date above will change accordingly.

## Contact

Questions about this policy or your data: **spokolabs@gmail.com**
