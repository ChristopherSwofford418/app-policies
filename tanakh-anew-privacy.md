# Tanakh Anew · תנ״ך מחדש — Privacy Policy

**Updated October 1, 2026.** The version currently distributed in internal TestFlight is **1.0.0/build 1**, a free bilingual reader. The separate onboarding, $2.99/week U.S. subscription draft and Supabase-backed Apple-account changes described below are a **source candidate only**: they have not been built, installed, or submitted for App Review. Tanakh Anew is not yet publicly available on the App Store.

## Current internal TestFlight build 1

Your Hebrew/English choice, reading preferences, saved verses and reading check-ins are stored locally on your device. The Hebrew and public-domain JPS 1917 editions are bundled so reading and search work offline. **Build 1 has no Tanakh user account, cloud sync, analytics SDK, advertising SDK, location collection, document uploads or in-app purchase.** We do not receive saved verses or reading preferences from this build.

Removing the app normally deletes its locally stored data under your device's app-data rules. Build 1 has no server-side Tanakh account to delete.

## Unbuilt premium and Apple-account candidate — not in build 1

The next candidate retains **all 24 traditional Jewish books, both editions, offline reading, search and saved verses free**. On supported iPhones it presents the optional Premium Study subscription offer **before** any account sign-in. A person can skip the offer and read without an account or purchase. A premium member may choose native Sign in with Apple after purchasing or restoring an active membership; an Apple account is not required to use the membership.

**Local reading data:** Language, chosen path, saved verses, check-ins and seven-day study completion remain on the device; these are **not uploaded or synchronized** to Supabase. Deleting the app may remove local data. Signing in on another device establishes the same Apple-backed account identity, **not** cross-device reading-data sync.

**Account data if Apple login is chosen:** Apple supplies a signed identity token, an Apple account identifier, and, if the person permits it, an email address or Apple private-relay address. The app sends the token to **Supabase Auth** for verification. A dedicated Tanakh Anew project hosted in Frankfurt, Germany, stores the resulting account identifier, Apple-provider identity and any email/relay address supplied. The app does not request a name, contacts or birth date. It keeps an authenticated session as AES-256-GCM-encrypted device storage with the encryption key in iOS Keychain; it does not put a server administration key in the app. Supabase may process operational security and access logs under its service terms. No reader profile, verses, notes or study history are saved in the Tanakh database.

**Purchase data if the candidate is installed:** Apple handles billing; Tanakh Anew does not receive your payment card information. RevenueCat uses an app-generated anonymous customer ID and purchase/restore history to validate the exact Premium Study entitlement. It is initialized on iOS to check membership status even if you use only the free reader. The app does **not** send the optional Supabase/Apple account ID or email to RevenueCat and does not use RevenueCat for advertising or cross-app tracking. RevenueCat's [Apple privacy documentation](https://www.revenuecat.com/docs/platform-resources/apple-platform-resources/apple-app-privacy) says purchase history is collected for **app functionality and analytics** (including its subscription dashboard); this must be declared accurately in App Store Connect before release. Apple may show a different local price outside the United States; there is no free trial configured.

**Account deletion and billing:** A signed-in person can select **Membership → Delete Tanakh account**, then confirm. An authenticated Tanakh-only server function verifies their session and deletes their Supabase Auth account. This does not delete locally stored reading data, nor does it cancel an Apple subscription. To avoid further billing, separately cancel via Apple's subscription settings. Sign out removes this device's account session; it does not cancel the membership. Account-deletion support is available via the [support page](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-support.md), but do not post personal account information in a public issue.

The candidate is **not yet on TestFlight**. Before shipping it, its signed build, native Apple login, purchase, Restore and account deletion must be device-tested, and the App Store App Privacy answers updated to cover the actual Apple/Supabase account data and RevenueCat purchase history. This page does not imply those flows already passed.

## Support and sources

We do not sell reading data or use it for targeted advertising. If you contact support outside the app, the information you choose to provide is processed by your contact service. **Public GitHub issues are public; never post your email, private reading notes, account identifiers, passwords or payment information there.** See [Help & Support](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-support.md).

Tanakh Anew is an independent Jewish reading app; it is not affiliated with Sefaria, JPS or tanach.us. See its [text-edition sources](https://github.com/ChristopherSwofford418/app-policies/blob/main/tanakh-anew-sources.md).
