# TestFlight Review Script

Use this script when testing the iOS preview build.

## Core navigation

- Open the app.
- Confirm onboarding appears or the selected state loads.
- Open Home/Laws, County, Updates, Account.
- Confirm no screen crashes.

## Laws page

- Confirm the monthly update banner appears instead of Pro scan copy.
- Search for a common topic such as carry or storage.
- Open a law card.
- Confirm source status and manual-verification language appear.
- Save a source link if available.

## County roadmap

- Select California and Alameda County.
- Confirm the application link is Permitium.
- Confirm fee, processing, and training values match the current verified source note.
- Mark roadmap steps complete and relaunch the app to confirm progress persists.

## Watchlist and retention

- Save a jurisdiction.
- Save an official source link.
- Confirm dashboard counts update.
- Confirm the Relevant to Me filter reflects saved/home jurisdictions.

## Updates

- Open Updates.
- Confirm unread indicators display correctly.
- Confirm update content has source and verification context.

## Paywall

- Open Pro paywall.
- Confirm product display is neutral and not firearm-commerce oriented.
- Test purchase and restore only in TestFlight/development build, not Expo Go.

## Account

- Confirm legal disclaimer is visible.
- Confirm notification toggles are opt-in.
- Confirm support/privacy/terms links open and do not 404.
