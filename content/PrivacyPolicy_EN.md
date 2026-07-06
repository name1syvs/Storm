# Privacy policy

**Storm** mobile application  
**Version in force:** 10 April 2026

*This document is a template for publication. It does not constitute legal advice.*

---

## Preamble

This Privacy Policy explains how the **Storm** mobile application (“the **App**”) collects, uses, and protects your personal data.

It is intended to align with:

- the General Data Protection Regulation (EU) 2016/679 (“GDPR”);
- the Belgian Act of 30 July 2018 on the protection of natural persons with regard to the processing of personal data; and
- relevant guidance from European data-protection authorities.

By using the App, you acknowledge that you have read this Policy and understand the processing described herein, within the limits of your consent and applicable law.

## 1. Data controller

The controller of personal data collected through Storm is:

| | |
|---|---|
| **Identity** | The individual who operates the Storm mobile application (natural person) |
| **Capacity** | Individual developer |
| **Country** | Belgium |
| **Contact email** | contact@getstorm.app |

The **legal name** of the controller is not published on this page for personal safety. It is disclosed to supervisory authorities where the law requires it, and to individuals who submit a **valid** access or other GDPR request via the email above, when identification is necessary to handle the request.

The controller determines the purposes and means of processing and undertakes to comply with applicable data-protection law.

## 2. Data collected

### 2.1 Data you provide directly

When you create an account and use the App, the following may be collected:

| Data | Purpose |
|---|---|
| **Email address** | Required for account creation and authentication |
| **Password** | Stored using secure hashing by the authentication provider (not stored in plain text by the publisher) |
| **First and last name** | Account identification |

### 2.2 Data collected automatically or through permissions

Depending on your choices and device permissions:

| Data | Notes |
|---|---|
| **Location** | Collected or accessed **only when** you enable location-related features, to support departure planning and related functionality. It may be processed on your device and, where the service requires it, via the backend. **It is not used to build a long-term location profile for advertising.** Retention is limited to what is needed for the feature and for short-term technical or security logs as described below. |
| **Calendar / event data** | If you grant calendar access, the App may read **event information** (e.g. titles, start/end times, and related metadata your system exposes) to anticipate departures. Processing is tied to the App’s core features. Data may be processed **on device** and, if you use cloud-backed features, **in the project database hosted in the EU (Ireland)** only to the extent required for the service you use. |
| **Technical data** | Such as session identifiers, connection timestamps, device type, and OS version, as needed for **security**, **fraud prevention**, and **operation** of the infrastructure (e.g. Supabase authentication and database access). |

### 2.3 Data not collected

The App does **not** intentionally collect:

- payment or bank card data (the App is currently free);
- “special category” data under Article 9 GDPR (health, religion, etc.) beyond what you might voluntarily type into calendar titles (which we do not use for profiling);
- your contacts, SMS, or call logs as a dedicated dataset;
- private communications between users as a messaging product (Storm is not a general-purpose messenger).

If the scope of the App changes, this Policy will be updated accordingly.

## 3. Purposes and legal bases

Processing relies on GDPR Article 6 bases, as applicable:

| Processing | Legal basis (summary) |
|---|---|
| **Account management** | Performance of a contract / steps prior to contract (Art. 6(1)(b)) — necessary to provide the service |
| **Authentication and security** | Contract (Art. 6(1)(b)) and, where applicable, legitimate interests (Art. 6(1)(f)) in securing accounts and preventing abuse |
| **Location** | **Consent** (Art. 6(1)(a)) where required — you can withdraw consent via device settings; some features may then be unavailable |
| **Calendar access** | **Consent** and/or **contract** (Art. 6(1)(a) / (b)), depending on how access is requested on your platform — necessary for calendar-based departure features |
| **Technical logs and security** | Legitimate interests (Art. 6(1)(f)) in secure, stable operation; **legal obligation** (Art. 6(1)(c)) where applicable |
| **Legal compliance** | Legal obligation (Art. 6(1)(c)) |

The App does **not** use a separate behavioural-advertising or “analytics marketing” stack. Operational data processed through Supabase is described in Sections 2 and 5.

## 4. Retention

Personal data is kept only as long as necessary for the purposes above:

- **Account data** (email, name): for the life of the account; deleted within a **reasonable period** (e.g. up to **30 days**) after account deletion, unless a longer retention is required by law.
- **Location**: processed for real-time functionality; **not kept for long-term location history** for advertising. Server-side copies, if any, are minimized and rotated in line with security practices.
- **Calendar-derived data** on backend: retained only as needed for features you use; removed or anonymized when no longer needed for those features.
- **Technical / security logs** (e.g. via infrastructure): typically up to **12 months**, unless a shorter or longer period is required for security or legal reasons.

After these periods, data is securely deleted or irreversibly anonymized where applicable.

## 5. Recipients and transfers

### 5.1 Processor: Supabase

Data is hosted and processed using **Supabase** as a **processor** under the GDPR.

- **Supabase Inc.** is established at 970 Toa Payoh North, Singapore.  
- **The Storm project data is hosted in the European Union (Ireland region)** under the project configuration in use.

Where processing involves access from outside the EEA or involves Supabase group companies, appropriate safeguards (such as **standard contractual clauses** approved by the European Commission, Art. 46 GDPR) may apply.

### 5.2 No sale of personal data

Personal data is **not sold**, rented, or traded for commercial advertising. Data is **not** shared with ad networks for profiling.

### 5.3 Other recipients

Other recipients may include **infrastructure or communications providers** strictly necessary to operate the App (e.g. app distribution platforms), under their own privacy terms.

## 6. Your rights

Under the GDPR and Belgian law, you have the right to:

- **Access** (Art. 15) — confirmation of processing and a copy of your data  
- **Rectification** (Art. 16) — correction of inaccurate data  
- **Erasure** (Art. 17) — deletion (“right to be forgotten”), subject to legal retention duties  
- **Restriction** (Art. 18) — limit processing in defined cases  
- **Portability** (Art. 20) — receive certain data in a structured, machine-readable format  
- **Object** (Art. 21) — object to processing based on legitimate interests, where applicable  
- **Withdraw consent** — for location or other consent-based processing, without affecting the lawfulness of prior processing

**To exercise your rights**, email: **contact@getstorm.app**

The controller will respond within **one month** of receipt, extendable by up to **two further months** for complex or numerous requests, with prior notice.

You may also lodge a complaint with the **Belgian Data Protection Authority (GBA/APD)**:

- Website: https://www.autoriteprotectiondonnees.be  
- Address: Rue de la Presse 35, 1000 Brussels, Belgium  
- Email: contact@apd-gba.be  

## 7. Security

Appropriate technical and organizational measures are applied, including:

- **Password hashing** via the authentication provider (e.g. bcrypt through Supabase Auth)  
- **HTTPS/TLS** for data in transit  
- **Two-factor authentication (2FA)** — **available when you enable it** on your account through the authentication options offered by the provider  
- **Access controls** to databases (e.g. row-level security policies where configured)  
- **Monitoring and logging** of infrastructure access for security

In the event of a personal data breach likely to result in a high risk to your rights and freedoms, you will be notified where required by law (including Art. 34 GDPR).

## 8. Children

The App is **not directed at children under 16**. If you are under 16, do not use the App or provide personal data. If the controller becomes aware that personal data was collected from a child under 16 without appropriate consent, steps will be taken to delete it promptly.

Parents or guardians who believe a child has provided data may contact: **contact@getstorm.app**

## 9. Changes to this policy

This Policy may be updated to reflect changes to the App, new data practices, or legal requirements. For **material changes**, users may be informed via an in-app notice or email where appropriate. The **last updated** date is shown at the top of this document.

Continued use of the App after notice of updates may constitute acknowledgment of the updated Policy, where permitted by law.

**Last updated:** 10 April 2026

## 10. Data protection contact

For any question about this Privacy Policy or the processing of your personal data, contact:

| | |
|---|---|
| **Contact** | Data protection / publisher (Storm) |
| **Email** | contact@getstorm.app |

Requests will be handled diligently and in line with your statutory rights.
