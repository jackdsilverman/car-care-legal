---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy for Car Care

**Effective date:** 2026-05-19
**Last updated:** 2026-05-19

This Privacy Policy explains how Jack Silverman ("we", "us") collects, uses, and shares information when you use the **Car Care** mobile application (the "App"). By using the App you agree to this Policy.

If you have questions about this Policy or how your data is handled, contact us at **[CONTACT EMAIL — please fill in]**.

---

## 1. Summary

- The App is a personal maintenance log for your vehicles. Most data stays on your device.
- We require a sign-in (Apple, Google, or email/password) so your records can sync to your account.
- We store your records on Supabase servers (our cloud backend) so you can access them across devices and survive a reinstall.
- We do **not** sell your personal information. We do **not** show you ads. We do **not** use third-party analytics, advertising SDKs, or tracking technologies.

---

## 2. Information we collect

### 2.1 Account information

When you create an account, we collect:

- **Email address** — used as your account identifier and for password resets.
- **Apple Sign In identifier and (if shared by Apple) name and relay email** — when you sign in with Apple. Apple may give you a private-relay address; we only see the relay address.
- **Google account email and (if shared by Google) name** — when you sign in with Google.

Authentication is handled by **Supabase, Inc.** Passwords are never visible to us; Supabase stores them as salted hashes.

### 2.2 Vehicle and maintenance data

Information you enter into the App about your vehicles and their service history:

- Vehicle year, make, model
- Purchase price and purchase mileage (optional)
- Free-text notes you write about a vehicle or service visit
- Service records: date, mileage, cost, service type(s), notes
- Parts catalog entries: name, brand, part number, category, notes
- Photos you attach to records: receipt images and "work photos" of the service

Photos and other record data are stored on your device by default. If you upgrade to Pro and cloud uploads are enabled, photos are also uploaded to a private Supabase Storage bucket and are scoped to your account ID.

### 2.3 Purchase information (when you upgrade to Pro)

Pro purchases are processed by **Apple App Store** (iOS) or **Google Play** (Android), and — once the integration ships — relayed to us via **RevenueCat, Inc.** for entitlement management.

- We receive: an anonymous purchase token, the product purchased (Annual or Lifetime), and entitlement status (active / cancelled / expired).
- We do **not** receive your full payment-card number, billing address, or other payment credentials. Those stay with Apple, Google, and their payment processors.

### 2.4 Technical information

The App connects to a small number of external services to function. The information shared with each is the minimum necessary to provide the feature:

| Service | Purpose | Data shared |
|---|---|---|
| Supabase (auth, database, storage) | Account, record sync, photo storage | Account credentials, vehicle/record/parts data, photos (Pro + uploads enabled) |
| Apple Sign In | Authentication via Apple ID | Handled by Apple per their privacy practices |
| Google Sign In (via OAuth) | Authentication via Google account | Handled by Google per their privacy practices |
| NHTSA vPIC API (US government) | Populating the year / make / model dropdowns when adding a vehicle | Your queries (year, make) — no account identifier is sent |
| RevenueCat *(planned, not yet shipped)* | Subscription entitlement management | Anonymous user ID + purchase tokens |
| Apple App Store / Google Play | Processing Pro purchases | Handled by the store per their privacy practices |

The App does **not** include analytics, crash-reporting, advertising, or tracking SDKs.

### 2.5 Information we do NOT collect

- We do not collect your precise or coarse location.
- We do not collect your contacts, calendar, microphone, or motion data.
- We do not access photos on your device except images you explicitly pick or capture for a service record.
- We do not collect device identifiers for advertising (IDFA / AAID).
- We do not use cookies or web tracking pixels.

---

## 3. How we use your information

We use your information only to:

1. Operate the App — authenticate you, store and display your records, sync across your devices.
2. Process Pro purchases and verify entitlement.
3. Maintain security — investigate suspected fraud, account takeover, or abuse.
4. Comply with legal obligations.

We do not use your data to train AI models. We do not profile you for marketing. We do not target ads.

**Legal bases (EU / UK GDPR):** processing is based on (a) **performance of a contract** when you use the App (Art. 6(1)(b)) for account, sync, and purchases; (b) **legitimate interests** (Art. 6(1)(f)) for security and fraud prevention; and (c) **legal obligation** (Art. 6(1)(c)) where applicable.

---

## 4. How we share your information

We do not sell or rent your personal information. We share it only with:

- **Service providers** (sub-processors) acting on our behalf and bound to confidentiality: Supabase, Apple, Google, and (when shipped) RevenueCat. Each is listed in the table in Section 2.4.
- **Law enforcement or regulators** if required by valid legal process, or to protect rights, safety, or property.
- **A successor entity** in connection with a merger, acquisition, or sale of assets — in which case we will provide notice before your data is transferred and becomes subject to a different policy.

We do not share data with advertising networks.

---

## 5. International data transfers

Supabase data may be processed in regions outside your country, including the United States. Where required by EU / UK law, transfers rely on the European Commission's Standard Contractual Clauses (SCCs) or equivalent safeguards offered by the relevant sub-processor.

---

## 6. Data retention

- **Account and records:** retained while your account is active. You can delete individual vehicles, records, parts, and photos at any time from within the App.
- **Account deletion:** you can request full deletion of your account and all associated data by emailing **[CONTACT EMAIL — please fill in]**. We will delete your data within 30 days of a verified request, except where we are legally required to retain it (e.g. financial records relating to a Pro purchase).
- **Purchase records:** retained as required by applicable tax and consumer-protection law (typically up to 7 years).
- **Backups:** copies in routine backups may persist for up to 90 days after deletion before being purged.

---

## 7. Security

We protect your information with industry-standard safeguards:

- TLS encryption in transit between the App and our servers.
- Encryption at rest for data stored in Supabase.
- Photos in cloud storage live in a **private** bucket; access is gated by short-lived signed URLs scoped to your account.
- Passwords are stored as salted hashes by Supabase — we cannot see them.

No system is 100% secure. If we become aware of a security incident affecting your personal information, we will notify you as required by applicable law.

---

## 8. Your rights

### 8.1 Everyone

You can, at any time:

- View, edit, or delete your vehicles, records, parts, photos, and notes from within the App.
- Sign out of your account.
- Email us to request a copy or deletion of your account data.

### 8.2 EU / UK residents (GDPR / UK GDPR)

You have the right to:

- **Access** the personal data we hold about you.
- **Rectify** inaccurate or incomplete data.
- **Erase** your data ("right to be forgotten").
- **Restrict** or **object to** processing.
- **Data portability** — receive your data in a structured, commonly used, machine-readable format.
- **Withdraw consent** at any time where processing is based on consent.
- **Lodge a complaint** with your local data-protection authority. In the UK, this is the [ICO](https://ico.org.uk/).

To exercise any of these rights, email **[CONTACT EMAIL — please fill in]**.

### 8.3 California residents (CCPA / CPRA)

In the past 12 months we have collected the categories of personal information described in Section 2 (identifiers, account information, content you create, transaction information). We have **not** sold or shared personal information for cross-context behavioral advertising, and we do **not** use sensitive personal information for purposes beyond what's permitted by default under CPRA.

You have the right to:

- **Know** what personal information we collect, use, and disclose.
- **Delete** personal information we have collected from you.
- **Correct** inaccurate personal information.
- **Limit** use of sensitive personal information (not applicable here — we do not use any).
- **Opt out of sale or sharing** (not applicable here — we do neither).
- **Non-discrimination** for exercising your rights.

To exercise any of these rights, email **[CONTACT EMAIL — please fill in]**. We may need to verify your identity before fulfilling the request.

---

## 9. Children's privacy

The App is not directed to children under 13 (or under 16 in the EU / UK), and we do not knowingly collect personal information from them. If you believe a child has provided us with personal information, contact us and we will delete it.

---

## 10. Changes to this policy

We may update this Policy from time to time. When we do, we will revise the "Last updated" date at the top. Material changes will be communicated through an in-App notice before they take effect. Continued use of the App after a change indicates acceptance of the updated Policy.

---

## 11. Contact

For privacy questions, requests, or complaints:

**Jack Silverman**
Email: **[CONTACT EMAIL — please fill in]**

---

*This Policy is provided for general information. It is not legal advice. Consider having it reviewed by a lawyer admitted in your jurisdiction before publishing it on the App Store, Play Store, or a public website.*
