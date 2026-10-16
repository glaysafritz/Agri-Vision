# Agri Vision (Soil Analysis and Crop Recommendation Mobile Application)

An offline Android app that identifies soil type from a photo and recommends crops suited to that soil and to the farmer's barangay. Built for smallholder farmers in Guimbal, Iloilo.

Most farmers decide what to plant based on habit or on what a neighbor is planting, because soil testing means sending a sample to a laboratory and waiting for results. Agri Vision shortens that to a photo. The farmer points a phone at the ground, picks their barangay, and gets a ranked list of crops with a suitability rating for each.

It runs entirely on the phone, so it works in the field where there is no signal and no data to spend.

Download page: https://glaysafritz.github.io/agrivision/

---

## What it does

1. The farmer takes a photo of their soil.
2. The app identifies the soil type, color, texture, and surface condition.
3. The farmer selects their barangay to pull local pH and NPK values.
4. The app returns a ranked list of crops with a suitability rating.

Everything runs on the phone. No internet connection is needed to use it.

## Features

- Soil image classification across six soil types
- Crop recommendation using barangay-level soil data
- Land suitability rating per crop, following FAO classes S1, S2, S3, and N
- Barangay soil reference for 15 barangays in Guimbal
- Tap-to-translate between English and Tagalog
- Works fully offline

## Coverage

Barangay soil data covers 15 barangays in Guimbal, Iloilo, sourced from Department of Agriculture soil health cards.

## This repository

This repository holds the public download page for the app.

| File | Purpose |
|---|---|
| `index.html` | The download page |
| `icon.png` | App icon |
| `favicon.ico` | Browser tab icon |
| `apple-touch-icon.png` | Icon for pinned shortcuts |
| `1.jpg` to `5.jpg` | App screenshots |

The app source code is not published here.

## Installing

Android blocks apps from outside the Play Store by default, so there is one extra step the first time.

1. Open the download page and tap Install.
2. If the browser warns about the file, tap Download anyway.
3. Open the downloaded file.
4. When asked, allow installs from this source, then go back.
5. Tap Install.
