# Privacy Policy

**Last updated: January 8, 2026**

*Version 1.3 - Added anonymous usage statistics disclosure*

Anchor ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use the Anchor app.

## Information We Collect

### Account Information
- **Display name**: The name you choose to identify yourself to your accountability partner
- **Partner pairing code**: A unique code used to connect with your accountability partner

### Usage Data
With your permission (PACKAGE_USAGE_STATS), we collect:
- **App usage statistics**: Which apps you use and for how long
- **Blocked app attempts**: When you try to open a blocked app

This data is used to:
- Show you your own usage patterns
- Share usage summaries with your accountability partner (if connected)
- Enforce app time limits you set for yourself

### Device Information
- **Device tokens**: For sending push notifications
- **Accessibility service status**: Whether app blocking is enabled
- **Default launcher status**: Whether Anchor is set as your home screen

### Anonymous Usage Statistics
To understand how many people use Anchor and ensure the app is working properly, we automatically collect minimal, anonymous data once per day:
- **Random identifier**: A randomly generated ID that is not linked to you, your device, or any personal information
- **App status**: Whether Anchor is your default launcher and whether app blocking is enabled
- **App version**: Which version of Anchor you are using

This data is completely anonymous and cannot be used to identify you. It helps us count active users and monitor app health. This collection happens regardless of other privacy settings because it contains no personal information.

## Accessibility Service Usage

Anchor requires Android's Accessibility Service to provide its core app-blocking functionality. This section explains exactly how we use this permission.

### What the Accessibility Service DOES:
- Detects when you open an app (receives "window state changed" events)
- Checks if the app is on your blocked list or has exceeded its time limit
- Redirects you to your home screen if the app is blocked

### What the Accessibility Service does NOT do:
- Read any text on your screen
- Access passwords, messages, or personal content
- Record or transmit screen contents
- Collect any data beyond app package names
- Function when Anchor is uninstalled

**Technical details**: Anchor only listens for `TYPE_WINDOW_STATE_CHANGED` events and has `canRetrieveWindowContent` set to `false`, meaning it cannot read screen content even if it wanted to.

This permission is essential for the app to work—without it, Anchor cannot block apps or enforce time limits.

## How We Use Your Information

- Provide core app functionality (blocking apps, tracking usage)
- Enable accountability partner features
- Send notifications about partner requests and alerts

## Data Sharing

### With Your Accountability Partner
If you connect with a partner, they can see:
- Your display name
- Your app usage (last 7 days)
- Your blocked app attempts
- Whether accessibility service is enabled
- Whether Anchor is your default launcher

### Third-Party Services
We use Firebase (Google) for:
- **Cloud Firestore**: Storing your data securely
- **Firebase Cloud Messaging**: Sending push notifications

**We do NOT:**
- Sell your data to third parties
- Share your data with advertisers
- Use your data for targeted advertising

## Data Storage and Security

Your data is stored securely on Firebase servers (Google Cloud Platform). We implement appropriate security measures to protect against unauthorized access.

## Data Retention

- **Active accounts**: Data is retained while you use the app
- **Deleted accounts**: Data is deleted upon request
- **Usage data display**: The app shows usage from the last 7 days to you and your partner

## Your Rights

- **Access**: View all data we have about you (visible in the app)
- **Delete**: Request deletion of your account and all associated data
- **Disconnect**: Remove your accountability partner connection at any time

To delete your data:
1. Uninstall the app (local data is removed)
2. Contact us to request server data deletion

## Age Requirement

Anchor is intended for users 18 years of age or older. We do not knowingly collect information from anyone under 18. If you are under 18, please do not use this app.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of changes by updating the "Last updated" date.

## Contact Us

If you have questions about this Privacy Policy, please contact us at:
- **GitHub**: [github.com/hrweaver/anchor-legal](https://github.com/hrweaver/anchor-legal)
