# Anchor Privacy Policy

**Last Updated:** August 2, 2026 (Version 1.9)

Your privacy matters. This policy explains what data Anchor collects, why we collect it, and how you can control it.

---

## Summary

- We collect only what's needed to make Anchor work
- Your accountability partner sees whether your protection is set up and holding, and the requests you send them. They do not see your app usage in current versions of Anchor
- We don't sell your data or show you ads
- You can delete all your data at any time
- You can disconnect from your partner at any time

---

## Information We Collect

### Account Information
When you set up Anchor, we collect:
- **Display name**: So your partner knows who you are
- **Pairing code**: A unique 8-character code to connect with your partner
- **Email address and password** (accountability partner mode only): If you connect
  with a partner, you create an account using an email address and password. This
  keeps your partnership securely tied to you and working across devices. Solo use
  does not require an account. Authentication is handled by Google Firebase; we
  never store your password in readable form. You can delete your account and all
  associated data at any time (see [Your Rights](#your-rights)).

### App Usage Data (With Your Permission)
If you grant usage stats permission, we collect:
- Which apps you use and for how long
- When you attempt to open blocked apps
- Your self-imposed app time limits

This data helps you and your partner track progress toward your digital wellness goals.

### Device Information
We collect basic device information to make Anchor work:
- **FCM token**: To send you push notifications
- **Accessibility service status**: Whether app blocking is enabled
- **Launcher status**: Whether Anchor is your home screen

### Diagnostic Data
When you submit a bug report through the app, we collect:
- Your description of the issue
- Device model and Android version
- App version and mode (solo/partner)
- Recent app events (last 100 events, for debugging)
- A random 8-character reference ID

This diagnostic data is used solely to identify and fix issues. It is not shared with your accountability partner or any third parties.

### Anonymous Statistics
We automatically collect minimal anonymous data daily to understand how many people use Anchor:
- A random identifier (not linked to your account)
- App mode (solo or partner)
- Whether blocking is enabled
- App version
- Date

This data is completely anonymous and cannot be used to identify you.

### Product & Usage Analytics
To understand how Anchor is used, to improve it, and to help us reproduce and fix problems you
report, we record certain **events** linked to your account identifier. Examples include: daily
active use, onboarding progress, which screens you visit within the Anchor app, when you block or
request access to an app, partner requests and approvals, when Anchor notifications arrive and
what you do with them (open, approve, deny), settings changes such as turning blocking on or off,
and whether a sign-in attempt succeeded or failed. These are **behavioral events about your use of Anchor itself, not the
content of your other apps, messages, or screen**. We keep them to analyze trends over time and to
support you when something goes wrong. **When you delete your account, we irreversibly anonymize
these events** by stripping your identifiers so they can no longer be tied to you, while retaining
only aggregate, non-identifying data.

**You can turn this off.** On Android, Settings > Advanced > Share Anonymous Usage Data. On
iPhone, that switch arrives in an upcoming release; until then, email
[support@anchorph.one](mailto:support@anchorph.one) and we will switch it off for your
account. Turning analytics off does not change how blocking, limits, or partner approvals
work.

---

## How We Use Your Information

We use your data to:
- **Provide the service**: Connect you with your partner, sync your settings, send notifications
- **Enable accountability**: Share relevant data with your partner (see below)
- **Improve Anchor**: Fix bugs and analyze how Anchor is used to improve it (see *Product & Usage Analytics* above)
- **Communicate**: Send push notifications about partner requests and alerts

We do NOT:
- Sell your data to anyone
- Share your data with advertisers
- Use your data for targeted advertising
- Read the content on your screen

---

## Accountability Partner Data Sharing

### What You Share With Your Partner

By entering a partner's pairing code and completing the connection, you explicitly consent to share the following with your partner in real-time:

| Data | Why It's Shared |
|------|-----------------|
| Your display name | So they know who you are |
| Setup status (blocking on or off, Screen Time or accessibility access, whether Anchor is your home screen, last check-in) | To verify your protection is set up and holding |
| The requests you send them, and their outcomes | So they can approve or deny, and see recent activity between you |
| Your app time limits and schedules | To see the commitments you set |

Anchor's partner view is built around accountability, not surveillance. Your partner sees the state of your setup and what you choose to ask them. They do not see which apps you use, for how long, or which blocked apps you tried to open.

**Transition note:** app usage and blocked-attempt data are still collected (see App Usage Data above) and were shown to partners in versions of Anchor before July 2026. Partners on older versions may still see them until they update. A future update will stop syncing this data entirely, and this policy will be updated again when it does.

### What Your Partner CANNOT See
- The content of your messages or apps
- Your location
- Your contacts
- Your photos
- Anything you type

### Disconnecting
You may disconnect from your partner at any time through Settings. Disconnecting:
- Immediately stops all data sharing
- Removes your partner's access to your usage data
- Does not require your partner's permission
- Allows both of you to continue using Anchor independently

---

## The Accessibility Service

### What It Does
Anchor's accessibility service detects when you open an app and checks if that app is allowed. If not, it redirects you back to your home screen.

### What It Does NOT Do
- Read any text on your screen
- Access your messages, emails, or personal content
- Record what you type
- Take screenshots
- Access your passwords or private information

### Technical Details
The accessibility service only receives these events:
- `TYPE_WINDOW_STATE_CHANGED`: Detects which app opened
- Package name: The technical identifier of the app (e.g., "com.instagram.android")

We set `canRetrieveWindowContent` to `false`, which means we technically cannot access screen content even if we wanted to.

---

## On iPhone: Apple Screen Time

On iOS, Anchor does not use an accessibility service. Blocking is built on Apple's Screen Time
framework, which is designed so that apps like Anchor never learn which apps you selected.

- When you choose apps to block or keep open, Apple gives Anchor **opaque tokens**, not app names.
  Anchor cannot read, store, or transmit the names of the apps you selected.
- The only time we know an app's name on iOS is when **you type it yourself**, for example when
  naming an app in a request so your partner knows what they are approving.
- Per-app usage numbers on iOS are rendered inside an Apple-sandboxed report on your device and
  are not readable, stored, or synced by Anchor.
- You can revoke Anchor's Screen Time access at any time in iOS Settings.

---

## Data Retention

We keep your data only as long as needed:

| Data Type | Retention Period |
|-----------|-----------------|
| Account info (email, name, pairing code) | Until you delete your account |
| App usage data (partner-visible) | 30 days rolling |
| Blocked attempt logs (partner-visible) | 30 days rolling |
| Product & usage analytics events | Retained while your account exists; irreversibly anonymized when you delete your account |
| Partner connection | Until you disconnect |
| App time limits | Until you remove them |
| Bug reports | 90 days |
| Feature requests | Until implemented or declined |
| Anonymous statistics | 1 year |

When you delete your account, all personally identifiable data is removed within 30 days.

---

## Data Storage and Security

### Where Your Data Is Stored
Your data is stored on Firebase (Google Cloud) servers in the United States. Firebase provides:
- Encryption in transit (HTTPS/TLS)
- Encryption at rest
- SOC 1, SOC 2, and SOC 3 compliance
- ISO 27001 certification

### International Data Transfers
For users in the European Economic Area (EEA), United Kingdom, or Switzerland: your data is transferred to the United States. This transfer is protected by:
- Google's Standard Contractual Clauses
- Firebase's compliance with applicable data protection frameworks

---

## Legal Basis for Processing (EEA Users)

If you're in the European Economic Area, we process your data based on:

- **Contract performance**: To provide the Anchor service you requested when you created an account
- **Consent**: For optional analytics. You can decline during setup on Android, and withdraw at any time (see *Withdraw consent* under Your Rights for how, on each platform)
- **Legitimate interest**: For service security, fraud prevention, and improving Anchor

---

## Your Rights

You have the right to:

- **Access**: See what data we have about you
- **Deletion**: Delete your account and all associated data (Settings > Advanced > Delete My Account). See the [account deletion instructions](https://github.com/hrweaver/anchor-legal/blob/main/ACCOUNT_DELETION.md).
- **Portability**: Request your data in a machine-readable format
- **Correction**: Update your display name anytime
- **Withdraw consent**: Turn off analytics in Settings > Advanced on Android. On iPhone this switch arrives in an upcoming release; until then, email [support@anchorph.one](mailto:support@anchorph.one) from your account email and we will switch analytics off for your account within a few days. Either route stops collection entirely, and blocking works exactly the same with analytics off.
- **Disconnect**: Leave your accountability partnership instantly
- **Restriction**: Request we limit how we process your data
- **Object**: Object to processing based on legitimate interest

To exercise these rights, use the in-app options or contact us at the address below.

---

## Children's Privacy

Anchor is intended for users 18 years of age or older. We do not knowingly collect data from anyone under 18.

If you are a parent or guardian and believe your child has provided us with personal information, please contact us. If we discover we have collected data from someone under 18, we will delete it promptly.

**Note for parents**: Anchor is not a parental control app. If you want to monitor or limit a minor's phone use, please use dedicated parental control solutions like Google Family Link.

---

## Third-Party Services

Anchor uses these third-party services:

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Firebase (Google) | Data storage, authentication, push notifications | [Google Privacy Policy](https://policies.google.com/privacy) |
| Firebase Crashlytics | Crash reporting | [Crashlytics Data Processing](https://firebase.google.com/support/privacy) |
| Firebase Analytics | Anonymous usage analytics (optional) | [Google Analytics Privacy](https://support.google.com/analytics/answer/6004245) |

We do not use any advertising SDKs or sell data to third parties.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. When we make significant changes:
- We'll update the "Last Updated" date at the top
- For major changes, we'll notify you in the app

Continued use of Anchor after changes constitutes acceptance of the updated policy.

---

## Contact Us

Questions about this Privacy Policy?

- **GitHub**: [github.com/hrweaver/anchor-legal](https://github.com/hrweaver/anchor-legal)
- **Email**: Create an issue on our GitHub repository

---

## Summary of Recent Changes

**Version 1.9 (August 2, 2026)**
- Made the analytics opt-out accurate per platform. The switch has always existed on Android
  (Settings > Advanced); on iPhone it arrives in an upcoming release. Until it does, emailing
  support turns analytics off for your account, and we honor that immediately on our servers
  rather than waiting for an app update. Blocking, limits, and partner approvals are unaffected
  either way.

**Version 1.8 (July 26, 2026)**
- Redesigned partner sharing: partners now see your setup status, your requests, and your
  commitments. Current versions of Anchor no longer show partners your app usage or blocked-app
  attempts. Added a transition note covering older app versions while usage syncing is wound down.

**Version 1.7 (July 26, 2026)**
- Expanded the Product & Usage Analytics examples to name the event types we record: screens
  visited within Anchor, notification delivery and responses, settings changes, and sign-in
  attempt outcomes. Same rule as before: events about your use of Anchor, never the content of
  your other apps.
- Added an iPhone section: iOS blocking uses Apple's Screen Time framework, which by design keeps
  the names of your selected apps hidden from Anchor.

**Version 1.6 (July 16, 2026)**
- Disclosed product & usage analytics (behavioral events linked to your account, used to improve Anchor)
- Clarified that analytics events are retained for trend analysis and **irreversibly anonymized on account deletion**

**Version 1.4 (January 20, 2025)**
- Added explicit partner consent disclosure
- Added data retention periods
- Added GDPR legal basis section
- Added international data transfer disclosure
- Added bug report data collection disclosure
- Added children's privacy section
- Clarified accessibility service limitations
