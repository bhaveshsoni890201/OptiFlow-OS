# OptiFlow OS License Agreement

**Version 1.0 — Effective upon adoption**

Copyright © OptiFlow Technologies. All rights reserved.

---

## Overview

OptiFlow OS is distributed under a dual licensing model:

1. **AGPL v3 — Community Edition** — free, self-hosted, open source
2. **Commercial License — Enterprise Edition** — paid, SaaS-capable, private modifications

This file defines the terms for both editions, trademark and branding protection, and the boundary between Community and Enterprise features.

---

## Part I: Community Edition (AGPL v3)

### 1.1 Grant

The Community Edition of OptiFlow OS is licensed under the **GNU Affero General Public License v3 (AGPL v3)**.

A copy of the AGPL v3 is provided in [LICENSE-AGPL.md](LICENSE-AGPL.md).

### 1.2 What AGPL v3 Means

| Right | Grant |
|-------|-------|
| Use | ✅ Free for any lawful purpose |
| Modify | ✅ You may modify the source code |
| Distribute | ✅ You may distribute copies |
| SaaS / Cloud | ✅ Permitted, but **all modifications must be shared back** under AGPL |
| Private modification | ✅ Free for internal use |
| Charge for service | ✅ You may charge for hosting/support |

### 1.3 AGPL v3 Obligation

If you modify the Community Edition and make it available to third parties as a network service (including but not limited to SaaS, cloud hosting, or managed service), you **must** provide the complete corresponding source code of your modifications to all users of that service, in accordance with Section 13 of the AGPL v3.

### 1.4 Community Edition Feature Scope

The Community Edition includes all core modules:

- Authentication (login, OTP, forgot/reset password, profile wizard)
- Doer Panel (tasks, worklists, attendance, leave, training, tickets, notifications, profile)
- Captain Panel (dashboard, rescue queue, team roster, worklists, leave approvals, attendance monitor, training assignment, tickets)
- Admin Panel (dashboard, employee management, department management, attendance, leave, training, tickets, basic insights, notifications)
- Rescue Management
- Offline Support
- Multi-Language (EN, HI, Hinglish)
- Theme Support (light, dark, high-contrast)

### 1.5 Community Edition Exclusions

The following features are **not** included in the Community Edition and require a Commercial License:

- AI Task Prioritization
- AI Rescue Prediction
- AI Performance Analysis
- AI Workflow Recommendations
- Advanced Analytics Dashboard
- Doer 360° Performance View
- Captain Index Scoring
- Weekly Review Automation
- Marketplace for Extensions
- Custom Integration Framework
- Audit Log Retention (>90 days)
- Role-Based Access Control Templates
- API Rate Limit Overrides
- Priority Support SLA

OptiFlow Technologies reserves the right to move additional features to the Enterprise Edition over time.

---

## Part II: Commercial License (Enterprise Edition)

### 2.1 When You Need a Commercial License

A Commercial License is required if:

| Use Case | Community (AGPL) | Commercial |
|----------|-----------------|------------|
| Self-hosted for your organization | ✅ Free | Optional |
| Modified internally, no external users | ✅ Free | Optional |
| SaaS offering to third parties (modifications private) | ❌ AGPL requires source sharing | ✅ Required |
| SaaS offering to third parties (modifications shared) | ✅ AGPL compliant | Optional |
| White-label / OEM distribution | ❌ Not permitted | ✅ Required |
| Embedding in proprietary product | ❌ AGPL requires parent project also AGPL | ✅ Required |
| Enterprise features access | ❌ Not available | ✅ Required |
| More than 500 employees | ✅ Free | Recommended |

### 2.2 Commercial License Grant

A Commercial License grants you:

1. **Right to Use** — Install and run OptiFlow OS Enterprise Edition on any number of servers
2. **Right to Modify** — Modify the source code for your internal use **without** AGPL copyleft obligations
3. **Right to SaaS** — Offer OptiFlow OS as a cloud service to third parties without sharing modifications
4. **Right to Embed** — Integrate OptiFlow OS into your proprietary products
5. **Enterprise Features** — Access to all features listed in Section 1.5
6. **Support** — Priority support with SLA (terms defined separately)

### 2.3 Commercial License Restrictions

Even with a Commercial License, you **may not**:

1. **Remove or alter** any copyright, trademark, or branding notices
2. **Resell** OptiFlow OS as a standalone product without substantial value-add
3. **Transfer** the license to a competitor
4. **Circumvent** or disable any feature gating or license enforcement mechanisms
5. **Use** the license to violate applicable law

---

## Part III: Trademark and Branding

### 3.1 Trademarks

"**OptiFlow OS**", "**OptiFlow**", the OptiFlow logo, and any related names, marks, and logos are registered and unregistered trademarks of OptiFlow Technologies.

### 3.2 Branding Requirements

All distributions of OptiFlow OS, whether Community or Commercial, **must**:

1. Retain the OptiFlow OS logo and branding in the application header and sidebar
2. Retain the "Powered by OptiFlow OS" attribution in the footer
3. Retain all copyright notices in source code headers
4. Not remove, obscure, or alter any branding elements

### 3.3 White-Label License

Removing or replacing OptiFlow branding requires a separate **White-Label License**, available exclusively under the Commercial License with additional fees. Unauthorized white-labeling is a violation of this license and applicable trademark law.

### 3.4 Logo and Asset Usage

Use of the OptiFlow logo, brand assets, and design assets is governed by the [OptiFlow Brand Guidelines](docs/branding/BRAND_GUIDELINES.md). You may not:

1. Modify the logo or brand assets
2. Use the logo in a way that implies endorsement of third-party products
3. Use the logo in misleading or deceptive ways
4. Register domain names containing "optiflow" without written permission

### 3.5 Trademark Violations

Unauthorized use of OptiFlow trademarks, including but not limited to passing off, cybersquatting, or confusingly similar marks, will be pursued to the fullest extent of the law.

---

## Part IV: Commercial Restrictions

### 4.1 SaaS Resale Restriction

You may not offer OptiFlow OS (Community or Enterprise) as a paid, standalone SaaS product to third parties without a valid Commercial License. "Standalone" means OptiFlow OS is the primary value being offered, even if bundled with other services.

Managed hosting for your own organization's employees is always permitted.

### 4.2 White-Label Restriction

You may not remove, replace, or obscure OptiFlow OS branding, logos, or attribution without a White-Label License. This includes:

- Replacing the application name in the UI
- Removing the footer attribution
- Replacing logos with your own branding
- Distributing OptiFlow OS under a different name

### 4.3 Competitive Restriction

If you are a direct competitor of OptiFlow Technologies, you may not use the Community Edition to offer a competing service. A "direct competitor" is any entity offering an operations, HRMS, or workflow management platform targeting Indian MSMEs.

### 4.4 Marketplace Restriction

The OptiFlow Marketplace (when launched) is governed by separate terms of service. Extensions and integrations distributed through the Marketplace may have their own licenses.

---

## Part V: Future Features and Modules

### 5.1 AI Module License

All AI-powered features (task prioritization, rescue prediction, performance analysis, workflow recommendations) are licensed exclusively under the Commercial License. The source code for AI modules may be withheld from the Community Edition.

### 5.2 Marketplace

The OptiFlow Extension Marketplace, when launched, is governed by separate terms. OptiFlow Technologies reserves the right to:

- Approve or reject extensions
- Set revenue sharing terms
- Establish extension certification requirements
- Modify marketplace terms

### 5.3 Future Editions

OptiFlow Technologies may introduce additional editions (e.g., "Ultimate", "Cloud") with different feature sets and pricing. The Community Edition will always remain free under AGPL v3, but may not include all features of newer editions.

---

## Part VI: Disclaimer of Warranties

**THE OPTIFLOW OS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.**

IN NO EVENT SHALL OPTIFLOW TECHNOLOGIES BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## Part VII: Limitation of Liability

To the maximum extent permitted by applicable law, in no event shall OptiFlow Technologies be liable for any special, incidental, indirect, or consequential damages whatsoever (including, but not limited to, damages for loss of profits, loss of data, business interruption, or loss of business information) arising out of the use or inability to use the software.

---

## Part VIII: Termination

### 8.1 Automatic Termination

This license terminates automatically if you violate any of its terms.

### 8.2 Effect of Termination

Upon termination:

1. All rights granted under this license cease immediately
2. You must cease all use of the software
3. You must delete all copies of the software in your possession

### 8.3 Survival

The following sections survive termination: Part III (Trademark and Branding), Part VI (Disclaimer), Part VII (Limitation of Liability), Part IX (Governing Law).

---

## Part IX: Governing Law

This license shall be governed by and construed in accordance with the laws of India. Any disputes arising under this license shall be subject to the exclusive jurisdiction of the courts of Mumbai, Maharashtra.

---

## Part X: How to Obtain a Commercial License

To obtain a Commercial License or inquire about pricing:

| Channel | Contact |
|---------|---------|
| **Email** | licensing@optiflowos.com |
| **Website** | https://optiflowos.com/pricing |
| **Sales** | Enterprise sales inquiries: enterprise@optiflowos.com |

Commercial Licenses include:
- Enterprise Edition access
- Priority support with SLA
- SaaS deployment rights
- Private modification rights
- Custom integration assistance

---

*OptiFlow OS — Operating System for Indian MSMEs*

*Copyright © OptiFlow Technologies. All rights reserved.*
