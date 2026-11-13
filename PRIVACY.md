# Privacy Policy
_Effective 13 November 2026_

Plume: AI Email ("Plume") is an email app for iPhone. This policy explains what happens to your information when you use it. In short: Plume has no ads or tracking, and no servers that see or store your mail. If you sign in with Google or Microsoft, Plume keeps an encrypted backup of your email accounts so a new iPhone can get them back. Your mail travels between your iPhone and your email provider, and the text of emails is sent to Microsoft's Azure OpenAI Service only to produce the AI features you see in the app.

## Information Plume handles

- **Your email account.** Your address, server settings, and either a sign-in token (Outlook, via Microsoft's sign-in page) or an app password you enter. Tokens and passwords are stored in the iOS Keychain on your device and, if you have a Plume account (see Account backup), in your encrypted backup.
- **Your email.** Plume downloads messages, attachments and folders directly from your provider over encrypted IMAP and sends mail over SMTP. Copies are kept on your iPhone so the app opens quickly and works offline.
- **Your settings.** Preferences such as your name, VIPs, blocked senders, templates and reminders are stored on your device.

## AI processing
To sort mail, write one-line summaries, suggest replies, translate, draft text you ask for, summarise attachments, and find events, bills and receipts, Plume sends the relevant email text to Microsoft's Azure OpenAI Service. That text is used only to return the result to your device. Under Microsoft's terms for the service, it is not used to train models. Plume does not keep a copy anywhere other than your iPhone. You can turn off automatic sorting in Settings; other AI features run only when you open an email or tap an AI button.

## Instant alerts (optional, Outlook accounts)
If you turn on Instant alerts in Settings, Microsoft notifies a small Plume alert service when new mail arrives in your Outlook inbox, and that service asks Apple to show an alert on your iPhone. The service stores only your iPhone's push address, a random code that links the two, and when it was last updated. It never receives your mail, address, password or sign-in token: your iPhone reads the sender and subject directly from Microsoft to fill in the alert. Turning Instant alerts off, or signing out of the account, deletes its entry.

## Account backup (Plume account)
When you add a Gmail or Outlook account, Plume uses that Google or Microsoft sign-in to create your Plume account. Plume then backs up the email accounts you've added to Plume: their addresses, server settings, the names you gave them, and their sign-in tokens or app passwords. Signing in with the same Google or Microsoft account on another iPhone, or after reinstalling, restores them.

- Plume receives only proof of who signed in (a signed ID token with your Google or Microsoft account ID and email address). It never sees your Google or Microsoft password.
- Backed-up sign-ins are encrypted (AES-256-GCM) on Plume's servers in Microsoft Azure in the United Kingdom, and are sent only to your devices over an encrypted connection.
- Your mail itself is never backed up or stored by Plume.
- Signing out of an account removes it from the backup. **Settings › Privacy & security › Delete Plume Account & Backup** deletes your Plume account and everything in the backup at once.

## What Plume does not do

- No advertising, analytics, or tracking across apps or websites.
- No selling or sharing of your information with data brokers.
- No Plume servers storing your mail. Plume's servers hold only the encrypted account backup above and push addresses for Instant alerts.

## Third parties

- **Your email provider** (for example Microsoft or Apple), which stores and delivers your mail under its own privacy policy.
- **Microsoft Azure OpenAI Service** , which processes email text for AI features as described above.
- **Apple Push Notification service and Microsoft Azure**, which deliver Instant alerts and host Plume's servers (the account backup and alert service).
- **Google and Microsoft sign-in**, which confirm who you are when you create or use your Plume account.
- **Unsubscribe pages** of senders, which open inside Plume only when you tap Unsubscribe.

## Permissions
Notifications (new-mail alerts and reminders), Calendar (adding events, only when you confirm them in the iOS calendar editor), and Face ID (optional app lock). Each is asked for when first needed and can be changed in iOS Settings.

## Keeping and deleting your information
Signing out of an account in Plume deletes its sign-in details and its mail stored on your iPhone, and removes it from your account backup. Deleting your Plume account in Settings erases the backup from Plume's servers. Deleting the app removes everything Plume stored. Mail on your provider's servers is not affected.

## Children
Plume is not directed at children under 13.

## Changes
If this policy changes, the new version will be posted on this page with a new effective date.

## Contact
Questions about privacy: [open an issue](https://github.com/xLuciferSx/plume-legal/issues/new).
