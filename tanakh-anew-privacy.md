# Tanakh Anew · תנ״ך מחדש — Privacy Policy

**Updated October 1, 2026.** Tanakh Anew is **not publicly available on the App Store**. The original **1.0.0/build 1** internal TestFlight version is a free bilingual reader. **Build 2** added premium and Apple-account source but still included RevenueCat; it remains an older TestFlight binary. **1.0.0/build 3** is Apple VALID and assigned to an internal TestFlight group; it removes RevenueCat and uses Apple's direct StoreKit for purchases. Its completed purchase, Restore and Apple-login flows have **not yet been independently verified on a device or against the account backend**. The app version and weekly subscription have not been submitted for App Review.

## Free reader

All 24 traditional Jewish books, Hebrew and public-domain JPS 1917 editions, chapter reading, offline text, search and saved verses are free. Your language choice, reading preferences, bookmarks, reading check-ins and guided-study completion stay on your device. They are **not uploaded or synchronized** with Tanakh's account backend. Removing the app may remove this local data. Build 1 has no Tanakh account or purchase feature.

## Optional Apple account in builds 2 and 3

Signing in with Apple is optional for both free and paying readers; it is not required to read or purchase. When chosen, Apple provides a signed identity token, an account identifier and, if permitted, an email address or private-relay address. The app sends the token to a separate **Tanakh Anew Supabase Auth project in Frankfurt, Germany** for verification and stores an encrypted session on the device with its encryption key in iOS Keychain. It does not request a name, contacts or birth date. The project may retain account identity, an optional email/relay address and operational security logs. It does **not** receive your reading history, saved verses or study progress. Signing in on another device establishes account identity, **not** cloud reading-data sync. Native login has not yet been verified against this project's account records.

A signed-in reader can choose **Membership → Delete Tanakh account** and confirm a request to an authenticated Tanakh-only deletion function. This deletes the backend account if successful, not local reading data and not an Apple subscription. Signing out similarly does not cancel a subscription. If deletion fails, consult the [support page](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-support.md) without posting account details in a public issue.

## Weekly membership and billing

Apple handles billing; Tanakh does not receive payment-card information. **Build 3 uses direct Apple StoreKit on iPhone**, not RevenueCat: it queries the exact weekly product, verified current entitlement and expiration on device. It does not upload the subscription status to Tanakh's Supabase project. Local guided-study access is denied if Apple cannot verify an active weekly subscription. The U.S. weekly price is $2.99; Apple displays its storefront-localized price elsewhere. No free trial is configured. A real Apple sandbox purchase sheet is not proof that a purchase completed or premium unlocked.

**Older TestFlight build 2** still includes RevenueCat's anonymous customer identifier and purchase-history processing for entitlement checks; it does not send the Supabase account ID or email to RevenueCat. The App Store privacy declaration must accurately reflect the actual binary submitted for public release, including any optional account identifiers and purchase data. The current Apple label was prepared for build 2 and must be revisited before build 3 is submitted.

Deleting the app or Tanakh account does **not** cancel Apple billing. To avoid further charges, cancel separately in Apple's subscription settings. We do not sell reading data or use it for targeted advertising. If you contact support outside the app, any information you voluntarily provide is processed by that contact service. **Public GitHub issues are public; never post email, account identifiers, private notes, passwords, receipts or payment details there.**

Tanakh Anew is an independent Jewish reading app; it is not affiliated with Sefaria, JPS or tanach.us. See its [text-edition sources](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-sources.md).
