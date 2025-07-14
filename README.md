# iam-lifecycle-simulation-scim-entra-okta
A hands-on project simulating identity lifecycle and SCIM-based provisioning using Azure Entra ID and Okta.
# 🛡️ IAM Lifecycle Automation Project

This project replicates a **real-world Identity and Access Management (IAM)** environment using free tools like Azure Entra ID and Okta. It simulates user provisioning through SCIM-like workflows, multi-factor authentication (MFA), SAML-based single sign-on (SSO), and lifecycle automation using an HR data source.

---

## 🧰 Tools Used
- **Azure Entra ID**
- **Okta**
- **Excel (simulating HR system)**
- **SCIM-style provisioning**
- **Screenshots**

---

## ⚙️ What This Project Covers

### 🔄 Lifecycle Automation
- HR adds user in Excel (HR system/ ex. Workday)
- User is created in IDP (Entra ID or Okta)
- Group assignment & app access automated

### 🔐 Access Governance
- MFA policies & Conditional Access
- SSO with SAML
- Least Privilege & Access Reviews

### 🔁 SCIM Provisioning (Simulated)
Provisioning based on department:
- Finance users → Finance group → Finance apps

---

## 🧾 IAM Lab Summary

### 🔹 Azure / Entra ID
- Created users
- Assigned security groups
- Enforced MFA
- Built conditional access policies

### 🔹 Okta
- Created users/groups
- Enabled MFA with Okta Verify
- Configured SSO (SAML)
- Created custom attribute: `departmentCode`

---

## 📂 Project Structure

```bash
📁 iam-lifecycle-simulation-scim-entra-okta/
├── README.md
├── user_data.csv
├── provisioning_steps.md
├── screenshots/
│   └── iam-summary.png
├── flows/
│   └── scim-lifecycle-flow.png
