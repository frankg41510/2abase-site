# App Review Notes for 2A Base

2A Base is a reference and regulatory-update app for firearm law research. It does not sell firearms, ammunition, accessories, training, or regulated goods. It does not facilitate weapon purchases, transfers, private sales, dealer referrals, product listings, price comparisons, or location-based matching between buyers and sellers.

The app provides general educational information only and includes source links, last-scan or last-update indicators, and repeated legal disclaimers. Users are instructed to verify current law with official government sources and consult a licensed attorney before making carry, transport, storage, transfer, or compliance decisions.

## Reviewer Access

No account is required to review the free app experience.

If Pro review is required, create the in-app subscription products in App Store Connect and RevenueCat before submitting the binary. Use StoreKit sandbox testing for purchase validation.

## In-App Purchases

The app uses Apple in-app purchase through RevenueCat for optional Pro access. No external payment link is used inside the app. The Restore Purchase action is available in the subscription UI and Account tab.

## Notification Consent

Push notifications are optional. The app does not request push permission at first launch. Permission is requested only after the user enables one or more notification categories in the Account tab. Users can disable all notification categories from Account.

## Sensitive Functionality Boundaries

The app does not provide emergency guidance, self-defense instructions, firearm operation training, weapon modification instructions, tactical instructions, or instructions to evade law enforcement. The app is limited to legal-reference summaries and source-linked regulatory updates.

## Data Collection Summary

The app stores selected state, checklist progress, display name, profile image, notification preferences, and CCW expiration reminders locally on device. Optional push notifications require an Expo push token and selected state so relevant alerts can be delivered. Subscription status is handled through RevenueCat and Apple.
