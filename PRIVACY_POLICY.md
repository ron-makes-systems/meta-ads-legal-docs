# Privacy Policy for Meta Ads Integration for Fibery

**Effective Date:** 2025-12-16

## 1. Introduction

This Privacy Policy describes how the Meta Ads Integration for Fibery ("we", "our", or "the Service") collects, uses, and discloses your information when you use our integration service. This Service is designed to fetch date from your Meta Ad Accounts and synchronize it into your Fibery workspace.

## 2. Information We Collect

### 2.1 Authentication Data
When you connect your Meta account, we collect authentication tokens provided by Facebook Login to authorized access to your Meta Ad Accounts. We do not store your Facebook password.

### 2.2 Advertising Data
To fulfill the Service's purpose, we fetch the following data from the Meta Marketing API on your behalf:
*   **Ad Account Information**: Name, currency, timezone, and account status.
*   **Campaigns**: Names, status, objectives, budgets, and schedules.
*   **Ad Sets**: Names, targeting details, status, budgets, and schedules.
*   **Ads**: Names, creative details, and status.
*   **Performance Metrics**: Aggregated data such as daily spend, impressions, and clicks.

## 3. How We Use Your Information

We use the information we collect solely for the purpose of providing the Service:
*   **Synchronization**: To transfer your Meta Ads data into your designated Fibery workspace/database.
*   **Functionality**: To allow you to filter and configure which data is synced (e.g., specific ad accounts or date ranges).

**We do not:**
*   Sell your data to third parties.
*   Use your data for advertising purposes.
*   Use your data to train machine learning models.

## 4. Data Sharing and Transfer

The Service acts as a bridge between Meta and Fibery.
*   **Meta (Facebook)**: We interact with Meta's APIs to retrieve your data.
*   **Fibery**: All retrieved data is sent directly to your Fibery workspace. **Fibery is the entity responsible for the storage and persistence of your data.** This Service does not maintain a persistent database of your advertising data.

## 5. Data Retention

This Service is non-persisting regarding your business data. Data fetched from Meta is transformed in-memory and transmitted to Fibery. Once transmitted, it is not retained by our Service. Your authentication tokens may be temporarily cached or stored securely to maintain the connection, but you can revoke this access at any time.

## 6. Your Rights and Choices

### 6.1 Revoking Access
You can stop the Service from accessing your data at any time by:
1.  Disconnecting the integration within Fibery.
2.  Removing the app from your Facebook business integrations settings (https://www.facebook.com/settings?tab=business_tools).

### 6.2 Data Deletion
Since we do not store your advertising data, disconnecting the Service stops further data collection. To delete data already synced to Fibery, please manage your data directly within your Fibery workspace.

## 7. Compliance with Meta Platform Terms

We adhere to the Meta Platform Terms and Developer Policies. We only request the permissions necessary to provide the synchronization features you have requested.

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. If we make material changes, we will notify you by updating the date at the top of this policy and, where appropriate, providing notice through the Service.

## 9. Contact Us

If you have questions about this Privacy Policy, please contact us at:
[Insert Contact Email or Support Link Here]
