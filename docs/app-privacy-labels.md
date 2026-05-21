# App Store Privacy Label Draft

Use this as the starting point for App Store Connect. Verify against the final SDK list before submission.

## Data Collected

### Identifiers
- Device ID or other identifier: Expo push token, only if the user enables notifications.
- Linked to user: No, unless you later add accounts or email login.
- Used for tracking: No.
- Purpose: App functionality.

### Purchases
- Subscription status and purchase metadata are processed by Apple and RevenueCat.
- Linked to user: Potentially yes through Apple/RevenueCat subscriber identifiers.
- Used for tracking: No.
- Purpose: App functionality.

### User Content
- Profile photo and display name are stored locally only and should not be marked as collected unless later transmitted to a backend.

### Diagnostics / Usage Data
- Currently no first-party analytics are implemented. Confirm RevenueCat SDK diagnostics requirements before final answers.

## Data Not Collected By Current App Code
- Precise location
- Contacts
- Email address
- Firearm ownership information
- Firearm serial numbers
- Government IDs
- Financial payment card data

## Required App Store Connect URLs
- Privacy Policy: https://2abase.com/privacy
- Terms: https://2abase.com/terms
- Support: https://2abase.com/support
