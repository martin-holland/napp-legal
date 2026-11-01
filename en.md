---
title: Napp privacy policy
lang: en
permalink: /en/
---

# Napp privacy policy

Last updated: 1 November 2026

Napp is a fishing app for Finnish waters. This policy explains what happens to your data when you use the app. In short:

- Napp has no accounts, no ads, no analytics tools and no tracking.
- Your catch log, your catch photos and your exact fishing spots stay on your phone, unless you export your log yourself.
- To fetch weather, water and rules data, the app asks open data services about lakes, using each lake's public register point, and about sea spots and the map area you view, rounded to 0.1 degree squares.

## Who is responsible

Beacon International Oy, Finland, is the controller of personal data processed through Napp.

Contact: dev@beacon-international.org

## What stays on your phone

Napp keeps the following only in the app's storage on your phone:

- your catch log and fishing sessions;
- the photos you add to a catch (Napp Full). Napp saves its own copy, re-encoded and stripped of the photo's metadata, such as the GPS position the camera recorded, the time and the camera model. A photo you pick stays as it was in your phone's gallery. A photo you take in Napp is not saved to your gallery by Napp, but your camera app may keep its own copy;
- the GPS positions of your catches and sessions, and the exact sea spots you pick on the map;
- your favourite waters, language choice and settings;
- whether you have Napp Full, by a subscription or the lifetime purchase, and when a subscription ends or was last confirmed by the store;
- copies of the data the app has fetched, so it works offline.

Napp never uploads any of this.

**Exporting your log (Napp Full):** when you tap "Export as CSV" in My log, the app makes a CSV file of your log on the phone and opens your phone's share sheet. The file holds your sessions and catches with their times, species, sizes and saved conditions; your notes and lures; the names of the waters you fished; and the exact coordinates of your spots (where you fished in a session, where you caught each fish, and the sea spots you picked). It goes only where you choose to send it (an email, a cloud drive, another app), under that service's terms. Napp does not receive a copy and collects nothing from it. A copy may stay in the app's own cache on the phone until your next export or until the phone clears the cache.

If backups are turned on in your phone (Google or iCloud), the phone includes the app's data in your own backup, under your account and that provider's terms. Catch photos are left out of Android backups; on an iPhone they are part of the device backup (iCloud or a computer). Uninstalling the app deletes the data from the phone, but not from backups already made; you manage those in your Google or iCloud account.

## Location permission

Napp asks for location only while you use the app, and only to save where you caught a fish. There is no background tracking. Location is optional: you can refuse or withdraw the permission in your phone's settings. The app still works, but catches are then saved without a spot.

Conditions for a session or catch are fetched for the lake you chose, not for your position. At sea, they are fetched for the sea spot you picked on the map, rounded to 0.1 degrees (about 5 to 11 km). If a catch were ever saved without a lake or sea spot, the app would use your position rounded to 0.1 degrees instead. Your exact position is never sent.

## Camera and photos

Napp asks for the camera only when you tap "Take a photo", and uses it only to take that photo. Choosing photos uses your phone's own photo picker: Napp gets only the photos you pick, and asks for no permission to your photo library. You can refuse or withdraw the camera permission in your phone's settings; you can still choose photos. Photos are never uploaded or sent anywhere.

## What the app sends, and why

To show weather, water temperature, water level, ice and fishing rules, the app requests open data. Each request contains one of the following:

- **A lake's register point or number:** taken from the public Finnish lake register (for the satellite ice reading, a small area around that point), sent when you open a lake, see it on the map, or log a session or catch there. It is not your GPS position. However, because a lake looked up while you log a catch is probably where you are, we treat these requests as approximate location.
- **A sea spot, rounded:** when you pick a spot on the sea on the map, open it, or log a session or catch there, the app sends that spot rounded to 0.1 degrees (about 5 to 11 km), never the exact point. Because it is roughly where you fish, we treat these requests as approximate location.
- **The map area on your screen:** map tiles are requested for the area you are viewing. When you zoom in closely, the app also asks for the fishing restriction areas there: the visible area as rounded 0.1 degree grid squares (about 5 to 11 km), sent to Napp's server or, when it cannot provide them, to the Kalastusrajoitus service. The map never follows your GPS position.
- **A lake name:** the text you type when you search for a lake.

As with any internet request, the services also see your device's IP address.

These requests go to:

| Service | What for | Who runs it |
| --- | --- | --- |
| Napp's server (Supabase, EU region) | Fetches and caches weather, water and restriction data, and serves updates to species profiles and rules | Supabase on our behalf (processor) |
| Finnish Environment Institute, Syke (rajapinnat.ymparisto.fi, geoserver2.ymparisto.fi) | Lake search and lake details, always directly; water temperature, level, ice and satellite lake ice when our server cannot provide the data | Syke |
| Finnish Meteorological Institute (opendata.fmi.fi) | Weather and forecasts, and at sea the sea temperature, sea level and waves, when our server cannot provide the data | FMI |
| Copernicus Marine Service (wmts.marine.copernicus.eu) | Satellite sea temperature for a rounded sea spot, when our server cannot provide the data | Mercator Ocean International, for the EU |
| Kalastusrajoitus service (avoinkara-mmm.ruokavirasto-awsa.com, MMM, run by the Finnish Food Authority) | Local fishing restrictions, when our server cannot provide the data | MMM / Ruokavirasto |
| OpenFreeMap (tiles.openfreemap.org) | Map tiles | OpenFreeMap |

**On Napp's server:**

- **The cache:** fetched open data is cached by lake point or map cell, not linked to you or your device. Entries are deleted after their lifetime: weather and sea forecasts within about 5 hours, satellite readings within about 10 hours, fishing restrictions within about 28 hours, and lists of measuring stations on a lake (by lake number) within about 8 days.
- **The logs:** the hosting provider's request logs hold each request's address (including the lake point or number, or the map square, asked for), your IP address and the time. On our current plan they are kept for 1 day, and in any case at most 7 days, to run and secure the service. Supabase and its network providers (Cloudflare, AWS) keep their own infrastructure logs under our data processing agreement.
- **Use:** we do not use the cache or the logs to identify or follow anyone, and we cannot link them to a person unless you give us your IP address and the time (GDPR Article 11).
- **Legal basis:** our legitimate interest in running the app you chose to use, reliably and securely (GDPR Article 6(1)(f)). Napp makes no automated decisions about you.

FMI, Syke, Copernicus Marine, the Kalastusrajoitus service and OpenFreeMap handle their own server logs under their own privacy terms.

## Purchases

Napp Full is sold through the App Store or Google Play, as a subscription or a lifetime purchase. Apple or Google handles the payment and any free trial under their own terms. Napp receives only the store's confirmation of what you have (for a subscription, also when its current period ends, where the store says), and keeps that on your phone only, so the app opens unlocked offline and stops unlocking when a subscription ends. We never see your payment details.

## Links

Some screens link to other sites, for example Omakala for the statutory catch report, or the data providers' own pages. Those sites have their own privacy policies.

## Transfers outside the EU

Napp's server runs in an EU region. Supabase is a US company. Any access from outside the EU is covered by the EU Standard Contractual Clauses in our data processing agreement with Supabase. Contact us for a copy. Apple and Google process purchases under their own terms.

## Your rights

Under the GDPR you have the right to:

- access your personal data;
- have it corrected or erased;
- restrict its processing;
- object to processing based on legitimate interest (Article 21).

Napp keeps no personal data about you on its servers beyond the short-lived logs and cache described above, so most of your data is under your own control on your phone. For anything else, contact us at the address above.

You can also lodge a complaint with the Data Protection Ombudsman in Finland (tietosuoja.fi).

## Changes

If this policy changes, the new version is published at this address with a new date. Material changes are also mentioned in the app's release notes.
