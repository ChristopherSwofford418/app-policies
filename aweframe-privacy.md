# Aweframe — Privacy Policy

**Updated October 2, 2026.** This policy covers Aweframe 1.0.0 internal TestFlight builds, including build 2 with an optional Apple account and weekly Premium subscription. Aweframe has **not** been approved or released on the public App Store.

## Your private journal

Your moments, captions, selected photo copies, categories and onboarding preferences are stored **on this device**, not in your Aweframe account. Daily invitations use built-in prompts and your locally saved preferences; your journal is not sent to an AI service or synchronized across devices. An optional Apple account is **not a backup**. Removing the app may remove its local journal and app-owned photo copies; an independent iPhone backup may depend on your Apple device settings.

Aweframe requests camera access only when you choose the camera and opens the system photo selector when you choose a photo. It does not scan your photo library in the background or request location or microphone permission. When you deliberately share a moment, the iOS share sheet passes the selected content to the destination you choose; that destination's policies apply.

## Optional Sign in with Apple

If you choose **Sign in with Apple**, Apple provides Aweframe with an identity token and may provide your email address or Apple private-relay address, depending on your Apple choice. The token is sent to a **dedicated Aweframe Supabase authentication project**, which creates an account identifier and may retain that email address. Supabase processes authentication events and technical security data, including an account identifier and potentially an IP address and user-agent information in authentication audit logs. These data are used to operate and secure the account, **not** for advertising or cross-app tracking. [Supabase's Auth audit-log documentation](https://supabase.com/docs/guides/auth/audit-logs) describes its event fields, and [Supabase's privacy notice](https://supabase.com/privacy) describes the provider's practices.

The app encrypts its locally cached account session, protecting its encryption key in the iPhone Keychain. Signing out removes that local session, not your on-device journal. **Delete Aweframe account** requests removal of your authenticated Supabase account identity; your locally saved journal remains on the device unless you separately delete its moments or remove the app. Provider security logs may remain under the provider's retention rules. Account deletion does not cancel an Apple subscription. If account deletion fails, the app should show an error rather than claiming it succeeded; contact support using the non-sensitive route below. Do not send us journal entries or identity tokens.

## Optional Apple subscription

Free users can write and keep text-only moments and use general reflection invitations. The optional **Aweframe Premium** auto-renewable weekly subscription unlocks creating photo moments from the camera/library and locally tailored invitations while an active Apple entitlement is verified. Purchase, renewal, cancellation and restore use Apple's StoreKit and your App Store account. Apple shows the localized price before confirmation; the U.S. starting price is $2.99 per week, with no free trial in the current draft. Aweframe does **not** receive your payment-card number. Your existing moments remain readable if a subscription ends. You can manage or cancel the subscription through Apple's subscriptions settings.

## Retention and your choices

You can edit or delete individual moments. Deleting a moment removes its journal record and attempts to delete its app-owned photo copy; the original photo in your library is not deleted. Deleting the account does not erase the local journal, and uninstalling the app is not a reliable way to cancel an Apple subscription. No advertising tracker, cloud journal sync, Firebase integration, Mixpanel analytics or health diagnosis is built into this candidate.

For non-sensitive help, visit the [Aweframe support page](https://github.com/ChristopherSwofford418/app-policies/blob/main/aweframe-support.md). Its linked GitHub issue route is **public**: never post private photos, captions, email addresses, access tokens, receipts, financial details or precise locations there. We will update this policy if the app's collection or functionality changes.
