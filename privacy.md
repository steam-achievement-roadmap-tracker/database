# Privacy Policy

**Last Updated:** September 2026

This Privacy Policy describes how the **Steam Achievement Roadmap Tracker** extension handles your data.

## 1. Data Stored Locally on Your Device

To function, this extension requires certain account information. **This data is stored exclusively on your local device and is never transmitted to our servers or any third-party databases:**

- **Steam API Key & Profile ID:** Saved securely in your browser's local storage (`chrome.storage.local`) and used solely to fetch your personal achievement progress directly from Valve's Steam Web API.

## 2. Data Transmitted (User Reports)

To keep the extension's database accurate, users can submit mapping corrections (e.g., manually linking a PSNProfiles guide to the correct Steam game). If you submit a correction, we collect:

- The **PSNP Guide ID**
- The corresponding **Steam App ID** you provided
- An **Anonymized User ID** (used strictly to prevent spam and tally votes accurately)

**If you do not actively submit a correction, absolutely no data is transmitted to our servers.**

_This payload contains absolutely no personally identifiable information (PII), Steam credentials, or browsing history. It is used exclusively to update the public, open-source database for all users._

## 3. Third-Party Services

This extension communicates directly with the **Steam Web API** (`api.steampowered.com`) and Steam Community endpoints to fetch game schemas and your personal achievement progress. By using this extension, your requests are subject to Steam's standard privacy policies regarding API usage.

## 4. Chrome Web Store Required Disclosures

In strict compliance with the Chrome Web Store Developer Program Policies, we explicitly guarantee that:

- We **do not** sell your data to third parties.
- We **do not** use or transfer your data for personalized advertising.
- We **do not** use or transfer your data for lending purposes or determining creditworthiness.
- We **only** use the data we collect to provide and improve the extension's core functionality.

## 5. Contact

If you have any questions or concerns about this policy, please open an issue in this repository or reach out via the contact links provided in the extension's About section.
