---
layout: default
title: Privacy & Support
---

# Privacy Policy

**Last Updated:** May 13, 2026

## Introduction

ReachDog for iOS respects your privacy. This Privacy Policy explains how information is handled when you use ReachDog on your iPhone.

✓ Your business cards, leads, and notes stay on your device. We do not sell, rent, or share your data.

## Information We Collect

ReachDog is designed to function primarily on your device.

**What we don't collect:**

- No usage analytics or tracking
- No advertising identifiers
- No location data
- No access to your device contacts, calendar, reminders, health, or financial data
- No third-party analytics or crash-reporting SDKs

**What we do receive when you sign in:**

When you sign in with **Apple** or **Google**, we receive a minimal profile — your name (if you choose to share it), your email address, and a unique user identifier. We do not receive your password, your contacts, or any other data from your Apple or Google account.

## Local Data Storage

All your leads, business card photos, notes, tags, events, custom statuses, templates, and generated email drafts are stored locally on your iPhone using Apple's secure on-device storage.

This includes:

- Lead contact details (name, company, email, phone, title, address)
- Business card photos you scan or upload
- Your notes, tags, events, and follow-up status
- AI-generated email drafts and saved templates
- App preferences
- Recently Deleted leads (kept on your device for up to 30 days so you can restore them, then permanently removed)

This data never leaves your device and is not accessible to us or any third parties.

## On-Device Processing

ReachDog performs **OCR (text recognition)** on business card images using Apple's Vision framework, entirely on your device. The images and the text extracted from them never leave your iPhone as part of the scanning step.

## AI Email Drafts

When you ask ReachDog to generate a follow-up email, the draft is produced from a small amount of context — the lead's name, company, job title, your tone selection, and your own notes about the lead.

On supported iPhones, this happens **entirely on your device** using Apple Intelligence — nothing leaves your iPhone for that draft.

On iPhones that do not support on-device Apple Intelligence, the same minimal context is sent over a secure HTTPS connection to a private service we operate solely to generate your draft, and the response is returned to your iPhone.

In both cases:

- We do not send the business card image
- We do not send your email address or your other leads
- Drafts and prompts are not retained on our side and are not used to train AI models
- You can edit the draft freely before sending

If you prefer not to use AI features, simply don't tap "Generate Follow-Up". The rest of the app works normally.

## Third-Party Services

ReachDog uses trusted services for sign-in and AI drafting. Each is subject to its own privacy policy:

- **Apple Sign In** — authentication
- **Google Sign-In** — authentication

We do not use advertising frameworks, analytics services, or tracking technologies.

## Security

- All network traffic uses HTTPS/TLS
- Authentication tokens are stored in the iOS Keychain, protected by your device passcode and Face ID / Touch ID
- The app uses only Apple-provided security primitives
- App Transport Security is enabled

Because your leads never leave your device, the attack surface is minimal by design.

## Children's Privacy

ReachDog is designed for business professionals. It does not knowingly collect information from children under 13.

## Account Deletion

You can delete your ReachDog account and all associated data at any time, directly from inside the app — no email, phone call, or website visit required.

**How to delete your account:**

1. Open the app and tap the **Settings** tab.
2. Scroll to the bottom and tap **Delete Account**.
3. Review the on-screen summary of the data that will be removed.
4. Type **DELETE** in the confirmation field to enable the destructive button.
5. Tap **Delete My Account**.

**What happens when you confirm:**

- **Sign in with Apple users:** ReachDog calls Apple's `/auth/revoke` endpoint with your stored refresh token, permanently revoking ReachDog's authorization on your Apple ID. ReachDog will no longer appear under *Settings → Apple ID → Sign in with Apple → Apps Using Apple ID*.
- **Sign in with Google users:** ReachDog calls Google's revocation endpoint, removing ReachDog from the apps connected to your Google account.
- **All on-device data is permanently deleted:** leads, notes, generated email drafts, business card images, templates, tags, profile, and preferences.
- **iOS Keychain and app preferences are wiped.**
- You are returned to the onboarding screen and can sign in fresh as a new user at any time.

The action is **immediate and cannot be undone.**

## Other Ways to Remove Data

- Deleting ReachDog from your iPhone removes all local data immediately.
- Signing out from Settings ends your session but does not delete your data — use **Delete Account** above for full removal.

## Your Rights

Depending on where you live (EU, UK, California, etc.), you may have rights under GDPR, UK GDPR, or CCPA, including access, correction, portability, and deletion of your personal information. To exercise any of these rights, contact us at the email below.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected by updating the "Last Updated" date at the top of this page.

---

# Support

We're here to help you get the most out of ReachDog.

## 📧 Contact Us

For support inquiries, feedback, or suggestions:

[Send Email](mailto:layth@Motionpexels.com)

We typically respond within 24–48 hours.

💡 **Pro Tip:** For the sharpest OCR results, place the business card on a flat, well-lit, contrasting surface before you scan.

## Frequently Asked Questions

### How do I scan a business card?

Open the app, tap **Scan** in the bottom tab bar, then tap **Take Photo** to use the camera or **Upload Image** to pick from your library. ReachDog auto-detects the card edges, extracts the contact details, and takes you to a review screen where you can edit anything before saving.

### The OCR missed a field. Can I fix it?

Yes. On the Review Contact screen every field is editable. Tap the field, type the correction, and tap **Save Lead**.

### Does ReachDog work offline?

Mostly yes. Scanning, OCR, saving, editing, tagging, browsing, and CSV export all work offline. The only feature that needs internet is the AI-generated follow-up emails.

### Where is my data stored?

All your leads, notes, card images, and templates are stored on your iPhone only. If you delete the app, the data is deleted with it. We don't keep copies on a server.

### How do I export my leads?

Go to **Settings → Data → Export CSV**. ReachDog shares a CSV file you can save to Files, email, or open in Excel, Numbers, or Google Sheets.

### How does the AI email draft work?

Open any lead, tap **Generate Follow-Up**, choose a tone and length, and ReachDog generates two variations you can edit, save as a template, or open in Mail, Gmail, Outlook, or Messages.

### Can I change the email app that opens?

Yes. **Settings → Email** lets you pick your default — Apple Mail, Gmail, Outlook, or Messages. If your chosen app isn't installed, ReachDog will offer to take you to the App Store to install it.

### How do I delete a lead?

You have two ways:

- **From the Leads list:** swipe left on the lead and tap **Delete**.
- **From the lead's profile:** open the lead and tap the **trash** icon at the top-right, then confirm.

Either way, the lead moves to **Recently Deleted** (Settings → Recently Deleted) where it stays for up to 30 days so you can restore it. After 30 days it is permanently removed from your iPhone.

### How do I delete my account?

Open **Settings → Delete Account** (red button at the bottom of the Settings tab), type **DELETE** to confirm, and tap **Delete My Account**. ReachDog immediately revokes its authorization on your Apple or Google account and erases all of your on-device data — leads, notes, drafts, card images, templates, tags, profile, and preferences. The action is immediate and cannot be undone.

### Which iPhones are supported?

ReachDog is iPhone-only and supports iPhones running iOS 17 or newer. iPhones on iOS 26+ get an upgraded OCR engine for even better recognition. Recent iPhones that support Apple Intelligence also generate AI follow-up emails fully on-device.

### Do you collect analytics or track me?

No. We don't use analytics SDKs, advertising identifiers, or cross-app tracking.

### Scan button is greyed out

Your device doesn't support the document scanner. Use **Upload Image** instead.

### "Camera access denied" or "Photos access denied"

Go to **iOS Settings → ReachDog** and enable the permission, then restart the app.

### Sign-in fails

Check your internet connection, then try signing out and back in. If it keeps happening, email us.

### AI follow-up says "couldn't generate email"

Usually a temporary network issue. Wait a moment and try again.

### App crashes on launch

Force-quit (swipe up from the app switcher), reopen. If it persists, restart your iPhone. Still crashing? Email us with your iPhone model and iOS version.

## Feedback & Feature Requests

We read every email. If you have an idea that would make ReachDog better, send it to the address above with the subject line starting with **"Feature:"**.

---

## Contact

Email: [layth@Motionpexels.com](mailto:layth@Motionpexels.com)

© 2026 ReachDog. All rights reserved.
