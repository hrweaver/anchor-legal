# Anchor Privacy Policy

**Last Updated:** January 20, 2025 (Version 1.4)

Your privacy matters. This policy explains what data Anchor collects, why we collect it, and how you can control it.

---

## Summary

- We collect only what's needed to make Anchor work
- Your accountability partner can see your app usage (if you connect one)
- We don't sell your data or show you ads
- You can delete all your data at any time
- You can disconnect from your partner at any time

---

## Information We Collect

### Account Information
When you set up Anchor, we collect:
- **Display name**: So your partner knows who you are
- **Pairing code**: A unique 8-character code to connect with your partner

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

---

## How We Use Your Information

We use your data to:
- **Provide the service**: Connect you with your partner, sync your settings, send notifications
- **Enable accountability**: Share relevant data with your partner (see below)
- **Improve Anchor**: Fix bugs and understand usage patterns (anonymously)
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
| App usage data (past 7 days) | To support accountability |
| Blocked app attempts | To see what you're struggling with |
| Your app time limits | To see your goals |
| Accessibility service status | To verify blocking is active |
| Launcher status | To verify Anchor is your home screen |

**Your partner sees this data continuously while connected.**

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

## Data Retention

We keep your data only as long as needed:

| Data Type | Retention Period |
|-----------|-----------------|
| Account info (name, pairing code) | Until you delete your account |
| App usage data | 30 days rolling |
| Blocked attempt logs | 30 days rolling |
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
- **Consent**: For optional analytics (which you can decline during setup or withdraw anytime in Settings)
- **Legitimate interest**: For service security, fraud prevention, and improving Anchor

---

## Your Rights

You have the right to:

- **Access**: See what data we have about you
- **Deletion**: Delete your account and all associated data (Settings > Advanced > Delete My Data)
- **Portability**: Request your data in a machine-readable format
- **Correction**: Update your display name anytime
- **Withdraw consent**: Turn off analytics in Settings > Advanced
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

**Version 1.4 (January 20, 2025)**
- Added explicit partner consent disclosure
- Added data retention periods
- Added GDPR legal basis section
- Added international data transfer disclosure
- Added bug report data collection disclosure
- Added children's privacy section
- Clarified accessibility service limitations
