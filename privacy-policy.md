---
layout: default
title: Privacy Policy – Family Care Blueprint
---

# Privacy Policy

**Family Care Blueprint**
**Effective Date:** June 23, 2026
**Last Updated:** June 23, 2026

---

## 1. Overview

Family Care Blueprint Growth Engine ("we," "our," or "the Application") is an internal analytics tool that connects to Pinterest via the official Pinterest API v5. This Privacy Policy describes how the Application collects, uses, stores, and protects data accessed through that integration.

This Application is operated for internal business intelligence purposes only. It is not a consumer-facing product and does not serve end users or collect data from visitors to this policy page.

---

## 2. Data We Access

Through the Pinterest API v5, the Application accesses the following data from the Family Care Blueprint Pinterest Business account:

**Pin Metadata (read-only)**
- Pin ID
- Pin title and description
- Destination URL (link)
- Board name and board ID
- Image URL
- Pin creation date

**Pin Analytics (read-only)**
- Impressions
- Saves
- Pin clicks
- Outbound clicks
- Closeups

**Account Information (read-only)**
- Business account name and ID (used solely for token validation)

The Application does **not** access:
- Follower data or audience demographics
- Private messages or direct messages
- Advertiser or campaign data
- Any data from other Pinterest users

---

## 3. How We Use This Data

Data accessed through the Pinterest API is used exclusively for:

- **Content analytics** — evaluating which pins and content themes perform best
- **Performance reporting** — generating internal reports on reach, engagement, and click-through behavior
- **Business intelligence** — informing content strategy and editorial planning for the Family Care Blueprint account

Data is never used for:
- Advertising targeting
- Resale or redistribution to third parties
- Training machine learning models for external use
- Any purpose beyond internal analytics and reporting

---

## 4. Data Storage

Accessed data is stored locally in a SQLite database on a private server controlled by the account owner. No Pinterest data is transmitted to external third-party services, cloud analytics platforms, or data brokers.

The database is not publicly accessible and is protected by server-level access controls.

---

## 5. Data Retention

Pin metadata and analytics data are retained for as long as they are operationally useful for content performance analysis. Data may be deleted at any time at the account owner's discretion. When the Application is decommissioned, all locally stored data will be deleted.

OAuth access tokens and refresh tokens are stored in environment configuration files on the private server and are never logged, transmitted, or committed to version control.

---

## 6. No Sale of Personal Information

We do not sell, rent, lease, or otherwise transfer any data — including data accessed via the Pinterest API — to any third party for commercial purposes.

---

## 7. Third-Party Services

This Application integrates with:

**Pinterest API v5**
Data access is governed by Pinterest's own Terms of Service and Privacy Policy. Our use of the Pinterest API complies with the [Pinterest API Terms of Service](https://developers.pinterest.com/terms/) and is limited to the scopes approved for this application (`pins:read`, `boards:read`, `user_accounts:read`).

No other third-party data integrations are used in connection with Pinterest data.

---

## 8. OAuth Authorization

This Application uses the Pinterest OAuth 2.0 Authorization Code Flow to obtain permission to access the Family Care Blueprint Pinterest account. Access tokens are:

- Stored only in private server environment configuration
- Never exposed in application logs, source code, or public repositories
- Automatically refreshed server-side without requiring additional user authorization
- Revocable at any time via Pinterest account settings at [pinterest.com/settings/security](https://www.pinterest.com/settings/security)

---

## 9. Your Rights

As the Pinterest account owner, you retain full control over data access at all times. You may revoke this Application's access to your Pinterest account at any time by:

1. Navigating to **Pinterest → Settings → Security and privacy → Apps with account access**
2. Locating "Family Care Blueprint Growth Engine"
3. Clicking **Revoke access**

Upon revocation, the Application will immediately lose access to your Pinterest data. Any data already stored locally can be deleted upon request.

---

## 10. Security

We implement reasonable technical safeguards to protect data accessed through the Pinterest API, including:

- Server-level access restrictions on the database and environment files
- Environment variable storage for all credentials (no plaintext secrets in source code)
- Atomic token refresh to prevent credential loss
- Monitoring and alerting for token expiry and authentication failures

---

## 11. Changes to This Policy

We may update this Privacy Policy from time to time. The "Last Updated" date at the top of this document will reflect any changes. Continued use of the Application following an update constitutes acceptance of the revised policy.

---

## 12. Contact

For questions about this Privacy Policy or data handling practices, contact:

**Email:** holmesbrandon810@gmail.com

---

*This Privacy Policy applies solely to the Family Care Blueprint Growth Engine application and its use of the Pinterest API. It does not apply to the Family Care Blueprint Pinterest account itself or its public content.*
