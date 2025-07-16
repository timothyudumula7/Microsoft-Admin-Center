# 📘 Intune Device Configuration Policy Setup

This documentation provides a step-by-step guide on how to create and deploy a **Device Configuration Policy** using Microsoft Intune. Configuration policies allow administrators to manage settings, security features, and device behavior for users across an organization.

---

## 🧭 Overview

In this tutorial, we will:
- Create a new Device Configuration Profile
- Define settings (e.g., password, encryption, restrictions)
- Assign the profile to users or device groups
- Review and deploy the configuration

---

## 🛠️ Step-by-Step Instructions

### 1️⃣ Navigate to Device Configuration

Go to the Microsoft Intune Admin Center:

- Select **Endpoint Security** > **Device Configuration**
- Click on **Create Policy**

> ![Managed Device Policy Create Intro](https://github.com/user-attachments/assets/66172dbf-55b0-42f7-bfc0-1fd76148a51c)

---

### 2️⃣ Create a Profile

- Select the **Platform** (e.g., *Windows 10 and later*)
- Choose a **Profile Type** based on your requirements (e.g., settings catalog, templates)

> ![Create Profile](https://github.com/user-attachments/assets/2143a757-03fb-4488-9510-29092f637c30)

---

### 3️⃣ Configure Settings

- Browse and select configuration options (e.g., BitLocker settings, USB restrictions, password complexity)
- Save after adding desired policies

> ![Pick Settings](https://github.com/user-attachments/assets/f9ebd8a3-a5ad-4448-86b7-a0a01180ac95)

---

### 4️⃣ Scope Tags (Optional)

- Add **scope tags** for RBAC scenarios
- Helps delegate control to specific admins or departments

> ![Scope Tags](https://github.com/user-attachments/assets/a7b7d023-0749-42e5-9fa8-61526889642c)

---

### 5️⃣ Assign to Groups or Users

- Assign the profile to specific groups (e.g., *All Devices*, *IT Department*, *Mohan’s Devices*)
- You can include or exclude groups for more control

> ![Assignments](https://github.com/user-attachments/assets/7786bfbe-ada4-41cb-a803-2cd226c0f77a)

---

### 6️⃣ Review & Create

- Review the summary of all configuration settings
- If everything looks good, click **Create** to apply the policy

> ![Summary](https://github.com/user-attachments/assets/e4979c6e-8683-4c21-bc64-5fe4ac4b899f)

---

## ✅ Outcome

Your Device Configuration Profile is now active. It will apply the specified settings to all assigned users or devices. This helps enforce security, productivity, and compliance in your organization.

---

## 📎 Additional Notes

- Policies may take several minutes to apply on the device
- Conflicting policies will be resolved based on priority
- Always test policies in a lab before rolling out organization-wide

---

## 📬 Questions?

If you have any questions or need support, feel free to open an issue in this repository or contact your Intune administrator.

---
