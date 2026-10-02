# Milarah · מילארה — Privacy Policy

**Updated October 2, 2026.** Milarah is in pre-release preparation; it is not publicly available on the App Store. This policy describes the current iOS build candidate and may be updated if the tested build changes before release.

## Child reading stays on the device

Milarah offers adult-guided Hebrew reading cards in English or Hebrew. The chosen guide language, completed-lesson identifiers, and welcome state are stored on the device. The free alphabet starter does not require a child account or an internet connection. We do **not** ask children for their name, age, email, location, photos, voice, or school information. The app does not upload a child profile, reading progress, lesson answers, or reading analytics to our backend. Erasing local progress in the grown-up area deletes those on-device completion marks; deleting the app may also remove them. There is no cloud progress sync or recovery guarantee.

## Optional adult Apple account

Only the grown-up area offers optional **Sign in with Apple**. If an adult uses it, Apple issues an identity token that the app exchanges with **Supabase**, our separate authentication provider for Milarah. Depending on the adult's Apple email-sharing choice, Supabase may store an email address or private relay email, a provider identifier, an account user ID, and the account/session information necessary to sign in. The local session is encrypted with a device-held key. Supabase may record authentication and security events and associated technical connection details such as IP address and user-agent information. This data is used for adult account functionality and security, **not** child profiling, ads, cross-app tracking, or sale of information. Reading progress does not become synced merely by signing in.

An adult can sign out in the app, or choose **Delete adult account** from the grown-up area. The deletion request is checked against the current authenticated adult and removes that Supabase Auth user. It does not erase the child's locally stored reading progress and does not cancel an Apple subscription. If an adult cannot reach the in-app control, they can request help using [Milarah support](milara-support.md) without putting personal information in a public issue. Provider security records may be retained according to Supabase's operational and legal requirements; we do not promise an instant deletion of every infrastructure log.

## Optional Apple subscription

The free alphabet starter remains free. A grown-up may separately choose a **weekly, auto-renewing Apple subscription** for expanded vowel/word lessons and a reordered practice mix. Apple handles payment and subscription management; the app checks the active Apple StoreKit entitlement to unlock the expanded library and supports Restore Purchases. Milarah does not receive or store payment-card numbers. The optional adult Apple-login account is not needed for Apple purchases or restore. To cancel, use the Apple Account subscription settings; deleting an account or the app does not cancel billing. No free trial is promised.

## Other practices and contact

This build candidate has no advertising or third-party analytics SDK and does not request location, contacts, camera, photo library, microphone, or health data. It uses network access for optional adult authentication and Apple's subscription services; technical requests may be handled by Apple and Supabase under their respective terms and privacy practices. For questions or account deletion assistance, see [Milarah support](milara-support.md). Public support issues must **not** contain a child's name, age, reading information, passwords, contact details, or other personal information. We will revise this policy if the actual released app's data practices change.
