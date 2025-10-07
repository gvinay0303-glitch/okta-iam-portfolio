# Okta IAM Portfolio

This repository contains *hands-on Identity & Access Management (IAM) projects* using  
*Okta Workforce Identity* and *Microsoft Entra (Azure AD)*.  

It demonstrates practical implementations of:
- Single Sign-On (SSO) with SAML/OIDC
- Multi-Factor Authentication (MFA)
- Lifecycle Management (LCM)
- Access Policies & Role-Based Access
- Active Directory (AD) Integration
- App Integrations & Okta Automation via APIs

---

## 🔑 Skills Demonstrated
- Okta Workforce Identity & Universal Directory
- SSO (SAML/OIDC) with session handling
- MFA configuration (Okta Verify, SMS, Email factors)
- Role-based access & conditional policies
- Active Directory (AD) integration with Okta
- Automated provisioning & de-provisioning
- Okta API automation workflows
- Security best practices in IAM

---

## 📂 Projects Included

1. [SSO Setup](docs/SSO_Setup.md)  
   - Configured Okta as Identity Provider (IdP)  
   - Implemented SAML-based authentication  
   - Tested login/logout session handling  

2. [MFA Configuration](docs/MFA_Config.md)  
   - Enabled MFA for workforce users  
   - Configured Okta Verify, SMS, Email factors  
   - Enforced adaptive MFA policies  

3. [Lifecycle Management](docs/Lifecycle_mgmt.md)  
   - Automated user provisioning & de-provisioning  
   - Configured JIT provisioning  
   - Managed access based on lifecycle state  

4. [Access Policies](docs/Access_Policies.md)  
   - Designed conditional access rules  
   - Created role-based session policies  
   - Implemented adaptive authentication  

5. [Active Directory Integration](docs/AD_Integration.md)  
   - Integrated Okta with Microsoft AD  
   - Synced users & groups between AD and Okta  
   - Configured hybrid identity model  

6. [App Integration (SAML/OIDC)](docs/App_Integration.md)  
   - Configured SAML-based app integrations  
   - Integrated OIDC apps for modern auth  
   - Tested enterprise application access  

7. [Okta API Automation](docs/Okta_Automation.md)  
   - Automated user creation/deactivation via Okta APIs  
   - Implemented bulk user onboarding scripts  
   - Scheduled automation for identity cleanup
## Okta API Automation

This section demonstrates how I used Okta APIs to automate user management and identity operations.

### Steps Implemented
1. Created an API token in Okta Admin Console.
2. Integrated Okta with Postman using the API token.
3. Configured environment variables for domain, userId, and API key.
4. Executed GET /api/v1/users/{userId} to retrieve user details.
5. Validated token usage and expiry date updates after API execution.

### Proof of Work
All steps are documented with screenshots in /docs/screenshots/okta_api_automation/.

Example result:
> Successfully retrieved user details using Okta API configured in Postman.

---

## 📅 Project Timeline
See detailed work timeline here: [TIMELINE.md](TIMELINE.md)  

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 📊 Project Timelines

- [Report 1: SSO, MFA, Access Policies, App Integration](reports/Timeline_SSO_MFA_Access_App.md)
- [Report 2: Lifecycle, SCIM, AD, API Automation](reports/Timeline_Lifecycle_SCIM_AD_API.md)


✅ This portfolio demonstrates *2 years of IAM hands-on experience (Sep 2023 – Aug 2025)*, covering SSO, MFA, AD Integration, Lifecycle Management, and Automation.

---

## 📌 About This Portfolio  
This portfolio is part of my journey as an *Identity & Access Management (IAM) professional, showcasing **practical projects* that demonstrate my ability to implement *enterprise-grade identity solutions*.  


📧 Contact: gvinay0303@gmail.com  
🔗 LinkedIn:https://www.linkedin.com/in/vinay-g-8290b8385/
