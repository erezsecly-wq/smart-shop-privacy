---
title: Privacy Policy — Smart Shop ES
---

# Privacy Policy — Smart Shop ES

**Publisher:** EMNY Tech  
**Contact:** support.emnytech@gmail.com  
**Last updated:** April 23, 2026

## 1. Who we are
Smart Shop ES ("the App") is developed by EMNY Tech. This policy explains what information the App collects, how it is used, and your rights.

## 2. Information the App collects

**Account information.** When you sign in, we store your email address and an anonymous user ID through Firebase Authentication (Google LLC).

**Your lists and shopping data.** Shopping lists, archived lists, expenses, store names, product names, prices, and category preferences you create are stored in Firebase Realtime Database (Google LLC) so they sync between your devices and the people you share a list with.

**Receipt images.** When you scan a receipt, the image is sent to Google's Gemini API, and as a fallback to Groq Inc.'s OCR API, solely to extract text (store name, items, prices). Images are not stored on our servers. Google and Groq may retain them temporarily per their own policies, linked below.

**Voice input (optional).** When you use voice input, speech recognition is processed on-device by the operating system's speech recognition service. No audio is sent to our servers.

**Device permissions.** The App requests Camera (to capture receipts), Photo Library (to pick an existing receipt image), Microphone (for voice input), and Internet (to sync with Firebase and call the OCR APIs).

**API keys.** If you enter your own Gemini or Groq API keys, they are stored only on your device using encrypted local storage and are never transmitted to EMNY Tech.

## 3. Information the App does NOT collect
- No advertising identifiers
- No third-party analytics
- No location data
- No contacts
- No crash reporting to us beyond Firebase's standard operational logs

## 4. How we share information
- **Google LLC** — Firebase Authentication, Firebase Realtime Database, Gemini API. Subject to Google's privacy policy: https://policies.google.com/privacy
- **Groq Inc.** — OCR fallback. Subject to Groq's privacy policy: https://groq.com/privacy-policy
- We do **not** sell your data to anyone.

## 5. Data retention
- Active lists remain until you delete them.
- Archived lists follow the retention period you choose in Settings (1 month to unlimited).
- Deleting your account removes all data associated with it from our databases within 30 days.

## 6. Your rights
You may:
- View and edit all your data directly from the App
- Export your data using the Backup feature in Settings
- Delete any item, list, or archive at any time
- Request full account deletion by emailing support.emnytech@gmail.com

EU/UK users have rights under GDPR; Israeli users have rights under the Protection of Privacy Law, 1981. Contact us to exercise them.

<a id="data-deletion"></a>
## 6a. Deleting some of your data (without deleting your account)
You can delete portions of your data without removing your account:

**In-app deletion (immediate):**
- **Individual list items** — tap the X next to any item, or long-press to delete multiple
- **Whole shopping lists** — open a list → menu → Delete list
- **Archived lists** — open Archive tab → swipe a list → Delete
- **Expense entries** — open Expenses tab → tap an entry → Delete
- **Saved prices** — open Prices tab → tap a price → Delete
- **Stored API keys** — Settings → clear keys (if you previously entered your own)

**By request (within 30 days):**
For data we cannot delete from inside the app, send an email to **support.emnytech@gmail.com** with the subject line `Delete data — Smart Shop ES` and describe what you want removed (for example: "delete all my receipt scans" or "delete my expense history before 2026"). We will confirm by email within 7 days and complete the deletion within 30 days.

The categories of data that can be deleted on request:
- Authentication metadata (login timestamps)
- Backup files you uploaded
- Anonymous usage logs (Firebase operational only)

Deleting partial data does **not** delete your account or other data — your remaining lists, settings, and login stay intact.

<a id="account-deletion"></a>
## 6b. Deleting your account
To permanently delete your Smart Shop ES account and all associated data:

1. Send an email to **support.emnytech@gmail.com**
2. Use the subject line: `Delete account — Smart Shop ES`
3. Include the email address you registered with so we can verify ownership

**What gets deleted:**
- Your authentication record (email, user ID)
- All your shopping lists (active and archived)
- All your expenses, saved prices, and store data
- All backup files associated with your account
- Any cached receipt images on Google Gemini / Groq (per their retention policies)

**Timeline:** We will confirm receipt of your request within 48 hours and complete the deletion within 30 days, as required by GDPR and the Israeli Protection of Privacy Law. You will receive a confirmation email when deletion is complete.

**What is retained:** None of your personal data. Aggregate, fully-anonymized statistics (e.g., "100 users scanned a receipt today") may remain but cannot be linked back to you.

**Note:** Deleting your account is irreversible. If you only want to remove some data, see [section 6a](#data-deletion) above.

## 7. Children
The App is not directed to children under 13 (or 16 in the EU).

## 8. Changes
We may update this policy. The "Last updated" date above will change accordingly.

## 9. Contact
**EMNY Tech** — support.emnytech@gmail.com
