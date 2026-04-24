---
layout: default
title: Privacy Policy
---

# Privacy Policy

**Last updated:** April 24, 2026
**Effective date:** April 24, 2026

ReachDog ("we", "our", or "the app") is a sales lead management application for iOS. This Privacy Policy explains what information we collect, how we use it, and the choices you have. By using ReachDog, you agree to the practices described below.

We designed ReachDog to be **privacy-first**: the vast majority of your data never leaves your device.

---

## 1. Information We Collect

### 1.1 Information you provide when signing in

When you sign in with **Apple** or **Google**, we receive a minimal profile:

- Your full name (if you choose to share it)
- Your email address
- A unique user identifier issued by Apple or Google

We do **not** receive your password, your contacts, your calendar, or any other data from your Apple or Google account.

### 1.2 Information you create inside the app

Everything you enter or scan inside ReachDog — business card photos, lead contact details, notes, tags, AI-generated email drafts, and email templates — is stored **locally on your device** using Apple's SwiftData framework. This data is **not uploaded to our servers**.

### 1.3 Information for AI features

When you ask ReachDog to generate a follow-up email, we send only the **minimum text context needed to produce the draft** (for example, the lead's name, company, job title, your tone selection) to our backend proxy, which forwards it to an AI provider (currently Groq running Llama 3.3). We do **not** send the business card image, your email address, other leads, or your full contact list.

This text is processed in real time to generate the draft and is **not retained** by us or used to train AI models.

### 1.4 Information we do **not** collect

- We do not collect your location
- We do not access your device contacts, calendar, reminders, health data, or financial data
- We do not track you across other apps or websites
- We do not use advertising identifiers
- We do not use third-party analytics or crash-reporting SDKs
- We do not sell, rent, or trade your data to anyone

---

## 2. How We Use Your Information

We use the limited information described in Section 1 to:

- Authenticate you and keep you signed in
- Generate AI follow-up email drafts when you request them
- Provide customer support if you contact us

That's it.

---

## 3. On-Device Processing

ReachDog performs **OCR (optical character recognition)** on business card images using **Apple's Vision framework, entirely on your device**. The images and the text extracted from them never leave your iPhone as part of the OCR step.

---

## 4. Data Storage

- **On your device:** Leads, notes, business card images, tags, templates, and generated emails are stored in SwiftData on your iPhone. When you delete the app, this data is deleted with it.
- **Authentication tokens:** Session tokens from Apple/Google Sign-In are stored in the iOS Keychain, which is protected by your device passcode and Face ID / Touch ID.
- **Our servers:** We do not store your leads, card images, notes, or email drafts on our servers. We use Supabase (our backend provider) only as a secure proxy for authentication sessions and the AI draft endpoint.

---

## 5. Third-Party Services

ReachDog uses the following third-party services, each subject to its own privacy policy:

| Service | Purpose | Privacy Policy |
|---|---|---|
| Apple Sign In | Authentication | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| Google Sign-In | Authentication | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Supabase | Auth session + AI proxy | [supabase.com/privacy](https://supabase.com/privacy) |
| Groq | AI email drafting | [groq.com/privacy-policy](https://groq.com/privacy-policy/) |

---

## 6. Your Choices and Rights

You control your data:

- **Delete your data:** Delete the app from your iPhone. All on-device data is removed immediately.
- **Export your leads:** Use the built-in CSV export feature in Settings.
- **Sign out:** Sign out from Settings at any time.
- **Delete your account:** Email us at the address in Section 10 and we will remove your authentication record.
- **Opt out of AI features:** You can simply not use the "Generate Follow-Up" feature. The rest of the app works normally.

Depending on where you live (EU, UK, California, etc.), you may have additional rights under GDPR, UK GDPR, or CCPA, including the right to access, correct, port, or delete your personal information. To exercise any of these rights, contact us at the email below.

---

## 7. Children's Privacy

ReachDog is intended for business use by adults (17+). We do not knowingly collect information from children under 13. If you believe a child has provided us with information, contact us and we will delete it.

---

## 8. Security

We use industry-standard measures to protect your information:

- All network traffic uses HTTPS/TLS
- Authentication tokens are stored in the iOS Keychain
- The app ships with no custom cryptography and uses only Apple-provided security primitives (App Transport Security is enabled)
- Our backend is hosted on Supabase's managed infrastructure

No system is perfectly secure, but since your leads never leave your device, the attack surface is minimal by design.

---

## 9. Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last updated" date at the top and, where appropriate, provide notice inside the app or on this page. Continued use of ReachDog after changes means you accept the updated policy.

---

## 10. Contact Us

Questions, requests, or concerns about this Privacy Policy or your data?

**Email:** hamud313@gmail.com

We aim to respond within 2 business days.

---

[← Back to home](index.html) · [Support](support.html)
