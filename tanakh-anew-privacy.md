# Tanakh Anew · תנ״ך מחדש — Privacy Policy

**Updated October 1, 2026.** Tanakh Anew is **not publicly available on the App Store**. iOS **1.0.0/build 3**, its first weekly subscription and subscription group were submitted together and are **Waiting for Review**. Build 3 uses direct Apple StoreKit rather than RevenueCat. Older internal TestFlight build 1 is a free reader with no account or purchase feature; older build 2 used RevenueCat and is not the build submitted for App Review.

## Free reader

All 24 traditional Jewish books, Hebrew and public-domain JPS 1917 editions, chapter reading, offline text, search and saved verses are free. Your language choice, reading preferences, bookmarks, reading check-ins and guided-study completion stay on your device. They are **not uploaded or synchronized** with Tanakh's account backend. Removing the app may remove this local data.

## Optional Apple account in builds 2 and 3

Signing in with Apple is optional for both free and paying readers; it is not required to read or purchase. When chosen, Apple provides a signed identity token, an account identifier and, if permitted, an email address or private-relay address. The app sends the token to a separate **Tanakh Anew Supabase Auth project in Frankfurt, Germany** for verification and stores an encrypted session on the device with its encryption key in iOS Keychain. It does not request a name, contacts or birth date. The project may retain account identity, an optional email/relay address and operational security logs. It does **not** receive your reading history, saved verses or study progress. Signing in on another device establishes account identity, **not** cloud reading-data sync. A build-3 TestFlight Apple sign-in produced a verified Tanakh backend account before App Review submission.

A signed-in reader can choose **Membership → Delete Tanakh account** and confirm a request to an authenticated Tanakh-only deletion function. This deletes the backend account if successful, not local reading data and not an Apple subscription. Account deletion has not yet been confirmed in a real-device test. Signing out likewise does not cancel a subscription. If deletion fails, consult the [support page](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-support.md) without posting account details in a public issue.

## Weekly membership and billing

Apple handles billing; Tanakh does not receive payment-card information. **Build 3 uses direct Apple StoreKit on iPhone**, not RevenueCat: it queries the exact weekly product, verified current entitlement and expiration on device. It does not upload subscription status to Tanakh's Supabase project. Local guided-study access is denied if Apple cannot verify an active weekly subscription. The U.S. weekly price is $2.99; Apple displays its storefront-localized price elsewhere. No free trial is configured. The TestFlight user reported a completed sandbox purchase, premium unlock and Restore on build 3; a purchase-sheet screenshot by itself is only a prompt, not evidence of completion.

Older TestFlight build 2 used RevenueCat's anonymous customer identifier and purchase-history processing; it did not send the Supabase account ID or email to RevenueCat. The **build-3 App Store privacy declaration** instead lists optional account Email Address and User ID for account functionality, not tracking. Direct StoreKit transaction data handled by Apple/on-device is not collected by our backend. If a future build changes data flows, its privacy disclosures will need to change too.

Deleting the app or Tanakh account does **not** cancel Apple billing. To avoid further charges, cancel separately in Apple's subscription settings. We do not sell reading data or use it for targeted advertising. If you contact support outside the app, any information you voluntarily provide is processed by that contact service. **Public GitHub issues are public; never post email, account identifiers, private notes, passwords, receipts or payment details there.**

Tanakh Anew is an independent Jewish reading app; it is not affiliated with Sefaria, JPS or tanach.us. See its [text-edition sources](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-sources.md).
